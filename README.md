<img width="338" alt="acebook logo" src="https://user-images.githubusercontent.com/55639318/92245684-9f2cd800-eebc-11ea-93a5-6bf824bb125e.png">

# (Rails Facebook Clone)

<br>

### A facebook clone written using Ruby on Rails. Sign up, find your friends and get posting! 

Visit acebook [here](http://intense-scrubland-58731.herokuapp.com)

<br>

## Screenshots: 

## To use locally:

First, clone this repository. Then:

```bash
> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
```
<br>

## Planning Wireframe
<br>
<img width="632" alt="Screenshot 2020-08-28 at 17 16 38" src="https://user-images.githubusercontent.com/55639318/92246256-6a6d5080-eebd-11ea-9214-1ec08f0ef49a.png">

<br>

## Final Database Schema
<br>
<img width="855" alt="Screenshot 2020-09-03 at 20 25 15" src="https://user-images.githubusercontent.com/55639318/92246629-f1222d80-eebd-11ea-9936-94262b3de8b7.png">
<br>

## User Stories

### Sign Up

```
As a new User
So that I can sign up easily
I would like to be able to sign up on the homepage

As a new User
So that I know if I am not signed in
I would like to directed to sign up if I am not

As a new User
So that I can sign up
I would like to provide my name, email address and password

As a new User
So that I can sign up easily
I would like the validity of my email address format to be checked

As a new User
So that I can start using Acebook quickly
I would like to directed to My Wall after signing up

As a new User
So that I know I have successfully signed up
I would like to see a welcome message

As a new User
So that I am not confused with another user
I would like to be blocked from signing up with another user's name or email

As a new User
So that I do not have to keep signing up
I would like my sign up to be remembered

```

### Login

```
As a User
So that I can login easily
I would like to login from the homepage

As a User
So that I can login
I would like to be told if I have entered my details incorrectly

As a User
So that I know my login has been successful
I would like to see a welcome message

As a User
So that I can start using Acebook quickly
I would like to directed to My Wall after login

As a User
So that I can navigate make use of all parts of the website
I would like my login to be remembered

As a User
So that I can change my login name and/or email
I would like to be able to edit my account details
```

### User Experience

```
As a User
So that I can navigate around the website easily
I would like navigation aids such as nav bar, buttons and links

As a User
So that I can have a pleasant experience using the website
I would like the website to have a simple, attractive style

As a User
So that I know if I try to navigate to a name of user that does not exist
I would like a custom 404 message to inform me of this

As a User
So that I know if I try to navigate to a post that does not exist
I would like a custom 404 message to inform me of this

As a User
So that I can easily go to another user's Wall
I would like the url of their Wall to end with their username

```

### Posts

```
As a User
So that I can communicate with others
I would like to be able to create posts

As a User
So that I can change my posts
I would like to be able to edit posts

As a User
So that I can remove my posts
I would like to be delete posts

As a User
So that I can see my own and other's posts
I would like to have an All Posts page

As a User
So that other users can see my posts
I would like to have an All Posts page

As a User
So that I can see new posts easily
I would like to see the newest posts first

As a User
So that I can seen when posts were made
I would like be informed how long ago they were made

As a User
So that I can express my opinion on a post
I would like to be able to make comments

As a User
So that I can remove my opinion on a post
I would like to be able to delete comments

As a User
So that I can see others' opinions on a post
I would like to be see comments

As a User
So that I can know if others liked my posts
I would like others to be able to 'Like' them

As a User
So that I can show I liked others posts
I would like to be able to 'Like' them

As a User
So that I feel more secure
I would like only logged in users to be able to see and create posts
```

### Wall

```
As a User
So that I can communicate with others in my own space
I would like to be able to post on my own Wall

As a User
So that others can communicate with me in my own space
I would like others to be able to post on my Wall

As a User
So that I can change my Wall posts
I would like to be able to edit posts

As a User
So that I can remove my Wall posts
I would like to be delete posts

As a User
So that I can seen when posts on my Wall were made
I would like be informed how long ago they were made

As a User
So that I can know if others liked my Wall posts
I would like there to be a Like button

As a User
So that I can easily visit someone's Wall
I would like there to be a search field to take me there

As a User
So that I feel more secure
I would like only logged in users to be able to see and post on my Wall

As a User
So that my Wall posts remain secure
I would like only the poster or Wall owner to be able to remove them

```

### Sign Out and Account Deletion

```
As a User
So that I know I am signed out
I would like to be taken back the homepage on signout

As a User
So that I can remove my account from the database
I would like to be able to delete my account

```




