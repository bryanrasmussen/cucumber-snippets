Cucumber snippets for Sublime Text
==================================

## How to get ##

 1. Go to Packages/User
 2. git clone git@github.com:verybigman/cucumber-snippets.git
 3. Be happy!

## How to use ##

__Steps:__

__cgiven__ -> tab
```ruby
Given /^stepname $/ do
  
end
```
__cgivenr__ -> tab
```ruby
Given /^stepname "regex"$/ do |var|
  
end
```
__cwhen__ -> tab
```ruby
When /^stepname $/ do
  
end
```
__cwhenr__ -> tab
```ruby
When /^stepname "regex"$/ do |var|
  
end
```
__cthen__ -> tab
```ruby
Then /^stepname $/ do
  
end
```
__cthenr__ -> tab
```ruby
Then /^stepname "regex"$/ do |var|
  
end
```

__Feature:__

__cfeat__ -> tab
```ruby
Feature: About
  In order ...
  As a ...
  I want ...
```
__cscen__ -> tab
```ruby
Scenario: Action
  Given I stepname
  When I stepname
  Then I stepname
```

'stepname' is sample and it not text.

__Best regards!__

