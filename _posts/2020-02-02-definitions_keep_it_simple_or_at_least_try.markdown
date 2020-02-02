---
layout: post
title:      "Definitions ... keep it simple or at least try"
date:       2020-02-02 18:11:11 +0000
permalink:  definitions_keep_it_simple_or_at_least_try
---


It's far to easy to get caught up in the lingo and trying to sound like you know what your talking about. Although using the correct terminology is very important dont let it confuse you and derail your train of thoughts. 

If you ask me Concatenation  sounds like somthing creatied in a spooky lab! All it basically is addition for strings! Not so scary after all.

The dreaded  argument error 
display_player': wrong number of arguments (given 1, expected 0) (ArgumentError).
All this means is that whatever is in your parenthesis, display_player(input)
which is called the parameter or argument the number given and expected is not the same all you need to do to fix this is make them identical.

An object is anything created from  a class and an easy way to spot this is by using new keyword.
So in the class of Cartoon
character1 = character.new
character2 = character.new
these are 2 seperate objects

Self can be a bit tricky depending on where it resides but Self inside of a class method is the class itself so in the example below when we say self.title we are actullay saying book.title
class Book
  def self.title
    true 
  end

A class lays out the foundation for you like a blueprint. Basically a class is defined using the keyword class, a name, and the keyword end
In our class Scraper we will have all of our data that we scraped.

Methods are an object’s behaviour these are things that the object can do.
ex: input = gets.chomp 
here we have an exapmle of method chaining where the gets method retrieves data input by the user and a second method .chomp is tacked onto it and it removes any trailing white space.

When you create an instance of a class your just making an object, but a single unique object like how there are millions of iphones but my perosnal iphone is an instance of the iphone class.

Instance method .each.with_index(1) do |name, index| with each iteration im creating a new instance of my class.
instance method lives where the object resdies.

The class method lives at the level of the class.
In nba class 
def self.scrape 
self returns the nba class and scrape is the method.

@@all  is a class variable
when you use a class varaible its pretty much default to that class becuase it belongs to it and is a characteristic of that class.

@name is an instance variable 
def initialize(name)
    @name = name  here the =name is the same as the name in the ()
		when you use an instance variable its unique to that object/instance or single object

Like with everything in life there is good and bad , there is hard and easy and some coding terms pretty much define themselves, others you just need to pay attention to what you are doing and google away if need be.These arent litteral definitions so for those of you who know  what you are actually doing please resist the urge to drop kick me, im just trying simplify it for myself and and others who may be struggling down the same road.
