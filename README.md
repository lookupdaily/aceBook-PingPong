### [Makers Academy](http://www.makersacademy.com) - Week 8 group project

[![Build Status](https://travis-ci.com/Peter2-71828/aceBook-PingPong.svg?branch=master)](https://travis-ci.com/Peter2-71828/aceBook-PingPong)
[![Maintainability](https://api.codeclimate.com/v1/badges/4f0cfbe1fc185ef34e2c/maintainability)](https://codeclimate.com/github/Peter2-71828/aceBook-PingPong/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/4f0cfbe1fc185ef34e2c/test_coverage)](https://codeclimate.com/github/Peter2-71828/aceBook-PingPong/test_coverage)
[![Heroku](https://pyheroku-badge.herokuapp.com/?app=acebook-pingpong&style=flat)](https://acebook-pingpong.herokuapp.com/)


Contributors: [Josh Blumberg](https://github.com/jlblumberg) | [Peter Dean](https://github.com/Peter2-71828) | [Joe Ellingworth](https://github.com/blu3skies) | [Dafna Libman](https://github.com/Dlibmanw) | [Liz Daly](https://github.com/lookupdaily) | [Jack Overton](https://github.com/Ovy95)
__________________________________________________________________________________________________________________

[Outline](#Outline) | [Specifications](#Specifications) | [User Stories](#User_Stories) | [Installation Instructions](#Installation_Instructions) | [Tech stack](#Tech_stack) | [Example use](#Example_use) | [Future work](#Future_work)

## <a name="Outline">Outline</a>

Work in a team of six to build a clone of Facebook.

## <a name="Specifications">Specifications</a>

The project specifications can be found [here](https://github.com/makersacademy/course/tree/master/engineering_projects/rails).

## <a name="User_Stories">User Stories</a>

User stories, which we designed from the specifications, can be found [here](https://docs.google.com/document/d/1GQxL08X9OiaRQS4eP1DW8j18zAJITgOzZBSF9FzqYNU/edit?usp=sharing).

## <a name="Installation_Instructions">Installation Instructions</a>

### Prerequisite setup:
- Clone this repo to your local machine and cd into it
- Run `gem install bundle` (if you don't have bundler already)
- Run `bundle` to install the project's dependencies

### Database setup:

To set up the databases, run the following migration commands:

```
bin/rails db:create
bin/rails db:migrate
```

### Running the site

Development:
- Run the server with command `bin/rails server`
- Visit `localhost:3000` to use the site

Production:
- Visit https://acebook-pingpong.herokuapp.com/

### Testing
- Tests can be run using Rspec. Run the command `rspec`.

## <a name="Tech_stack">Tech stack</a>

Front-end:
- HTML & CSS

Back-end:
- Ruby
- Ruby On Rails
- PostgreSQL

Testing:
- RSpec
- SimpleCov
- Code Climate
- Travis CI

## <a name="Example_use">Example use</a>

Some screenshots of the different functionality of the site:

The landing page prompts users to sign up or sign in

![landing page](https://i.imgur.com/FBKhPts.png)

Doing so will take you to the timeline, which lists posts in reverse chronological order

![Timeline](https://i.imgur.com/EOt0FoK.png)

You can click 'New Post' in the navbar to make new posts

![New Post](https://i.imgur.com/1XqR5dk.png)

Once you've made a post, you can edit or delete it for up to 10 minutes

If you click on a user's name, it will take you to that persons profile, which will display their profile picture and their photos

![Other User](https://i.imgur.com/gF5mccu.png)

If you click on your own name, it will take you to your profile

![Your profile](https://i.imgur.com/aoMI4WQ.png)

The 'Your Photos' navbar option takes you to a list of your photos. Here you can also edit, delete, and choose to make one of your photos your profile picture

![Your photos](https://i.imgur.com/4jikYsu.png)

You can sign out at any time by clicking the 'Sign Out' button in the navbar

## <a name="Future_work">Future work</a>

On a revisit of the project, we would like to add functionality to comment on and like/unlike people's posts.
