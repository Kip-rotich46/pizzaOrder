Below is a `README.md` file tailored for your "Pizza Paradise" website project, which includes `index.html`, `order.html`, `about.html`, and `contact.html`, along with a `css/style.css` stylesheet and an `images/` folder. This README provides an overview, setup instructions, file structure, and notes for anyone (e.g., instructors, collaborators) who might use or evaluate your project. It assumes the project is a static HTML/CSS website built for a class assignment, consistent with the midterm context we’ve been working in.

---
###Live url link
https://kip-rotich46.github.io/pizzaOrder/


```markdown
# Pizza Paradise Website

Welcome to the **Pizza Paradise** website, a static HTML/CSS project designed to showcase a pizzeria’s online presence. This site allows users to explore the pizzeria’s story, order custom pizzas, and contact the team, all wrapped in a warm, pizza-themed design.

## Project Overview

Pizza Paradise is a fictional pizzeria established in 1995, offering premium, customizable pizzas with a focus on fresh, locally-sourced ingredients. This website includes:
- A homepage (`index.html`) with a welcome message and an "Order Now" call-to-action.
- An order form (`order.html`) for creating and submitting pizza orders.
- An about page (`about.html`) detailing the pizzeria’s history and values.
- A contact page (`contact.html`) with multiple ways to get in touch.

The site uses a consistent color scheme (coral red `#ff6b6b`, light red `#ffadad`, dark brown `#3c2f2f`) and Arial typography to evoke a cozy, inviting feel.

## Features

- **Responsive Navigation**: A simple `<nav>` bar links all pages.
- **Custom Order Form**: Users can select pizza size, crust, toppings, and provide delivery details, submitted to a placeholder endpoint.
- **Rich Content**: Detailed "About" and "Contact" pages with images and additional sections.
- **Interactive Elements**: Topping images toggle checkboxes, and buttons feature hover effects.
- **Consistent Styling**: CSS ensures a cohesive look across all pages.

## File Structure

```
pizza-paradise/
│
├── css/
│   └── style.css          # Main stylesheet for all pages
├── images/
│   ├── pizza1.jpg        # About page kitchen image
│   ├── pizza2.jpg        # Contact page store image, toppings (Pepperoni)
│   ├── pizza3.jpg        # Toppings (Olives)
│   ├── pizza4.jpg        # Order page pizza, toppings (Ham)
│   ├── pizza5.jpg        # Toppings (Mushrooms)
│   ├── pizza6.jpg        # Toppings (Sausage)
│   ├── pizza7.jpg        # Toppings (Onions)
│   ├── pizza9.jpg        # Toppings (Bell Peppers)
│   ├── pizza10.jpg       # Toppings (Pineapple)
│   ├── pizza11.jpg       # Home page pizza image
│   ├── community.jpg     # About page community event (optional)
│   └── map-placeholder.jpg # Contact page map (optional)
├── index.html            # Homepage
├── order.html            # Order form page
├── about.html            # About page
├── contact.html          # Contact page
└── README.md             # This file
```

## Setup Instructions

1. **Clone or Download**:
   - Clone this repository or download the ZIP file and extract it to a local directory.

2. **File Placement**:
   - Ensure all files remain in the structure above, with `css/style.css` in a `css/` folder and images in an `images/` folder relative to the HTML files.

3. **Open in Browser**:
   - Open any `.html` file (e.g., `index.html`) in a web browser (Chrome, Firefox, etc.) to view the site locally. No server is required as this is a static site.

4. **Image Check**:
   - Verify all images listed above are present in the `images/` folder. If missing, replace with placeholder images or update the HTML `src` attributes accordingly.

5. **Form Testing**:
   - The order form submits to `https://www.stonecoldprofessor.com/pizza-order.php` (a placeholder). For testing, you won’t see a response unless connected to a real endpoint.
   - The contact form uses `https://formspree.io/f/your-form-id` (a placeholder). Replace with a valid Formspree ID or server-side script for functionality.

## Usage

- **Home (`index.html`)**: Start here to see the welcome message and click "Order Now" to jump to `order.html`.
- **Order (`order.html`)**: Customize a pizza with size, crust, and toppings, then enter personal info and submit (simulated).
- **About (`about.html`)**: Learn about Pizza Paradise’s history, team, and community efforts.
- **Contact (`contact.html`)**: Find contact details, use the form, or follow social links (placeholders).

## Styling Notes

- **Colors**:
  - `#ff6b6b`: Headings, buttons, accents.
  - `#ffadad`: Hover states, secondary accents.
  - `#3c2f2f`: Text for readability.
  - `#fff8e1`: Background for `<p>` elements.
  - `#f4f4f4`: Page background.
- **Typography**: Arial, sans-serif for simplicity and availability.
- **Layout**: Flexbox and grid used for crust and topping selections; centered elements for visual balance.

## Known Issues

- **Form Submission**: The order and contact forms point to placeholder URLs. They won’t function without a backend setup.
- **Images**: If any `images/` files are missing, broken image icons will appear—replace with your own assets.
- **Responsiveness**: Basic styling is applied, but full mobile responsiveness isn’t implemented yet (e.g., navigation may stack awkwardly on small screens).

## Future Enhancements

- Add a backend (e.g., PHP, Node.js) to process form submissions.
- Implement responsive design with media queries for mobile devices.
- Embed a real Google Maps iframe on `contact.html` instead of a placeholder image.
- Replace placeholder social media links with real URLs.

## Credits

- Built as a static HTML/CSS project for a web development assignment.
- Images are placeholders; real assets should be sourced for a live site.
- Formspree suggested for contact form handling (optional).

## License

© 2025 Pizza Paradise (fictional). This project is for educational purposes and not licensed for commercial use.


