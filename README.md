<H1 align ="center" > MERN STUDENT MANAGEMENT SYSTEM </h1>
<h5  align ="center"> 
Fullstack open source student management system application made with MongoDB, Express, React & Nodejs (MERN) </h5>
<br/>

- [Configuration and Setup](#configuration-and-setup)
- [Key Features](#key-features)
- [Technologies used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
- [📸 Screenshots](#screenshots)
- [Author](#author)
- [License](#license)

## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the Frontend on one terminal and the server on the other terminal)

In the first terminal

```
$ cd Fronted
$ npm install (to install Frontend-side dependencies)
$ npm run dev(to start the Frontend)
```

In the second terminal

- cd Backend and Set environment variables in .env
- Create your mongoDB connection url, which you'll use as your MONGO_URL
- Supply the following credentials

```
#  ---  Config.env  ---
PORT =8070
MONGO_URL =
```

```
# --- Terminal ---

$ npm install (to install backend-side dependencies)
$ npm start (to start the backend)
```

## Key Features

- Add Student
- Edit Student
- Remove Student
- No Student Page
- 404 Page and many more
- Responsive Design

<br/>

## Technologies used

This project was created using the following technologies.

#### Frontend

- [React js ](https://www.npmjs.com/package/react) - JavaScript library that is used for building user interfaces specifically for single-page applications
- [React Hooks ](https://reactjs.org/docs/hooks-intro.html) - For managing and centralizing application state
- [react-router-dom](https://www.npmjs.com/package/react-router-dom) - To handle routing
- [axios](https://www.npmjs.com/package/axios) - For making Api calls
- [Bootstrap](https://getbootstrap.com/) - For User Interface
- [React icons](https://react-icons.github.io/react-icons/) - Small library that helps you add icons to your react apps
- [SweetAlert2](https://sweetalert2.github.io/) - PopUp

#### Backend

- [Node js](https://nodejs.org/en/) -A runtime environment to help build fast server applications using JS
- [Express js](https://www.npmjs.com/package/express) -The server for handling and routing HTTP requests
- [cors](https://www.npmjs.com/package/cors) - Provides a Connect/Express middleware
- [Mongoose](https://mongoosejs.com/) - For modeling and mapping MongoDB data to JavaScript
- [Dotenv](https://www.npmjs.com/package/dotenv) - Zero Dependency module that loads environment variables
- [Nodemon](https://www.npmjs.com/package/nodemon) - To monitor changes to the program code that is being developed

#### Database

- [MongoDB ](https://www.mongodb.com/) - It provides a free cloud service to store MongoDB collections.

 <!-- ##  Screenshots  -->

![img-1](https://i.ibb.co/bXX7fdV/img-1-yhedpu.png)

---

![img-2](https://i.ibb.co/Qdk6NKb/img-2-uktrxk.png)

---

![img-3](https://i.ibb.co/YTDHbJb/img-3-s1js9i.png)

---

![img-4](https://i.ibb.co/1R4Sj89/img-4-sb9ga6.png)

---

![img-5](https://i.ibb.co/VvJTmQH/img-5-wrxlr7.png)

## Author

- Portfolio: [Daniel Lee](http://masterdev0218.portfolio.app)
- Github: [masterdev0218](https://github.com/masterdev0218)
- Email: [daniel.lee0218929@gmail.com](mailto:daniel.lee0218929@gmail.com)

## License

MIT License

Copyright (c) 2022 Gilbert Hutapea

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
