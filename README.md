# YourHotel 

YourHotel is a hotel booking website designed to provide users with a simple and clear hotel search and booking experience.

The project is currently **in development**. The current version focuses on implementing the main UI design from the Figma prototype into HTML and CSS and connecting the main booking flow between pages.

# Figma Design Link
https://www.figma.com/design/GOuhgK6AxFve8C1NxLFFH0/YourHotel?node-id=0-1&t=AnM66wGbWbEewI31-1 

---

## Project Status

**Status:** In Progress 

### Completed so far

- Designed the main hotel booking interface in Figma
- Implemented the main pages using HTML and CSS
- Created a consistent visual design system
- Implemented the main booking flow between pages
- Added hover and click animations to buttons
- Added a printable booking receipt
- Added a shared JavaScript file for page navigation and printing

---

## Current Pages

The project currently contains four main pages:

### 1. Home Page

The Home Page includes:

- YourHotel header and navigation
- Search bar
- Destination section
- Trending hotel destinations
- Featured hotels
- Hotel cards
- Hotel ratings and reviews
- Hotel prices
- View Details buttons
- Favorite buttons

**Current interaction:**

`View Details` → Property Details

---

### 2. Property Details

The Property Details page includes:

- YourHotel header
- Breadcrumb navigation
- Hotel image gallery
- Hotel name
- Rating and reviews
- Location
- About the resort
- Services and amenities
- Guest reviews
- Booking card
- Hotel contact information
- Location map
- Select Room Options button

**Current interaction:**

`Select Room Options` → Guest Information

---

### 3. Guest Information

The Guest Information page includes:

- Breadcrumb navigation
- Guest information form
- First name
- Last name
- Email
- Phone number
- Special requests
- Booking summary
- Hotel information
- Room information
- Check-in and check-out dates
- Guests and room information
- Cost breakdown
- Total amount
- Continue to Payment button

**Current interaction:**

`Continue to Payment` → Booking Confirmation

---

### 4. Booking Confirmation

The Booking Confirmation page includes:

- Booking confirmation message
- Booking reference
- Selected property
- Hotel location
- Room type
- Guest information
- Check-in and check-out dates
- Amount paid
- Print Receipt button
- Back to Home button

**Current interactions:**

`Print Receipt` → Opens the browser print dialog

`Back to Home` → Home Page

The printed receipt is designed to hide unnecessary navigation and buttons and display the booking information with the YourHotel branding.

---

## Current User Flow

```text
Home
  │
  │ View Details
  ▼
Property Details
  │
  │ Select Room Options
  ▼
Guest Information
  │
  │ Continue to Payment
  ▼
Booking Confirmation
  │
  ├── Print Receipt
  │
  └── Back to Home
