# BookMyShow
Event Booking Website
About the Project

This is a modern, responsive event booking website built with React. Users can browse a variety of events, including music, sports, and movies, book their favorites, and manage their selections in a simple booking cart. The clean and intuitive user interface is designed to provide a seamless booking experience.
Features

    Interactive Event Cards: Browse through a grid of different events, each with a price and description.

    Dynamic Booking Cart: Add events to your personal booking list with a single click. The total cost is calculated in real-time.

    Remove Bookings: Easily delete a booked show from your cart if you change your mind.

    Category Filtering: Sort events by category (Music, Sports, Dance, Circus, Movie) to quickly find what you're looking for.

    Booking Confirmation: A friendly pop-up confirms your successful booking.

    Fully Responsive Design: The website is optimized for an excellent viewing experience on both desktop and mobile devices.

## Technologies Used

    React: A JavaScript library for building user interfaces.

    Vite: A fast build tool for modern web projects.

    Tailwind CSS: A utility-first CSS framework for rapid styling.

## Getting Started

To run this project locally, you will need Node.js and npm installed on your machine.
Prerequisites

    Node.js (v14.0.0 or later)

    npm (v6.0.0 or later)

Installation

    Clone the repository:

    git clone [your-repository-url]

    Navigate to the project directory:

    cd [your-project-folder]

    Install the dependencies:

    npm install

    Configure Tailwind CSS (if not already done):

    npx tailwindcss init -p

    Open tailwind.config.cjs and ensure the content section includes ./src/**/*.{js,ts,jsx,tsx}.

    Open src/index.css and add the Tailwind directives at the top:

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

Running the App

After the installation, you can start the development server:

npm run dev

Open your browser and visit http://localhost:5173 to view the website.
How to Use

    Book a show: Click the "Book My Show" button on any event card.

    Filter events: Use the category buttons at the top to filter the displayed events.

    Remove a booking: Click the "Remove" button next to a show in the "My Bookings" section.

License

This project is licensed under the MIT License.
