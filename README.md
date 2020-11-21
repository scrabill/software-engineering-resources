# Software Engineering Resources

A collection of resources, cheatsheets and code snippets I found helpful (or kept forgetting) during my Flatiron Software Engineering bootcamp.

> HEY FRIENDS! This repo/resource is a perpetual work in progress. I'm not sure how big I want to expand it, but had a thought to include some resources I am gathering for my own knowledge. I'm open to suggestions or contributions.

## To-Dos

- What is the difference between `find`, `find_by` & `find_by_id`?
- Sessions
- RESTful routes
- Atom packages

## Algorithms

_Resources recommended by others in the community._

- [AlgoExpert](https://www.algoexpert.io/)
- [BaseCS Podcast](https://www.codenewbie.org/basecs)
- [Binary Search Trees | Data Structures in JavaScript](https://www.youtube.com/watch?v=6JeuJRqKJrI&feature=youtu.be)
- [binarysearch.io](https://binarysearch.io/)
- [The Coding Interview Bootcamp: Algorithms + Data Structures](https://www.udemy.com/course/coding-interview-bootcamp-algorithms-and-data-structure/)
- [Cracking The Code Interview](https://www.youtube.com/playlist?list=PLX6IKgS15Ue02WDPRCmYKuZicQHit9kFt)
- [Daily Coding Problem](https://www.dailycodingproblem.com/)
- [De-Coding The Technical Interview Process](https://technicalinterviews.dev/)
- [HackerRank: Algorithms](https://www.youtube.com/playlist?list=PLI1t_8YX-ApvMthLj56t1Rf-Buio5Y8KL)
- [HackerRack: Data Structures](https://www.youtube.com/watch?v=IhJGJG-9Dx8&list=PLI1t_8YX-Apv-UiRlnZwqqrRT8D1RhriX)
- [JavaScript Algorithms and Data Structures Certification](https://www.freecodecamp.org/learn)
- [JavaScript Algorithms and Data Structures Masterclass](https://www.udemy.com/course/js-algorithms-and-data-structures-masterclass/)
- [The Working Developer's Guide To Algorithms](https://scrimba.com/course/galgorithmsguide)

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

## Git

- [Create a new empty branch in Git](https://gist.github.com/ozh/4734410)
- [How To Rename a Local and Remote Git Branch](https://linuxize.com/post/how-to-rename-local-and-remote-git-branch/)

### Create a New, Empty Branch

```git
git checkout --orphan NEWBRANCH
git rm -rf .
```

### Resources

- [Changing a remote's URL](https://docs.github.com/en/free-pro-team@latest/github/using-git/changing-a-remotes-url)

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

_Resources I have referenced or others have referenced_

- [The Bastards Book of Ruby](http://ruby.bastardsbook.com/)
- [DigitalOcean: How to Code in Ruby](https://www.digitalocean.com/community/tutorial_series/how-to-code-in-ruby)
- [Dissecting my Ruby Project Skeleton](https://dev.to/maxwell_dev/dissecting-my-ruby-project-skeleton-4pd7)
- [The Odin Project](https://www.theodinproject.com/courses/ruby-on-rails)
- [Rubular: a Ruby regular expression editor](https://rubular.com/)
- [Ruby Guides](https://www.rubyguides.com/)
- [Why’s (Poignant) Guide to Ruby](https://poignant.guide/book/)


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

Create a new branch and switch to it

```
git checkout -b branch-name
```

## Markdown

Create an alert box. Reference: https://stackoverflow.com/questions/50544499/how-to-make-a-styled-markdown-admonition-box-in-a-github-gist

```
| WARNING: Don't do the thing! |
| --- |
```
