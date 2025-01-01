# Video Sharing Platform 

## Introduction

This project combines the core functionalities of YouTube and Twitter into a seamless backend system, offering users the ability to host, engage, and share videos while integrating the tweet functionality for enhanced social interactions.

## Important links

| Content            | Link                                                                        |
| -------------------| ----------------------------------------------------------------------------|
| API Documentation  | [click here](https://documenter.getpostman.com/view/29234253/2sAYJ7gKFf) |

## Features

### User Management:

- Registration, login, logout, password reset
- Profile management (avatar, cover image, details)
- Watch history tracking

### Video Management:

- Video upload and publishing
- Video search, sorting, and pagination
- Video editing and deletion
- Visibility control (publish/unpublish)

### Tweet Management:

- Tweet creation and publishing
- Viewing user tweets
- Updating and deleting tweets

### Subscription Management:

- Subscribing to channels
- Viewing subscriber and subscribed channel lists

### Playlist Management:

- Creating, updating, and deleting playlists
- Adding and removing videos from playlists
- Viewing user playlists

### Like Management:

- Liking and unliking videos, comments, and tweets
- Viewing liked videos

### Comment Management:

- Adding, updating, and deleting comments on videos

### Dashboard:

- Viewing channel statistics (views, subscribers, videos, likes)
- Accessing uploaded videos

### Health Check:

- Endpoint to verify the backend's health

## Technologies Used

- Node.js 
- Express.js
- MongoDB
- Cloudinary 

## Installation and Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Shubham23jha/Backend.git
    ```

2. **Install dependencies:**

    ```bash
    cd Backend
    npm install
    ```

3. **Set up environment variables:**
    Create a .env in root of project and fill in the required values in the .env file using .env.sample file

4. **Start the server:**

    ```bash
    npm run dev
    ```
