# 💍 Khalib & Zoë Wedding Website

A beautifully designed, single-page wedding website built with pure HTML, CSS, and JavaScript. This project includes a password-protected entry, animated sections, RSVP call-to-action, countdown timer, and a fully responsive layout.

---

## ✨ Features

* 🔐 **Password Protection**

  * Simple front-end gate using JavaScript
  * Stores access state in `localStorage`

* 🎨 **Elegant Design System**

  * Custom color palette (sage, cream, gold, etc.)
  * Typography using Google Fonts:

    * Great Vibes (script)
    * Cormorant Garamond (serif)
    * Jost (sans-serif)

* 🎬 **Scroll Reveal Animations**

  * Smooth fade + slide animations using `IntersectionObserver`

* ⏳ **Live Countdown Timer**

  * Updates every second to the wedding date

* 💌 **RSVP Section**

  * Ready to connect to external RSVP services (Zola, The Knot, Google Forms, etc.)

* 📖 **Story Section**

  * Styled narrative with drop cap and image placeholder

* 📍 **Event Details**

  * Ceremony, venue, reception, and accommodations cards

* 🖼️ **Gallery Grid**

  * Responsive layout with support for portrait & landscape images

* ❓ **FAQ Accordion**

  * Interactive expand/collapse behavior

* 📱 **Fully Responsive**

  * Optimized for mobile, tablet, and desktop

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (custom properties, flexbox, grid)
* Vanilla JavaScript (no frameworks)

---

## 🚀 Getting Started

1. **Clone or download the project**

   ```bash
   git clone https://github.com/your-username/wedding-site.git
   ```

2. **Open the site**

   * Simply open `index.html` in your browser

3. *(Optional)* Use a local server for best results:

   ```bash
   npx serve
   ```

---

## 🔑 Customization Guide

### 1. Change the Password

In the `<script>` section:

```js
const CORRECT_PASSWORD = 'electric';
```

Replace `'electric'` with your desired password.

---

### 2. Update Wedding Details

Search and replace the following:

* Names: `Khalib & Zoë`
* Date: `November 27, 2027`
* Venue: `The Club Continental`
* Location: `Jacksonville, Florida`

---

### 3. RSVP Button

Replace the placeholder:

```js
onclick="alert('Thank you! RSVP form coming soon.')"
```

With a real link:

```html
<a href="https://your-rsvp-link.com" class="rsvp-btn">RSVP Now</a>
```

---

### 4. Add Your Story

Replace the placeholder text in the **Our Story** section:

```html
<p class="story-text">
[Replace this with your story...]
</p>
```

---

### 5. Add Images

#### Story Image

Replace the placeholder div with:

```html
<img src="images/story.jpg" alt="Khalib and Zoë">
```

#### Gallery Images

Replace each placeholder:

```html
<img src="images/gallery1.jpg" alt="Memory">
```

---

### 6. Update Countdown Date

In JavaScript:

```js
const WEDDING_DATE = new Date('2027-11-27T19:30:00-05:00');
```

Adjust date/time as needed.

---

### 7. FAQ & Details

* Edit text directly in HTML
* Add/remove FAQ items by duplicating `.faq-item`

---

## 📁 Project Structure

```
/
├── index.html   # Main website file (HTML, CSS, JS combined)
└── README.md    # Project documentation
```

---

## ⚠️ Notes

* This is a **front-end-only project**:

  * Password protection is not secure for sensitive data
  * RSVP requires an external service

* Images should be optimized for performance (recommended < 500KB each)

---

## 💡 Future Improvements

* Backend RSVP system (Node, Firebase, etc.)
* Email notifications
* Guest list management
* Photo upload/gallery integration
* Multi-language support

---

## 📄 License

This project is open for personal use and customization.

---

## ❤️ Acknowledgements

Designed with elegance and simplicity in mind for a memorable wedding experience.

---
