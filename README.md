# Grammable

Live site: https://grammable-julian-smith.herokuapp.com/

## About

Grammable is a web application for posting photos ("grams") and comments. Each gram has a caption, and users can post comments about the gram.

Grammable was created using Test-Driven Development (`TDD`).

## Getting Started

![Grammable1](https://user-images.githubusercontent.com/55506831/88234882-5c31e080-cc3f-11ea-8c59-fa2a5e53dff8.PNG)

### Accounts

A user account is required in order to post grams and comment on grams.

A sample user account can also be signed into. The username is `gram@example.com`. The password and username match.

### Basic Use

* Click on `Grammable` in the navigation bar to return to the Home Page.

* The Home Page lists all of the grams and comments posted by users. 

* To post your own gram, simply click on the `New Post` link and fill out the form. Click on the `Choose File` button and to select a photo (note: the uploaded image must be a `.jpg`, `.jpeg`, `.gif`, or `.png` file). You must also include a valid caption.

![Grammable2](https://user-images.githubusercontent.com/55506831/88234884-5d630d80-cc3f-11ea-9d37-e65de6f53240.PNG)

* To post a comment on a gram, simply find the `Add a comment` section of a gram, type your comment in the box, and click the `Add Comment` button.

## Built With

* [Amazon S3](https://aws.amazon.com/s3/) - Media storage
* [Bootstrap](https://getbootstrap.com/) - Front-End library
* [Heroku](https://www.heroku.com/) - Deployment
* [RSpec](https://rspec.info/) - Testing
* [Ruby on Rails](https://rubyonrails.org/) - Web application framework
* [PostgreSQL](https://www.postgresql.org/) - Database
