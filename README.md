# ChatIO🚀


<!-- ABOUT THE PROJECT -->

## Built With

- Frontend: EJS Templating Engine, CSS, Vanilla JavaScript
- Backend: Node.js, Express.js
- Libraries: Socket.io, Mongoose
- Database: MongoDB Atlas
---

# 📈 UML Diagram

<details>
   <summary>Unoptimized Architecture (old)</summary>
   <img src="https://user-images.githubusercontent.com/61842142/168617573-a0cbdbd9-804c-4108-ba86-4a9136d56416.png"/ alt="Previous UML Architecture">
</details>

<details>
   <summary>Optimized Architecture (revamped)</summary>
   <img src="https://user-images.githubusercontent.com/61842142/172811785-3ed66bf7-0635-42f5-87a5-d58ff641bb0d.png"/ alt="Revamped UML Diagram">
</details>


<!-- ## 🔥 Screenshots

| Landing Page |
| - |
| ![client/media/1.PNG](client/media/1.PNG) |

| Chat Page |
| - |
| ![client/media/2.PNG](client/media/2.PNG) | -->

## 🚩New Updates

- Added persistent chat storage in MongoDB Atlas

<!-- BUILT WITH -->  

## How to Install Locally

**1. Fork and clone this repository using**

   ```
   git clone https://github.com/shivamyadav11 && cd ChatIO/
   ```  
   
**2. Install required dependencies/dev dependencies using**  

   ```
   npm install && npm install -D && touch .env
   ```  
**3. Add the following key-value pairs inside the .env file**  

> Generate the VAPID keys using the following command:  
> ```
> ./node_modules/.bin/web-push generate-vapid-keys
> ```

  ```
  MONGO_URI=<Unique MongoDB Cluster URL>
  BASE_URL=<App Server URL> (Either http://localhost:3000 or deployment origin)
  ```

**4. Run server in development mode at `localhost:3000` using**  

  ```
  npm run dev
  ```

---

## 🤎 Found this project interesting?

If you found this project useful, please leave a :star: on Github💔.

---

## ✨ Project Maintained By-
  - [Suraj Prasad](https://www.linkedin.com/feed/)
