# Alvin Leung Portfolio

A modern, responsive personal portfolio website showcasing my skills, projects, and experience as a Full-Stack Software Developer.

## Features

- Clean, mobile-friendly design using Tailwind CSS
- Tech stack overview
- Project showcase with modal details
- Contact and social links

## Tech Stack

- HTML5
- Tailwind CSS
- JavaScript

## Getting Started

1. Clone the repository:
   ```sh
   git clone https://github.com/alvin991/portfolio.git
   ```
2. Open `index.html` in your browser.

## Project Structure

```
index.html
README.md
script.js
style.css
```
## Local Development with Docker

To test the site locally with Nginx in Docker and see live changes:

1. Build the Docker image:
   ```sh
   docker build -t my-portfolio .
   ```
2. Run the container and mount your project directory:
   ```sh
   docker run -d -p 8080:80 --name my-portfolio -v C:/alvin/code/portfolio:/usr/share/nginx/html my-portfolio
   ```
3. Open your browser and go to:
   [http://localhost:8080](http://localhost:8080)

Any changes to your HTML, JS, or CSS files will be reflected immediately. Just refresh your browser.

## Contact

- [GitHub](https://github.com/alvin991)
- [LinkedIn](https://linkedin.com/in/alvinleung)
- Email: alvin991@icloud.com
