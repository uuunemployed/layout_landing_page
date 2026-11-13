# My Bike: Landing Page

## Introduction

Welcome to the My Bike landing page project, built according to a Figma design. It is a single-page website for a fictional electric bike brand that presents the bike lineup, key product details and a contact form. The project was created to practice semantic HTML, BEM methodology and SCSS by following a design mockup.

## Live Preview

[View the deployed version](https://uuunemployed.github.io/layout_landing-page/)

## Design Reference

[Figma mockup](https://www.figma.com/design/NZQAIydtHo5QkINyGLHNcq/BIKE-New-Version?node-id=41317-189&t=MRte5Y2W6kJWUbiu-0)

## Key Features

- **Responsive Design:** the layout adapts to mobile, tablet and desktop screens.
- **Header with Burger Menu:** a fullscreen menu implemented with pure CSS (`:target`), without JavaScript.
- **Compare Bikes:** a section with three bike models, their descriptions and prices.
- **The Details:** an adaptive grid of images and descriptions of the bike's features.
- **Contact Form:** a form with required field validation, plus phone, email and address.
- **Smooth Scrolling:** animated navigation between sections.

## Challenges

- **Responsive layout:** adapting the design to different screen sizes required careful testing and fine-tuning of the styles.
- **CSS-only burger menu:** building a working menu with the `:target` selector and smooth transitions, without JavaScript.
- **Adaptive image grid:** arranging wide and square images in "The Details" section so that it looks right on every screen size.
- **Fonts and performance:** self-hosting the font, adding `preload` and `font-display: swap` to speed up loading.
- **Code quality:** following BEM naming and passing HTML and CSS linters before every commit.

## Technical Requirements

To run this project, you will need:

- NPM (version 8.x or newer)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/uuunemployed/layout_landing-page.git
   ```

2. Navigate to the project directory:

   ```bash
   cd layout_landing-page
   ```

3. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

4. Run the project locally:

   ```bash
   npm start
   # or
   yarn start
   ```

After starting, the project is available at `http://localhost:1234` (the default Parcel port).

## Technologies Used

- **HTML5:** semantic markup following BEM methodology.
- **CSS3 / SCSS:** styling and responsive layout, written with the Sass preprocessor.
- **Parcel:** bundler used to build and optimize the project.
- **Poppins font** (weights 400, 700, 800): self-hosted with `preload` and `font-display: swap`.
- **Stylelint, linthtml, BEM linter:** code style checks on every commit.
- **Git and GitHub:** version control, repository hosting and deployment (GitHub Pages).

## Design Specifications

- **Font:** Poppins
- **Design sizes:** desktop, tablet and mobile, as in the Figma mockup
