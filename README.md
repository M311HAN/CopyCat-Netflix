# CopyCat-Netflix

[Check out the live site here!](https://m311han.github.io/CopyCat-Netflix/)

## Description

CopyCat-Netflix is a cloned version of the Netflix sign-in page that I've created to demonstrate my abilities in HTML, SCSS, and live SASS. This project was made to showcase my frontend skills and my capability to recreate intricate web designs. The replica is designed to be responsive and user-friendly. If you're a potential employer, a fellow developer, or anyone interested in knowing more about my frontend development journey, this project will offer you a glimpse of my proficiency in these domains.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Containerisation](#Containerisation)
- [Usage](#usage)
- [Credits](#credits)

## Technologies Used

- HTML
- SCSS
- Live SASS

HTML and SCSS were used for the structure and styling of the sign-in page. Live SASS, a compiler that automatically compiles SASS (Syntactically Awesome StyleSheets) files to CSS, was used to make the development process smoother and faster.

## Installation

Follow the steps below to install, configure, and run the project on your local system.

```bash
# Copy the following code into your terminal

# Clone the repository
git clone https://github.com/M311HAN/CopyCat-Netflix.git

# Navigate into the cloned directory
cd CopyCat-Netflix

# Install Live SASS Compiler extension if you're using VS Code

# Watch your .scss file for any changes by clicking on "Watch Sass" from the status bar
# It will create a respective .css file and update it whenever you save changes in your .scss file

# Open the index.html file in a web browser
```

## Containerisation

The CopyCat-Netflix sign-in page has been containerized using Docker to ensure that it runs consistently across any environment. Whether you're a developer looking to run this project on your local machine or planning to deploy it on a server, using the provided Docker configuration will streamline the process.

```bash
# Make sure Docker is installed on your system.

# Navigate to the project directory and build the Docker image:
docker build --platform linux/amd64 -t melihhan/copycat-netflix .

# Run the Docker container:
docker run -p 8080:80 melihhan/copycat-netflix
```
This will start the website inside a Docker container, and it can be accessed via a browser at http://localhost:8080 in your browser.

## Usage

CopyCat-Netflix serves as a testament to my ability to recreate detailed web designs. The project is not only a clone but a refined reproduction, boasting responsiveness and usability. Feel free to navigate around the sign-in page to appreciate the details and responsiveness. Remember, this is merely a clone, so it doesn't provide real streaming services.

## Credits

This project was created by Melihhan (https://github.com/M311HAN). The official Netflix sign-in page link is served as the reference for the design at the bottom of the page.
