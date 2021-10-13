---
title: seed-fu
categories: ['ruby']
---
## [seed-fu](https://github.com/mbleigh/seed-fu)

### Advanced seed data handling for Rails, combining the best practices of several methods together.


    User.seed do |s|
      s.id    = 1
      s.login = "jon"
      s.email = "jon@example.com"
      s.name  = "Jon"
    end

    User.seed do |s|
      s.id    = 2
      s.login = "emily"
      s.email = "emily@example.com"
      s.name  = "Emily"
    end
