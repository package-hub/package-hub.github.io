---
title: drf-writable-nested
categories: ['python']
---
## [drf-writable-nested](https://github.com/beda-software/drf-writable-nested)

### Writable nested model serializer for Django REST Framework

We have a special mixin `UniqueFieldsMixin` which solves this problem.
The mixin moves` UniqueValidator`'s from the validation stage to the save stage.

If you want more details, you can read related issues and articles:
https://github.com/beda-software/drf-writable-nested/issues/1
http://www.django-rest-framework.org/api-guide/validators/#updating-nested-serializers
