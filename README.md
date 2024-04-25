# Messenger Chatting App

## Overview
This project is a messenger chatting application built using Next.js, Tailwind CSS, NextAuth, and MongoDB. It enables real-time messaging, file sharing, group chat functionality, and management of chat rooms and channels. The application also supports CRUD operations for efficient data management.

## Demo
  Website link -> [click here](https://messenger-clone-nine-black.vercel.app/)
  **Note:** Site have not any virus, browser is just showing because of UI of this app is related to real messenger. 

## Features
- **Real-time Messaging:** Utilizes Pusher for real-time messaging, enabling seamless communication between users.
- **Responsive Design:** Built with a responsive design using Tailwind CSS, ensuring optimal user experience across various devices and screen sizes.
- **File Sharing:** Users can share files within conversations, enhancing collaboration and interaction.
- **Group Chat:** Supports group chat functionality, allowing multiple users to participate in conversations simultaneously.
- **Chat Room and Channel Management:** Enables users to create, join, and manage chat rooms and channels according to their preferences.
- **CRUD Operations:** Implements CRUD operations for user-friendly data management, enabling users to create, read, update, and delete messages and other content.

## Technologies Used
- **Frontend:** Next.js, Tailwind CSS
- **Authentication:** NextAuth
- **Database:** MongoDB
- **Real-time Messaging:** Pusher
- **Image Uploading:** Cloudinary CDN

## Installation
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Set up environment variables for authentication and database connection.
4. Run the application using `npm run dev`.

## Usage
1. Register or log in to access the messaging features.
2. Create or join chat rooms and channels.
3. Start sending and receiving real-time messages.
4. Share files and engage in group conversations.
5. Manage your conversations and content using CRUD operations.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests for any enhancements or bug fixes.

## Environment Variables
- `DATABASE_URL`: MongoDB connection string.
- `NEXTAUTH_SECRET`: Secret key for NextAuth authentication.
- `GITHUB_ID`: GitHub OAuth client ID.
- `GITHUB_SECRET`: GitHub OAuth client secret.
- `GOOGLE_CLIENT_ID`: Google OAuth client ID.
- `GOOGLE_CLIENT_SECRET`: Google OAuth client secret.
- `NEXT_PUBLIC_PUSHER_APP_KEY`: Pusher app key.
- `PUSHER_APP_ID`: Pusher app ID.
- `PUSHER_SECRET`: Pusher app secret.
- `NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME`: Cloudinary cloud name.
