## **`Facebook-Clone`**

![](https://img.shields.io/github/languages/code-size/phanison898/facebook-clone?style=flat-square)
![](https://img.shields.io/github/languages/top/phanison898/facebook-clone?style=flat-square)
![](https://img.shields.io/github/license/phanison898/facebook-clone?style=flat-square)

---
### 🚥 Description

Building facebook application clone using **`React`** and **`express`**. This build covers the core functionality (`uploading normal text, images & videos`....etc) of original facebook application. It is fully responsive and looks better in most of the devices. It includes dark/light theme toggle feature as well



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#demos">Demo</a>
    </li>
    <li>
      <a href="#key-features">Key Features</a>
    </li>
    <li>
      <a href="#api-usage">API Usage</a>
    </li>
    <li>
      <a href="#deployment">Deployment</a>
    </li>
    <li>
      <a href="#build-with">Build With</a>
    </li>
    <li>
      <a href="#to-do">To Do</a>
    </li>
  </ol>
</details>


## Demos

<h3>Register</h3>

![register](https://user-images.githubusercontent.com/75969308/193156186-758504b9-f965-4aeb-b7ad-6caf1eca230a.gif)

<h3>Verify the newly created account via sending mail</h3>

![verifyMail](https://user-images.githubusercontent.com/75969308/193156623-7971294b-b389-4475-a827-bd575746b96a.gif)

<h3>Reset password by sending verification code to the corresponding email address to this account</h3>

![forgetPassword](https://user-images.githubusercontent.com/75969308/193156829-5f01763a-a378-4d5f-b14f-8442d0fa0847.gif)


<h3>Upload posts and reacts to them</h3>

![createpost makeReacts](https://user-images.githubusercontent.com/75969308/193156940-3313293f-0bd5-45c8-ba14-0adf88429644.gif)


<h3>Responsive Design</h3>

![responsive design](https://user-images.githubusercontent.com/75969308/193157058-7ee0e507-7611-4eb3-adab-b35e166bccf1.gif)

<h3>Edit personal info in your profile page, upload (profile image & cover page)</h3>

![editPersonalInfo](https://user-images.githubusercontent.com/75969308/193157129-9a5658f5-c710-4bf6-b25f-10c0018061f2.gif)


<h3>Live Search for other user in the system, view their profile, reacts to their post, and sending friend request or just following them</h3>

![search viewUserProfile sendFriendRequest](https://user-images.githubusercontent.com/75969308/193157152-8e46cc6c-db90-42c7-9b01-802e92ab0432.gif)

<h3>View your friends and accept or reject friend request</h3>

![acceptFriendRequest viewComments](https://user-images.githubusercontent.com/75969308/193157421-b1464ed5-403e-414e-b396-81a55dea6081.gif)

<h3>Dark mode</h3>

![darkmode](https://user-images.githubusercontent.com/75969308/193157574-e22a74d3-113d-4f45-8363-0d17ca870a46.gif)

------------------------------





## Key Features

* Authentication
  * Login 
  * SignUp
  * Logout
  * Tokens
* Password Management
  * Change Password 
  * Forgot Password 
  * Reset Password  
* Email Management
  * Send Email Verification 
  * Send reset password code 
* User
  * Update personal info, upload profile image, upload cover page
  * Create, remove posts, and reacts on posts
  * Search for friends, Send friend requests, accept/reject friend requests, view current friends
  * View friends posts in the home page 
  * Change from light mode to the dark one


## API Usage

### User Endpoints

| Methods  |        Endpoints       |
| -------  | ---------------------- |
| POST     | /register              |          
| POST     | /activate              |          
| POST     | /login                 |         
| POST     | /sendVerification      |          
| POST     | /findUser              |          
| POST     | /sendResetPasswordCode |          
| POST     | /validateResetCode     |
| POST     | /changePassword        |
| GET      | /getProfile/:username  |          
| PUT     | /updateProfilePicture  |          
| PUT     | /updateCover           |          
| PUT     | /updateDetails         |          
| PUT     | /addFriend/:id         |
| PUT     | /cancelRequest/:id         |
| PUT     | /follow/:id            |          
| PUT     | /unfollow/:id          |   
 PUT     | /acceptRequest/:id          | 
| PUT     | /unfriend/:id          |      
| PUT     | /deleteRequest/:id          |
| POST     | /search/:searchTerm    |          
| PUT     | /addToSearchHistory    |          
| GET     | /getSearchHistory      |          
| PUT     | /removeFromSearch      |          
| GET     | /getFriendsPageInfos   |          



### Post Endpoints

| Methods |        Endpoints       |
| ------- | ---------------------- |
| POST    | /createPost            |
| GET     | /getAllPosts           |
| GET     | /comment               |
| GET     | /savePost/:id          |
| GET     | /deletePost/:id        |


### Reacts Endpoints

| Methods |        Endpoints       |
| ------- | ---------------------- |
| POST    | /reactPost             |
| GET     | /getReacts/:id         |

### Upload Endpoints

| Methods |        Endpoints       |
| ------- | ---------------------- |
| POST    | /uploadImages          |
| GET     | /listImages            |



### 🛠 Tech used

- React
- React hooks
- Redux
- Material UI
- Flexbox
- Express
- Nodejs
- JWT


### ✅ How to make use of this build?

1. Clone the repository
   ```bash
   git clone https://github.com/phanison898/facebook-clone.git
   ```
2. Navigate to the cloned directory
   ```bash
   cd path/to/cloned/directory
   ```
3. Create .env file in the backend folder with following properties and paste them
   ```bash
   DATABASE_URL=
   TOKEN_SECRET=
   BASE_URL=
   EMAIL=
   MAILING_ID=
   MAILING_SECRET=
   MAILING_REFRESH=
   MAILING_ACCESS=
   CLOUD_NAME=
   CLOUD_API_KEY=
   CLOUD_API_SECRET=
   ```
4. Create .env file in the frontend folder
  ```bash
   REACT_APP_BACKEND_URL=
   ```
5. Install node packages
   ```bash
   npm install
   ```
6. Start the development server
   ```bash
   npm start
   ```
7. Happy learning 😊
8. Please consider to star ( ⭐ ) this repo. It'll boost my confidence





