# Health Care Systems (HCS) Website

A modern, responsive website for Health Care Systems, specializing in behavioral health technology solutions. Built with React, TypeScript, and Tailwind CSS.

## Features

### 1. Modern Design
- Responsive layout for all devices
- Beautiful animations and transitions
- Dark mode support
- Wave background effects
- Smooth scrolling animations

### 2. Interactive Components
- **Navigation**
  - Dropdown menus
  - Mobile-responsive menu
  - Smooth navigation between pages
  
- **Booking System**
  - Interactive calendar
  - Time slot selection
  - First session free feature
  - Payment integration ready

- **Contact Form**
  - Form validation
  - Google Maps integration
  - ReCAPTCHA integration
  - Multiple contact methods

### 3. Real-time Features
- **Live Chat**
  - Floating chat widget
  - Real-time messaging interface
  - Auto-responses

- **Pricing Calculator**
  - Dynamic pricing updates
  - Module selection
  - User count scaling
  - Instant total calculation

### 4. Content Sections
- Hero section with animated images
- Achievement statistics with counters
- Testimonials showcase
- News and updates section
- Product showcase
- Company information

## Getting Started

### Prerequisites
- Node.js 18.0.0 or higher
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

The application will open automatically in your default browser at `http://localhost:5173`.

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## Technology Stack

- **Frontend Framework**: React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **UI Components**: Headless UI
- **Build Tool**: Vite
- **Form Handling**: Native Forms
- **Maps Integration**: Google Maps Embed API
- **Security**: ReCAPTCHA
- **Payment Processing**: Stripe (ready to integrate)

## Project Structure

```
src/
├── components/         # Reusable components
├── App.tsx            # Main application component
├── main.tsx          # Application entry point
└── index.css         # Global styles
```

## Key Components

- `App.tsx`: Main application layout and routing
- `BookingModal`: Appointment scheduling system
- `Chatbot`: Customer support chat interface
- `ContactPage`: Contact information and form
- `PricingCalculator`: Dynamic pricing tool
- `Testimonials`: Client testimonials section
- `NewsSection`: Latest updates and articles
- `Achievements`: Company statistics and milestones

## Customization

### Theming
- Colors can be customized in `tailwind.config.js`
- Dark mode toggle available through `ThemeToggle` component
- Animations can be modified in `index.css`

### Content
- Update text content directly in components
- Modify images by updating URLs to your own hosted images
- Customize navigation menu items in `App.tsx`