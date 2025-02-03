# Zentry Landing Page

A **responsive** and **animated landing page** for **Zentry**, the metagame, built with **React**, **Tailwind CSS**, and **GSAP**. This page showcases the metagame with smooth animations and a modern UI design, hosted on **Netlify** for easy access.

## Features

- Fully responsive design for all screen sizes
- Smooth, interactive animations powered by **GSAP**
- Modern UI/UX built with **React** and **Tailwind CSS**
- Fast and easy deployment with **Netlify**

## Technologies Used

- **React**: Frontend JavaScript library for building the user interface
- **Tailwind CSS**: Utility-first CSS framework for styling the webpage
- **GSAP**: GreenSock Animation Platform for smooth, high-performance animations
- **Netlify**: Hosting platform for deploying the website

## Live Demo

You can view the live version of the landing page here:  
[Zentry Landing Page - Live Demo](https://679f1d27f6d5d8410b94c684--idyllic-cupcake-029134.netlify.app/)

## How to Run Locally

To run this project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/zentry-landing-page.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd zentry-landing-page
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Set up environment variables**:
   - Create a `.env` file in the root directory
   - Add the following variables:
     ```
     REACT_APP_API_URL=your_api_url_here
     ```

5. **Start the development server**:
   ```bash
   npm start
   ```

6. **View the website**:
   - Open your browser and navigate to `http://localhost:3000`
   - The page will automatically reload if you make any changes to the source files

## Build for Production

To create a production build:

1. **Run the build command**:
   ```bash
   npm run build
   ```

2. **Test the production build locally**:
   ```bash
   npx serve -s build
   ```

## Project Structure

```
zentry-landing-page/
├── public/
│   ├── index.html
│   └── assets/
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   ├── utils/
│   ├── App.js
│   └── index.js
├── package.json
└── tailwind.config.js
```

## Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [GSAP](https://greensock.com/gsap/)
- [Netlify](https://www.netlify.com/)
