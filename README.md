# Bakery Website

## Description

A responsive and elegant bakery website built using only HTML and CSS.  
It contains multiple sections including a header, about section, product showcase, map with contact info, and a footer.

---

## Features

- Well-structured semantic HTML layout
- Responsive hero header with image overlay
- Clean and reusable CSS with variables
- Font Awesome icons for visual enhancements
- Organized folder structure (HTML, CSS, JS, images)
- Google Fonts integration
- Contact information embedded with Google Maps

---

## Technologies Used

- HTML5
- CSS3
- Font Awesome (CDN)
- Google Fonts: Alegreya & Alegreya Sans

---

## File Structure

```

Bakery-Website/

│

├── index.html

├── README.md

├── CSS/

│ └── style.css

├── JS/

│ └── main.js

├── images/

│ ├── bakery-light-1.png

│ ├── alexandru-stavrica-170390-800x760.jpg

│ ├── clem-onojeghuo-206832-600x500.jpg

│ ├── ben-garratt-134774-600x500.jpg

│ ├── stas-ovsky-123540-600x500.jpg

│ └── full-2-800x640.jpg



```

---

##  Code Explanation (Section by Section)

###  HTML Structure

- **`<head>`**: Contains meta tags for SEO, fonts, icons, and links to external styles.
- **`.container`**: The main wrapper for the website content.
- **`.header`**: Hero section with background image, title, subtitle, and buttons.
- **`.nav-bar`**: Navigation bar with logo and menu links.
- **`.about-us-section`**: Flex section showing a photo and content with icons and list.
- **`.loc-section`**: Our Location section with image and text side-by-side.
- **`.products-section`**: Card-based layout for 3 featured products (bread, bagels, cookies).
- **`.map-section`**: Contact section with address, phone, email, and embedded Google Map.
- **`.footer-section`**: Four-column footer with links, about info, hours, and contact details.
- **`.second-footer`**: Copyright & social media.

---

### CSS Structure

- **`:root`**: CSS variables for colors, fonts, and layout settings.

## :root CSS Variables

| Variable Name            | Value                                        | Description / Usage                                |
|--------------------------|----------------------------------------------|-----------------------------------------------------|
| `--main-color`           | `#8E7754`                                    | Main accent color (used in buttons, icons, etc.)   |
| `--secondary-color`      | `#969696`                                    | Secondary color (text, icons, etc.)                |
| `--light-color`          | `#ffffff`                                    | Light/white color (used in text or backgrounds)    |
| `--dark-color`           | `#303030`                                    | Dark color for headings and backgrounds            |
| `--heading-color`        | `#303030`                                    | Used for headings like `<h1>`, `<h2>`              |
| `--text-color`           | `#686868`                                    | Default paragraph color                            |
| `--btn-hover-bg`         | `#ffffff`                                    | Background color on button hover                   |
| `--btn-hover-color`      | `#000`                                       | Text color on button hover                         |
| `--border-radius`        | `4px`                                        | Rounded corners for buttons and icons              |
| `--box-shadow`           | `0 4px 12px rgba(0, 0, 0, 0.1)`              | Shadow for depth effect                            |
| `--font-small`           | `14px`                                       | For small text                                     |
| `--font-base`            | `16px`                                       | Base font size                                     |
| `--font-lg`              | `24px`                                       | Large text like subheadings                        |
| `--font-xl`              | `36px`                                       | Extra large text like main titles                  |

---
- **Reset Rules**: `*`, `body`, `a`, `li` – reset default styles.
- **Utility Classes**:
  - `.Box`: Centered fixed-width section with margin.
  - `.flex`: Flexbox helper to align items horizontally.
- **Header Styling**:
  - Fullscreen background with overlay.
  - Centered text and buttons.
- **Navbar Styling**:
  - Flex layout, logo on left, links on right.
- **About & Location**:
  - Split layout using `flex`.
  - Icon styling with `border-radius` and `padding`.
- **Products Section**:
  - 3 equal cards with images, titles, and descriptions.
- **Map Section**:
  - Icons + embedded iframe map.
- **Footer**:
  - Dark theme with four columns and structured lists.
  - Social media icons in rounded containers.

---
## Preview Images

Here are some images from the project:

#### Header section image
![Header](./images/header.png)

#### Why section image
![Why](./images/whoWe.png)

#### location section image
![location](./images/loc.png)

#### products section image
![products](./images/Pros.png)

#### map section image
![map Section](./images/map.png)

#### footer section image
![footer Section](./images/footer.png)


---

## Author

**Mohamed Sayed Omar El-sayed**  
Faculty of Computers and Information, Fayoum University  
Email: [ms3655@fayoum.edu.eg](mailto:ms3655@fayoum.edu.eg)  
GitHub: [Mohamedsayed101](https://github.com/Mohamedsayed101)
LinkedIn: [Mohamed Sayed ]([https://www.linkedin.com/in/mohamed-sayed-omar/](https://www.linkedin.com/in/mohamed-sayed-439a54347/))

---

## License

This project is developed for learning and personal portfolio use.  
You are free to modify and use the code with proper credit to the author.
