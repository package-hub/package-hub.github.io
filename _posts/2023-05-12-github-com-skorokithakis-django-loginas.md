---
title: django-loginas
categories: ['python']
---
## [django-loginas](https://github.com/skorokithakis/django-loginas)

### "Log in as user" for the Django admin.


If you already have a logout view, you can modify to login the original user again after having had a "login as" session. Here's an example:

```python
class LogoutView(LogoutView):
    template_name = 'myapp/logged_out.html'

    @method_decorator(never_cache)
    def dispatch(self, request, *args, **kwargs):
        from loginas.utils import restore_original_login
        restore_original_login(request)
        return redirect('myapp:login')
```
