#  Full Stack MERN AI Image Generation App

## Description

This web application consists on a AI Image Generation application where users can auto generate images based on their typing prompt. Utilized OpenAI API to auto generate images based on user's typing prompt. Then users can share the image to the community, which will render to the home page.

[AI Image Generation App](https://dall-e-bacc.onrender.com/) has been deploy online. Check it out and generate your favorite image then share!

## Functionalities

- SurpriseMe button to give a random prompt
- Auto genarating based on any typing prompt
- Sharing image to the community 
- User information of prompt and name

## How to Run

Fork this repository and follow the next steps

```
git clone git@github.com:JielinWang/AI-Img-Generation-App.git

cd client

npm install

npm run dev

THEN OPEN SECOND TERMINAL

cd server

npm install

npm start

```

Before running `npm run dev`, you will need the following environment variables:


```

MONGO_URL = <This is your MongoDb URI>

OPENAI_API_KEY = <This is your OPENAI_API_KEY>

CLOUDINARY_CLOUD_NAME = <This is your CLOUDINARY_CLOUD_NAME>

CLOUDINARY_API_KEY = <This is your CLOUDINARY_API_KEY>

CLOUDINARY_API_SECRET = <This is your CLOUDINARY_API_SECRET>

```

Once you have set up the environment variables, you can safely run the application in your browser.

## Tech Specifications

- Frameworks: [ReactJS](https://legacy.reactjs.org/)  [NodeJS](https://nodejs.org/en)   [Express](https://expressjs.com/)
- Database: [MongoDB](https://www.mongodb.com/)
- Image Storage: [Cloudinary](https://imagekit.io/cloudinary-alternative/?utm_source=google&utm_medium=cpc&utm_campaign=cloudinary-alternative&gclid=Cj0KCQiAic6eBhCoARIsANlox86kTNO1sArCY3wVliofqjaKRWohCyZtsSzpvsMj2l2xeUYZDUF9nnkaAv-2EALw_wcB)
- Tool: [ViteJS](https://vitejs.dev/)
- Deployment:[Render](https://render.com/)
- Styling: [TailwindCSS](https://tailwindcss.com/)
- Source: [OpenAIApi](https://openai.com/)

## Images of the App

HomePage <img width="1422" alt="Screenshot 2023-04-14 at 5 25 13 PM" src="https://user-images.githubusercontent.com/94776104/232165768-77404e84-911e-4d35-a782-706680e721d7.png">

CreatePost Page <img width="1401" alt="Screenshot 2023-04-14 at 5 27 11 PM" src="https://user-images.githubusercontent.com/94776104/232165803-53e61753-dddd-4182-bc32-071d7140160f.png">


## Author
[Jielin Wang](https://www.linkedin.com/in/jielinwang-/)

## License

MIT License
