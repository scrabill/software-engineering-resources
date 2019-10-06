# Software Engineering Resources

A collection of resources, cheatsheets and code snippets I found helpful (or kept forgetting) during my Flatiron Software Engineering bootcamp.

## To-Dos

- What is the difference between `find`, `find_by` & `find_by_id`?
- Sessions
- RESTful routes
- Atom packages

## Bundler

Run the following code to have bundler create a new Ruby project for you

```ruby
bundler gem name_of_your_project_repo
```

## Forms

A hidden input for editing or deleting data with a form

```
<input type="hidden" name="_method" value="patch">
```

## Nokogiri

Open a new website for scraping

```ruby
Nokogiri:HTML(open("http://www.example.com"))
```

## Rake

See a list of all available Rake tasks.

```ruby
Rake -T
```

### Seed Data

1. Within the `db` folder, create a file named `seeds.rb`.
1. Create object instances. For example:
`Dog.create(:name => "Fido", :breed => "mutt")`. Using `create` as opposed to `new` creates the Ruby object _and_ saves it to the database
1. Run `rake db:seed`

## Ruby

Substitute a character in a string for another character

```ruby
string.gsub("character-to-target","character-to-replace")
```

### Gems

- [Bcrypt](https://github.com/codahale/bcrypt-ruby). _An easy way to keep your users' passwords secure._
- [Bundler](https://bundler.io/)._Bundler provides a consistent environment for Ruby projects by tracking and installing the exact gems and versions that are needed._
- [Corneal](https://github.com/thebrianemory/corneal). _A Ruby gem that is a Sinatra app generator with Rails-like simplicity_
- [Faker](https://github.com/faker-ruby/faker). _A library for generating fake data such as names, addresses, and phone numbers._
- [Nokogiri](https://github.com/sparklemotion/nokogiri). _Nokogiri (鋸) is an HTML, XML, SAX, and Reader parser_
- [Rake](https://github.com/ruby/rake). _Rake is a Make-like program implemented in Ruby. Tasks and dependencies are specified in standard Ruby syntax._
- [Shotgun](https://github.com/rtomayko/shotgun). _This is an automatic reloading version of the rackup command that's shipped with Rack._
- [Tux](https://github.com/cldwalker/tux). _Tux dresses up sinatra in a shell. Use it to interact with your helpers, view rendering and your app's response objects._

## Terminal / CLI

Open an item or folder in a specific application
```
application .
```

For example, to open a folder in Atom, you would use this command

```
atom .
```

Clear the terminal window

```
clear
```

Create a new file

```
touch file-name.txt
```

Create a new directory

```
mkdir directory-name
```
