# PhotoFolio

PhotoFolio is an online photo album React app that enables users to manage and share their digital photo collections. It utilizes React concepts, Firebase Firestore for data storage, and various UI components for album and image management.

## Live Demo
[View Live Demo](https://photofolio-oh4l.onrender.com/)

## Features
- AlbumsList: Display a list of albums fetched from Firestore.
- AlbumForm: Add a new album to the database.
- ImagesList: Display images in a selected album, manage images (edit/delete).
- ImageForm: Add/update images in an album.
- Carousel: View images in a model window with navigation buttons.

## Firestore Database Structure
#### collections:
- albums: Store album information.
- images: Store images associated with specific albums.

## Getting Started
To get a local copy of the project and run it on your machine, follow these steps:

### Prerequisites
- Node.js and npm/yarn installed on your machine
- Firebase project and credentials (Firestore setup)

### Installation
1. Clone the repository:
- git clone https://github.com/your_username/PhotoFolio.git 

2. Navigate to the project directory:
- cd PhotoFolio

3. Install dependencies:
- npm install

4. Set up Firebase:
- Create a Firebase project and set up Firestore.
- Obtain Firebase configuration credentials.
- Add Firebase config in firebaseConfig.js or similar, if not already present.

### Usage 
1. Start the development server:
- npm start

2. Open the app in your browser:
- http://localhost:3000
