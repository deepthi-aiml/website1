# LankaDrive Auto Sales - Web Design Project

## Project Overview

This is a **First Semester Web Design Project** completed as part of the **Bachelor of Information Technology (BIT)** program at the **University of Moratuwa**.

The project is a complete front-end website for **LankaDrive Auto Sales**, a fictional automobile dealership based in Colombo, Sri Lanka. The website showcases vehicle listings, services, customer reviews, and contact information with a modern, responsive design.

## Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling, CSS Grid, Flexbox, animations
- **Formspree** - Backend form handling for inquiries and newsletter subscriptions

## Pages Included

| Page | Filename | Description |
|------|----------|-------------|
| Home | `index.html` | Landing page with hero banner, featured vehicles, promotions, and showroom gallery |
| About Us | `about.html` | Company introduction, mission & vision, reasons to choose LankaDrive |
| Vehicles | `vehicles.html` | Grid listing of all available vehicles with specifications |
| Vehicle Details | `vehicle-details.html` | Detailed specifications for each vehicle (9 cars total) |
| Services | `services.html` | Comprehensive list of services offered (leasing, insurance, etc.) |
| Reviews | `reviews.html` | Customer testimonials with star ratings and video testimonial |
| Contact Us | `contact.html` | Contact form, location map, and showroom details |

## Vehicle Inventory

The website features **9 vehicles** with detailed specifications:

| # | Vehicle | Year | Price (Starting from) |
|---|---------|------|----------------------|
| 1 | Toyota Corolla Axio | 2018 | LKR 8,250,000+ |
| 2 | Honda Fit GP5 Hybrid | 2020 | LKR 7,000,000+ |
| 3 | Suzuki Swift | 2019 | LKR 5,800,000+ |
| 4 | BMW X5 xDrive | 2017 | LKR 45,500,000+ |
| 5 | Nissan Leaf EV | 2021 | LKR 9,450,000+ |
| 6 | Mitsubishi Outlander | 2019 | LKR 18,250,000+ |
| 7 | Toyota Vios | 2022 | LKR 9,850,000+ |
| 8 | Honda HR-V | 2020 | LKR 12,250,000+ |
| 9 | Suzuki Jimny | 2021 | LKR 9,250,000+ |

## Key Features

### Design Elements
- Responsive layout (works on desktop, tablet, and mobile)
- Sticky navigation header
- CSS Grid and Flexbox for layouts
- Hover effects and smooth transitions
- Custom card components for vehicles and services

### Interactive Components
- Newsletter subscription forms (integrated with Formspree)
- Contact inquiry form with radio buttons and checkboxes
- Google Maps iframe integration
- Video testimonial with custom poster image
- Star rating display for reviews

### Form Handling
All forms use **Formspree** (`https://formspree.io/f/mbdpowyg`) as the backend service. Forms include:
- Newsletter subscription (email only)
- Contact inquiry (name, email, phone, vehicle interest, message)
- Inquiry type selection (Buy/Test Drive)

## Project Structure
```
lankadrive-project/
├── index.html
├── about.html
├── vehicles.html
├── vehicle-details.html
├── services.html
├── reviews.html
├── contact.html
├── css/
│ └── style.css
├── images/
│ ├── logo.png
│ ├── V-1.jpg
│ ├── V-2.jpeg
│ ├── V-3.png
│ ├── V-4.jpg
│ ├── V-5.avif
│ ├── V-6.avif
│ ├── V-7.webp
│ ├── V-8.jpg
│ ├── V-9.webp
│ ├── Showroom.webp
│ ├── gallery1.avif
│ ├── gallery2.jpg
│ ├── gallery3.avif
│ ├── gallery4.jpg
│ ├── promo.webp
│ ├── review.video.mp4
│ ├── facebook.png
│ ├── instagram.png
│ └── x.png
└── README.md
```


## Setup & Installation

1. **Clone or download** all files to your local machine
2. Ensure the folder structure remains intact (especially `css/` and `images/` folders)
3. Open any `.html` file in a modern web browser
4. **No server required** - pure HTML/CSS frontend

> **Note**: Image and video files referenced in the code need to be placed in the `images/` folder. Some external CDN icons are used for vehicle specification icons.

## External Resources Used

| Resource | Purpose |
|----------|---------|
| Google Maps Embed API | Showroom location map |
| Flaticon CDN | Vehicle specification icons |
| Formspree | Form backend handling |

## Learning Outcomes Demonstrated

- ✅ Semantic HTML5 structure
- ✅ CSS styling with external stylesheet
- ✅ Responsive web design principles
- ✅ Form creation with various input types
- ✅ Embedding external content (maps, video)
- ✅ Navigation across multiple pages
- ✅ Consistent UI/UX design patterns

## Screenshots


## Credits

| | |
|-|-|
| **Course** | BIT - Web Design (First Semester) |
| **Institution** | University of Moratuwa, Sri Lanka |
| **Project Type** | Academic Assignment |

---

*This project was created for educational purposes as part of the BIT degree program.*
