# Chatterhub



**Chatterhub** is a full-featured social media web application designed to bring people together. From real-time chat to interactive posts and user-friendly features, Chatterhub is your go-to platform for seamless online connections.

---

## 🌟 Features

- **Real-Time Chat**: Engage in instant messaging with your friends.
- **Post Creation & Comments**: Share your thoughts and get feedback through likes and comments.
- **Google Authentication**: Effortless sign-in and sign-up via Google.
- **Notifications**: Stay updated on the latest interactions.
- **Responsive Design**: A seamless experience across all devices.

---

## 🔿 Technologies Used

- **Backend**: Node.js, Express.js, Mongoose (MongoDB)
- **Frontend**: EJS, SCSS, Vanilla JavaScript
- **Real-Time**: Socket.io
- **Authentication**: Passport.js (Google OAuth & JWT)
- **Email Services**: Nodemailer
- **Queue Management**: Kue with Redis
- **Session Management**: express-session with MongoDB

---

## 📸 Screenshots

### 1. **Home Page**
![image](https://github.com/user-attachments/assets/5bc9d4d2-6842-443f-bdf7-6de8fcfaf519)



### 2. **Real-Time Chat**

![image](https://github.com/user-attachments/assets/962548d5-845e-4687-a9de-5667b1af6011)


### 3. **Post Creation**

![image](https://github.com/user-attachments/assets/b305ba4d-9fd1-4f13-a3f6-5f905f50b361)


### 4. **Google Authentication**

![image](https://github.com/user-attachments/assets/c22cefe3-dd37-4b4e-8c8b-2801049878d6)

### 4. **Update User Profile information and picture**
![image](https://github.com/user-attachments/assets/f58df82f-ac1b-4638-bc56-a3372b8ed3d6)


---

## 🚀 Installation & Setup

Follow these steps to set up Chatterhub on your local system:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/chatterhub.git
   cd chatterhub
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory with the and populate all the variables
   Add the following variables:
   ```bash
    MONGO_URI=<your-mongodb-uri>
    GOOGLE_CLIENT_ID=<your-google-client-id>
    GOOGLE_CLIENT_SECRET=<your-google-client-secret>
    REDIS_URI=<your-redis-uri>
    ```
4. **Start the server**:
   ```bash
   npm run dev
   ```
5. **Access the application**:
Open your browser and go to 
   ```bash
   http://localhost:8000
   ```
