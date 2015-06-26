---
layout: post
title:  "Definitions"
date:   2015-06-26 12:32:16
categories: markdown
---

## Class

A class is a collection on variables and methods. The methods defined within the class can be called upon the class itself or on an instance of the class (which has attributes stored as variables).

## Model

A model is the blueprint that an object uses. It stores all necessary attributes and the methods that can be called on the object.

Example: A 'Person' model would contain information (attributes/variables) about that person. E.g. Name, Age, Weight, Height. It also contains things (methods) a 'Person' can do. E.g. Walking, Talking, Eating, Sleeping.

## Method

A method is a chunk of code that is saved and called by its name.

Example:

```ruby
def speak
  puts "Hello World"
end
```

Instead of typing "Hello World" everytime we want to "speak" we can just call the method by it's name and it will run the code within.

## Variable

A variable is an object that contains information within itself.

Example:

```ruby
a = "Hello World!"


puts a
  # => "Hello World!"
```

## Request

A request is asking a server for information for something. 

I.e. /home is a request for whatever '/home' does

## Route

A route code that deals with the changing information in a url.

Example:  www.facebook.com/home

The '/home' is picked up in by the controller and 'routes' you to the proper view.

## Response

When you into a route into an html, the response is what the server returns. The response is usually the 'view' you are supposed to see.