Re-Former
==============

This is part of the Forms Project in The Odin Project’s Ruby on Rails Curriculum. Find it at http://www.theodinproject.com

## What it does?
This is a basic form created on MVC basis using rails model and controller properties

## How it works?
The Model is working on top of the following resources:

- Ruby (version 2.6.5)
- Rails (version 5.2.4)

And the next dependencies:

- sqlite3
- puma
- sass-rails
- uglifier
- coffee-rails
- turbolinks
- jbuilder
- bootsnap

## Usage
### Step 1: Clone and install dependencies
Clone the repo and run `bundle install` to get all the gems on your terminal.
### Step 2: Run database migration
From terminal type `rails db:migrate` to get your schema updated
### Step 3: Work on IRB
That's it on configuration. Now you can open the site with `http://localhost:3000/users/new` and see the main page for users registration (running `rails server` previously from terminal)

- `http://localhost:3000/users/new` for creating a new user

- `http://localhost:3000/users/user_id/edit` for updating an existing user

You can see how your users get saved on db from your rails console with `User.all` or `User.find_by_id(id_user_here)`

## 🤝 Contributing

Contributions are more than welcome!<br/>Feel free to check [issues page](https://github.com/ClintonEnyinna/micro-reddit/issues/).

1. Fork (https://github.com/ClintonEnyinna/micro-reddit/development/fork)
2. Create your working branch (git checkout -b [branch_name])
3. Commit your changes (git commit -am 'what you will add or fix or improve')
4. Push (git push origin [branch_name])
5. Create a PR

## 🤖 Contributor

Clinton Enyinna - [GitHub](https://github.com/ClintonEnyinna)
<br>
Ricardo Valtierra - [GitHub](https://github.com/ricardovaltierra)

## 🙋‍♂ Support :)

Give a ⭐️ if you liked it!

## 📝 License

This project is under the [MIT](LICENSE) license.