# APP NAME

Blog Website

## AUTHOR

Elisephan NTAKIRUTIMANA

## DESCRIPTION

This is an app to create a personal blogging website where you can create and share your opinions and other users can read and comment on them. Additionally, add a feature that displays random quotes to inspire your users.

## User Stories

A users can see blogs that other people have posted

A user can comment on different blogs and leave feedback

A user can see random quotes displayed once the page is refreshed

A writer can submit a blog post

A writer can delete comments that are insulting to their blog

A writer can update the blog they posted

## BDD

Behaviour | Input | Output

---------------------+-------------------------------+-------------------------------

Create an account | Click Register |Register a new user

---------------------|-------------------------------|------------------------------

Go to your previous |Click login |Return to your previous account
account

---------------------|-------------------------------|--------------------------------

See your profile |Click profile |See your bio and profile pic

---------------------|-------------------------------|-------------------------------

Go to main page |Click home |Go back to homepage

## Prerequisites

Python3.8

## Installation steps

$ git clone https://github.com/Elisephan/personal_blog.git/

$ cd Blog_web

$ source virtual/bin/activate

Inside the manage.py module change the config_name parameter from 'production' to 'development' ie app = create_app('production') should be app = create_app('development')

$ ./start.sh

## How it works

A user needs to sign up

A user the needs to sign in order to see posts,create posts,comment posts and delete posts

## Technologies Used

This project uses major technologies which are :

HTML5/CSS

Bootstrap

Python3.6

flask

## KNOWN BUGS:

No known bugs

## CONTACT INFO:

You can email at: elisephanius@gmail.com

## LICENSE:

MIT License
