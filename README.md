# cs465fullstack
 

Overview 

I created a full-stack web app for this project as part of my training. It has a webpage for customers and a secure area for admins. Anyone can go to the public page and see trips. Administrators can log in to add, update, and keep an eye on trip details. The last version of the project had security mechanisms added to keep the admin login and routes safe. This made the app feel more authentic and complete. 

  

Front-end work for architecture 

 I used more than one front-end solution for this project, depending on what the page was for. 

On the side that the consumer sees, HTML and JavaScript are used with Express. This strategy works effectively for sites that only provide information and don't need to be changed regularly or have a lot of intricate user interactions. 

 Angular was utilized to turn the admin side of the program into a single-page app (SPA). The SPA lets you alter the content without having to refresh the site. This makes it easier and faster for the admin user to handle trips. 

 Using both helped me find out when a regular server-rendered page is superior and when an SPA is better for speed and simplicity of use. 

 Back end and database 

 The backend was built with Node.js and Express, while MongoDB was utilized to store data. 

MongoDB is a NoSQL database that stores data in documents that look like JSON files. It was a fantastic choice for our project because it works well with JavaScript and makes it easy to update the data structure as the program expands. It also worked well with Mongoose, which helped us keep our models in order and check that the data we had was right. 

  

JavaScript and JSON  

 JSON is a kind of data that goes from the front end to the back end. JSON is just a way to store and send data, while JavaScript is a full computer language. 

In this case, JSON links all the parts of the system together. Data is transferred in JSON format from the front end to the back end. The API processes the data, saves it in MongoDB, and then sends it back to the front end in the same way. This makes it easy for different components of the software to talk to each other and always work. 

Reusable components and Restructuring 

 I modified the code throughout the project to enhance its readability and usability. This involved partitioning routes, controllers, and models on the back end, along with eliminating redundant code. 

Reusable UI components, such as trip lists and modification forms, were developed for the admin single-page application (SPA). Repurposing components reduced superfluous code, facilitated app management, and ensured a consistent user experience. This also expedited future updates, as modifications needed to be implemented in only one location. 

  

Evaluation  

Postman was utilized to evaluate API endpoints and ensure that requests and responses functioned correctly. This involved verifying the GET, POST, PUT, and DELETE methods to ensure that data could be accurately inserted, modified, deleted, and retrieved. 

Security made testing harder because you had to prove who you were before you could access certain parts of the application. To protect the admin side and make sure only approved users could get in, JSON Web Tokens (JWTs) were used. This helped me understand how security, middleware, and protected routes all work together in a full stack application. 

  

This course helped me better understand how all the parts of a full stack program connect and work together. I learned how to build a project from beginning to end, including connecting to a database, creating backend APIs, and adding security. 

  

I also learned how to use MongoDB and Mongoose, create RESTful APIs with Express, add login authentication, and test secure endpoints. With more practice, I got better at finding bugs, fixing code, and solving real-world software problems. 

  

Because of this project, I feel more confident in my skills and better prepared for a future job as a software engineer. 
