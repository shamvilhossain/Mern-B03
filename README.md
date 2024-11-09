# GlowHub - Responsive Website Design

## Project Description
GlowHub is a responsive, modern website designed to showcase various services, provide information about the company, and allow users to easily get in touch. The website is built using **Bootstrap 5** for responsive layout and styling, ensuring that the design is flexible across various screen sizes. Key features include a **carousel hero section**, a **responsive grid layout**, and an **interactive contact form**. The website is designed to provide a seamless experience for users on desktops, tablets, and smartphones.

## Design Choices

### 1. **Responsive Layout**
   - The entire website is built with a **mobile-first approach**, ensuring it’s fully responsive and works on all devices. 
   - The layout adjusts to smaller screen sizes by using Bootstrap’s grid system, ensuring the website content stacks or reorganizes based on the available screen space.

### 2. **Fixed Navigation Bar**
   - The navigation bar is fixed to the top of the page using the `navbar-fixed-top` class, ensuring it remains visible as users scroll through the content.
   - I implemented a **hamburger menu** that is displayed on smaller screens to toggle the navigation links.

### 3. **Carousel for Hero Section**
   - The **carousel** in the hero section features a smooth, auto-sliding image carousel with captions and buttons to guide users to the relevant sections.
   - I ensured that the carousel is fully responsive, and its size is fixed using Bootstrap's responsive classes and custom styling to maintain the aspect ratio of images.

### 4. **Grid System for Content Layout**
   - The content is displayed using Bootstrap's **grid system**. 
   - On larger screens, the content is displayed in three columns (`col-lg-4`), while on medium and small screens, the content stacks into a single column (`col-md-6`, `col-12`).
   - The grid layout allows for easy scaling and adaptability for any content type.

### 5. **Cards for Service Section**
   - I used Bootstrap's **card component** to display services in a neat and clean layout. The cards include images, titles, descriptions, and hover effects.
   - A **hover effect** is applied to each card to make them interactive. The cards gently scale up on hover and display a subtle shadow, achieved using `card:hover` and `shadow-sm` classes.

### 6. **Contact Form**
   - A **contact form** is included at the bottom of the page, where users can send inquiries or messages.
   - Bootstrap's form controls are used to create a clean and accessible form with input fields for name, email, and message.
   - I used the `btn-primary` class to style the submit button and make it stand out.

### 7. **Footer with Social Icons**
   - The footer is styled using `bg-dark` and `text-light` classes for a sleek, modern look.
   - Social media icons are added using **Bootstrap Icons**, ensuring that users can easily connect with the company on various platforms.

## Unique Bootstrap Features Implemented

- **Fixed Navbar**: `navbar-fixed-top` ensures the navbar stays at the top of the screen even when scrolling.
- **Carousel**: Used `carousel` with `carousel-control-prev` and `carousel-control-next` for navigation controls, ensuring easy sliding between images and content.
- **Responsive Grid System**: The grid is responsive, adjusting based on screen size using classes like `col-lg-4`, `col-md-6`, and `col-12`.
- **Card Hover Effect**: Implemented a smooth scale and shadow effect on cards with `transform` and `box-shadow` to add interactivity.
- **Social Media Icons**: Integrated Bootstrap Icons for social media links with a sleek and modern design.

## How to Run

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/shamvilhossain/Mern-B03.git

