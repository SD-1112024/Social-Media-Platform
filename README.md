# Social Media Platform - Java Application

## Overview

The Social Media Platform is a Java-based console application that simulates a basic social media platform. It allows users to register, post messages, view other users' posts, follow other users, and comment on posts. This app demonstrates object-oriented programming concepts such as classes, inheritance, and encapsulation.

## Features

- **User Registration:** Users can register with their name, username, email, and password.
- **User Authentication:** Users can log in to the platform with their username and password.
- **Post Messages:** Authenticated users can create posts.
- **View Posts:** Users can view all public posts made by other users.
- **Follow Users:** Users can follow other users to see their posts in the future.
- **Comment on Posts:** Users can comment on posts made by others.
- **User Profiles:** Each user has a profile that contains personal information and posts they have created.
  
## Technologies Used

- **Java:** The application is built using the Java programming language.
- **Console-based UI:** The application uses the command line for user interaction.

## File Structure

```bash
SocialMediaApp.java      # Main class for the social media platform
User.java                # Class representing a user of the platform
Post.java                # Class for creating and displaying posts
Comment.java             # Class representing a comment on a post
SocialMediaApp.java      # Main driver class for the social media platform

##Sample Output

Welcome to the Social Media App!
1. Register New User
2. Login
3. Exit
Enter your choice: 1

Enter your name: John Doe
Enter your username: johndoe
Enter your email: johndoe@example.com
Enter your password: password123

Registration successful! Please login.

Enter your username: johndoe
Enter your password: password123

Login successful! Welcome back, johndoe!
1. Create Post
2. View Posts
3. Follow User
4. Logout
Enter your choice: 1

Enter your post content: This is my first post!
Post created successfully!



