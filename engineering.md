---
layout: page
title: Engineering
permalink: /engineering/
---

## `Role Description`

- Insert bullets here on what it is the engineering team does

## `Practices`
* DevOps Culture
* [Test-Driven Development]("{site.baseurl}/submissions/engineering/TDD.md")
* Pairing

## `How`

- Insert bullets here on HOW we get perform this role

## `Sample Code`

```ruby
class User < ApplicationRecord
  has_many :posts
  belongs_to :group
  
  def full_name
    "#{first_name} #{last_name}"
  end
end
```