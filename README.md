# Kindergarten Covid Check In App (Apr 2022)
A Node/Express app where parents are able to submit Covid test results daily before dropping their children off at Kindergarten.
- Live demo [_here_](https://t.co/4n89kh0QrQ) - use testUsername and testPassword to gain access

## General Information
Parents are busy people. Life in Germany is rife with paper-based bureaucracy. 

Most kitas (kindergartens) required parents to complete paper forms _daily_ and hand them in, in person.

We wanted to streamline this process with a digital, easy-to-use solution that could be adopted by kitas and parents.

I built this, alongside @cschnitzel10 in two weeks as part of Ironhack's part-time Web Development Bootcamp as my second project - I ended up building two, alongside [Trusted Travel Tech] (https://github.com/ChrisJCastle93/travel-tech-project)

## Technologies Used
- Node 
- Express
- Mongo
- Mongoose
- Handlebars
- Axios
- bcrypt
- Nodemailer
- Tailwind
- Heroku

## Features
- **Test Submission**: Once logged in, Parents are able to submit a test (Covid/Other), in a form pre-populated with their children. Parents only see the last 7 days of tests to keep the app performant and the UI clean.
- **News**: Admins are able to create news, such as changes in Covid regulations, that then appears on the parent's side of the app. The parent will only see news relevant to their child's group.
- **Admin Dash**: On the admin side, they have visibility of all tests across all groups, and can filter by date and group to see the status of each group and child.
- **Email Alerts**: If a child receives a positive test for any disease, an email alert is issued to all parents of children within the same group. Just for fun, they'll also receive a random recommendation for a cocktail based on an API.

## Usage
You can run this app after cloning by using `npm start`

## Project Status
Project is: _complete_

## Room for Improvement

- **User CRUD**: We didn't have time to create the routes for our user management - the next step would be to create a subsection of the admin dashboard to manage Parents and Children (CRUD).

## Contact
feel free to [_contact_](mailto:chrisjcastle93@gmail.com) me
