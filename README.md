
##  ![Logo](https://media.licdn.com/dms/image/v2/D4E22AQGljQZUu22jTQ/feedshare-shrink_1280/feedshare-shrink_1280/0/1711394022509?e=1726704000&v=beta&t=7D7R6RA4Y46VuZu16hegXoAD64YoYDqRKwsjSu99sEU)

### portfolio
# Software Dev // Juan Camilo


This repository contains my personal portfolio website, built using C# and the ASP.NET Core MVC framework. The project showcases my skills, projects, and experience in a professional and elegant format.

## Table of Contents

 - [Introduction]()
 - [Feactures]()
 - [Technologies Used]()
 - [Setup]()
 - [Usage]()
 - [Project Structure]()
 - [Contributing]()
 - [License]()



## Introduction

The Portfolio project is designed to provide a personal website that highlights my professional background, including my skills, previous projects, and other relevant information. 


## Features

- **Responsive Design**: The site is fully responsive and adapts to different screen sizes using **Tailwind CSS**.
- **Project Showcase**: A dedicated section to display my past projects with descriptions and links.
- **Contact Form**: A form that allows visitors to send me messages directly.
- **Resume Download**: A link to download my latest resume in **PDF format**.


## Technologies Used

- **C#**: For the backend logic and server-side operations.
- **ASP.NET Core MVC**: To implement the Model-View-Controller design pattern.
- **Tailwind CSS**: For styling the UI and ensuring a modern, responsive design.
- **HTML5 & CSS3**: For the basic structure and styling of the website.
- **JavaScript**: To add interactivity and enhance the user experience.
- **LibMan**: For managing client-side libraries (e.g., jQuery).
- **Git**: For version control.

## Setup

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Node.js & npm](https://nodejs.org/)
- [Git](https://git-scm.com/)

 



## Installation

#### Restaurar Dependencias

#### Clone the repository:
```bash
   git clone https://github.com/yourusername/Portfolio.git
   cd Portfolio
```
#### Install Node.js dependencies:
```bash
npm install
```
#### Compile Tailwind CSS:
```bash
npm run build:css
```
#### Build and run the project:
```bash
dotnet build
dotnet run
```

#### Build and run the project:
Navigate to http://localhost:5000 (or the port specified) in your web browser to view the site.

## Contributing
If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.

## Project Structure
```bash
Portfolio
│
├───Controllers
│   └───HomeController.cs
│
├───Views
│   ├───Home
│   │   └───Index.cshtml
│   └───Shared
│       └───_Layout.cshtml
│
├───wwwroot
│   ├───css
│   │   ├───input.css
│   │   └───site.css
│   ├───js
│   └───lib
│       ├───jquery
│       └───...
│
└───Program.cs
└───Startup.cs
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.
[MIT](https://choosealicense.com/licenses/mit/)

