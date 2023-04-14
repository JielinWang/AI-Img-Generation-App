#  Full Stack MERN AI Image Generation App

## Description

This web application consists on a AI Image Generation application where users can auto generate images based on their typing prompt. Utilized OpenAI API to auto generate images based on user's typing prompt. Then users can share the image to the community, which will render to the home page.


furthermore for adding more featrues to this project I will create a user signUp and signIn page. so users can not only sign up as a regular users, but also track the food status on their own page and make a review of the food.

[Food-ordering-app Presentation](https://drive.google.com/file/d/1br3lfN7TH7YVLLE79yvOUa7RXjoapOn2/view?usp=sharing)

## Functionalities

- Admin Sign In
- Add dishes to your cart by selecting a quantity, size and extras
- Price and quantity shown in cart updates automatically
- Check out with cash or Paypal
- Create products by signing in as a restaurant admin
- Upload edit or delete your restaurant products
- Create, Edit and Delete Dishes. Including pictures, prices, size and extras

## How to Run

Fork this repository and follow the next steps

```
git clone git@github.com:JielinWang/Food-Ordering-App.git

cd Food-Ordering-APP

npm install
```

Before running `npm run dev`, you will need the following environment variables:

```
MONGO_URL = <This is your MongoDb URI>
ADMIN_USERNAME = <This is your ADMIN_USERNAME>
ADMIN_PASSWORD = <This is your ADMIN_PASSWORD>
TOKEN = <This is your TOKEN>
Paypal: client-id =  <This is your Paypal client-id>
```

Once you have set up the environment variables, you can safely run the application in your computer by running `npm run dev`. Then open [localhost:3000](http//localhost:3000) in your browser.

## Tech Specifications

- Framework: [NextJS](https://nextjs.org/)
- Database: [MongoDB](https://www.mongodb.com/)
- Secondary Storage: [cloudinary](https://imagekit.io/cloudinary-alternative/?utm_source=google&utm_medium=cpc&utm_campaign=cloudinary-alternative&gclid=Cj0KCQiAic6eBhCoARIsANlox86kTNO1sArCY3wVliofqjaKRWohCyZtsSzpvsMj2l2xeUYZDUF9nnkaAv-2EALw_wcB)
- Payment Getaway: [Paypal](https://www.paypal.com/us/home)
- Authorization and Authentication: [cookies](https://auth0.com/docs/manage-users/cookies)

## Images of the App
