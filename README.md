# Software Engineering Resources

A collection of resources, cheatsheets and code snippets I found helpful (or kept forgetting) during my Flatiron Software Engineering bootcamp.

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

## Ruby

Substitute a character in a string for another character

```ruby
string.gsub("character-to-target","character-to-replace")
```

### Gems

- [Bundler](https://bundler.io/)._Bundler provides a consistent environment for Ruby projects by tracking and installing the exact gems and versions that are needed._
- [Corneal](https://github.com/thebrianemory/corneal). _A Ruby gem that is a Sinatra app generator with Rails-like simplicity_
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
