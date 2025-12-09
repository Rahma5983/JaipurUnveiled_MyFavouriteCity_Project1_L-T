# 🌸 Jaipur Unveiled: The Pink City Tour Guide 🏰

A vibrant, multi-page website designed to showcase the history, attractions, and culture of the magical Pink City, Jaipur.

## ✨ Project Overview

This website was built to be a functional, visually appealing, and interactive guide to Jaipur. The central theme is a mix of **pink** hues, reflecting the city's famous nickname, combined with rich, colorful imagery and engaging user experiences.

### Key Features Implemented:

* **Multi-Page Architecture:** Seven fully functional pages covering all aspects of a trip to Jaipur.
* **Pink Theme:** A customized CSS theme built around various shades of pink for a cohesive and attractive look.
* **Interactive Flip Cards:** Every major section (Attractions, Restaurants, Things to Do, Events) features unique, flip-able cards. Clicking an image reveals detailed information (speciality, ratings, reviews) on the back.
* **Integrated Map Links:** Each attraction card is connected to a "View on Map" link for easy location tracking (simulated Google Maps links).
* **Trip Planning Integration:** Dedicated external links to major travel platforms for seamless hotel booking (MakeMyTrip) and tour guide sourcing (GetYourGuide).
* **Attractive Typography:** Utilizes custom Google Fonts (`Playfair Display` and `Raleway`) for a luxurious and readable feel.

## 📁 Project Structure

JaipurUnveiledWebsite/
├── index.html
├── history.html
├── attractions.html
├── restaurants.html
├── things_to_do.html
├── events.html
├── plan_your_trip.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── img/

## 🛠️ Technologies Used

* **HTML5:** Structure and Content
* **CSS3:** Custom Styling (Pink Theme and Layout)
* **Bootstrap 5.3:** Responsive design and component utility
* **JavaScript (Vanilla JS):** Interactive card flipping logic
* **Google Fonts:** Custom attractive typography

## 🌟 How to Run

1.  **Clone the Repository (or download the files):**
    ```bash
    git clone L-T_Frontend_Project1_3rdsem
    cd Jaipurunveiled
    ```
2.  **Add Images:** Populate the `img/` folder with high-quality images of Jaipur attractions, restaurants, etc., ensuring filenames match those referenced in the HTML (e.g., `hawa_mahal.jpg`).
3.  **Open:** Simply open the `index.html` file in your web browser.

    ```bash
    # Example (on macOS/Linux):
    open index.html 
    ```

## 🖼️ Feature Showcase: The Interactive Flip Card

This is the central interactive element of the site, providing a dual-view experience for every point of interest:

| Front View | Back View (On Click) |
| :---: | :---: |
| **Image & Title** | **Description, Speciality, Ratings, Reviews** |
|  | Details about the Palace of Winds, visitor information, and a **functional "View on Map" link**. |

---

## 💡 Custom Enhancements

* **Fixed Navigation:** Ensures smooth, accessible navigation across all seven pages.
* **External Integration:** Direct links to **MakeMyTrip** and **GetYourGuide** in the "Plan Your Trip" section, fulfilling the requirement for functional external booking resources.
* **Thematic Design:** Every element, from the navbar background (`.bg-pink-dark`) to the card body (`.bg-light-pink`), uses the custom color palette defined in `style.css`.
   
    ├── kite_festival.jpg
    ├─
