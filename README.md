# Tech-Titans-Movie Library WebApp

# CineTrac

CineTrac is a web application that allows users to discover, search, and filter movies. It provides a user-friendly interface for managing a catalog of movies.

![WhatsApp Image 2024-02-05 at 9 08 01 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/2a92aa33-9790-4e78-8570-351d3e70783e)

![WhatsApp Image 2024-02-05 at 9 08 22 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/9630481c-7934-495d-8369-d7a850f12a90)


## Introduction

CineTrac is designed to make movie management and discovery easy. Users can view detailed information about movies, search for specific titles, and apply filters based on various criteria.

## Requirements

- Node.js
- npm (Node Package Manager)
- SQLite (or any other preferred database)

## Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, EJS 
- **Backend**: Node.js, Express.js
- **Database**: SQLite 
- **File Uploads**: multer

![WhatsApp Image 2024-02-06 at 7 50 00 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/99d07c3b-93c1-435e-90ea-cd3c323f81bd)


## Features

### CineTrac includes user authentication features:

- **Register**: Users can create accounts by providing a username,password,mail and age.

![WhatsApp Image 2024-02-06 at 7 53 00 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/ff02065d-3835-4fa7-99e2-5e8439fc3045)

![WhatsApp Image 2024-02-06 at 7 53 23 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/2381c854-4e4b-4b64-b262-47b09aa88654)

- **Login**: Registered users can log in to access personalized features.

![WhatsApp Image 2024-02-06 at 7 53 46 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/bac1763e-9adf-4fc1-a6b5-4e83d47a9c55)  

### CRUD Operations

CineTrac supports basic CRUD (Create, Read, Update, Delete) operations for managing movies.

- **Create**: Add new movies with details such as title, director, release year, genre, description, and an image.

![WhatsApp Image 2024-02-06 at 7 48 46 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/3c751df0-c187-4e1e-9b58-6b4cd59df9dc)
  
- **Read**: View a list of featured movies with their details. Click on "Read More" to view a specific movie's detailed information.

![WhatsApp Image 2024-02-05 at 9 12 29 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/c6455837-3d1f-4d50-bbb3-0f3841ba607a)
  
- **Update**: Modify existing movie details, including title, director, release year, genre, description, and image.

  ![WhatsApp Image 2024-02-05 at 9 13 36 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/b53b1885-c771-40e1-9d02-4dfd168baa87)

- **Delete**: Remove movies from the catalog.

  ![WhatsApp Image 2024-02-06 at 7 50 57 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/ae5f8a4b-0c18-4362-8662-faf0560b27c7)


### Search

CineTrac allows users to search for movies by title. The search results provide a quick overview of movies matching the search query.

![WhatsApp Image 2024-02-05 at 9 09 06 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/051c746a-b936-49c1-919b-322fb5fb6ce3)

![WhatsApp Image 2024-02-05 at 9 09 42 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/e887cf73-b425-4da6-8c16-1e8863335159)


### Filter

Users can filter movies based on different criteria:

- Title
- Genre
- Release Year
- Director

  ![WhatsApp Image 2024-02-05 at 9 10 15 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/f0a0b6c7-cc13-4b06-927a-58b04ad7f65a)

  ![WhatsApp Image 2024-02-05 at 9 11 40 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/79bf1688-a0d2-4b50-be72-436235813d4b)

  ![WhatsApp Image 2024-02-05 at 9 11 58 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/c27bbafb-f96c-4340-b3d4-ed4b6dbb3fc9)


## Responsive Testing

The application is designed to be responsive, ensuring a consistent experience across various devices. You can test the responsiveness using browser developer tools or real devices of different sizes.

![WhatsApp Image 2024-02-06 at 7 52 08 PM](https://github.com/kiddoGirl/Tech-Titans---Movie-Booking-App/assets/103051896/16461bac-f137-49b5-be9f-4faaf91e81ec)



## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the application: `nodemon index`
4. Visit `http://localhost:3000/` in your browser.

