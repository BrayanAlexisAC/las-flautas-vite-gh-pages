# 🌮 Las Flautas - Restaurant Website

A modern, responsive website for **Restaurante Las Flautas**, showcasing their delicious Mexican cuisine and multiple locations. This is an enhanced version of the restaurant's web presence, built with cutting-edge web technologies to provide an exceptional user experience.

## ✨ Features

### 🏠 **Main Landing Page**
- Interactive carousel showcasing restaurant highlights
- Beautiful grid layout with promotional images
- Smooth animations and modern UI design

### 🍽️ **Digital Menu System**
- **Complete Menu Categories:**
  - Antojos Tradicionales (Las Flautas, Enmoladas, Enchiladas, Flautines)
  - Sopas (Traditional Mexican soups)
  - Consomé (Classic broths with various proteins)
  - Guarniciones (Side dishes)
  - Postres (Desserts)
  - Bebidas (Traditional and commercial beverages)
  - Ensaladas (Fresh salads)
- **Special Packages:** Pre-designed meal combinations for quick ordering
- Dynamic pricing display with elegant dotted separators
- Responsive design optimized for all devices
- Smooth scroll animations and intersection observers

### 🏢 **Branch Locations (Sucursales)**
- Interactive branch selector
- Detailed information for each location:
  - **Chapalita**
  - **Providencia** 
  - **Plaza Úbika**
  - **Call Center**
  - **Zona Real**
- Embedded Google Maps for each location
- Contact information and schedules
- Phone number integration for direct calling

### 📱 **Responsive Design**
- Mobile-first approach
- Portrait and landscape orientation support
- Adaptive navigation (hamburger menu on mobile)
- Touch-friendly interface

### 🎨 **Modern UI/UX**
- Custom animations and transitions
- Intersection Observer API for scroll-triggered animations
- Modal system for mobile navigation
- Bootstrap integration for consistent styling
- LESS/SCSS for advanced styling capabilities

## 🚀 Local Development Setup

### Prerequisites
- **Node.js** (version 16 or higher)
- **npm** or **yarn** package manager

### Installation & Running

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd las-flautas-vite
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:3000`

4. **For network access (testing on mobile devices):**
   ```bash
   npm run host
   ```
   This will make the app accessible from other devices on your network.

### Available Scripts

- `npm run dev` - Start development server
- `npm run host` - Start development server with network access
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 🛠️ Tech Stack

- **Frontend Framework:** React 19
- **Build Tool:** Vite 6.3.1
- **Language:** TypeScript
- **Styling:** 
  - Bootstrap 5.3.5
  - LESS & SCSS
  - Custom CSS animations
- **Routing:** React Router DOM 7.6.0
- **Development Tools:**
  - ESLint for code quality
  - TypeScript for type safety
  - SWC for fast compilation

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Carousel/       # Image carousel component
│   ├── HeaderMenu/     # Navigation header
│   ├── Footer/         # Site footer
│   ├── Modal/          # Modal system
│   └── ...
├── pages/              # Main page components
│   ├── main/           # Landing page
│   ├── menu/           # Menu system
│   └── sucursales/     # Branch locations
├── resources/data/     # JSON data files
├── styles/            # LESS/SCSS stylesheets
├── hooks/             # Custom React hooks
└── interfaces/        # TypeScript interfaces
```

## 🌟 Key Improvements Over Current Production

This enhanced version includes:
- **Better Performance:** Vite build system for faster development and optimized builds
- **Modern Architecture:** Component-based React structure with TypeScript
- **Enhanced UX:** Smooth animations, better mobile experience, intersection observers
- **Maintainable Code:** Modular components, type safety, and organized structure
- **SEO Optimized:** Proper meta tags, semantic HTML, and optimized images

## 📞 Contact & Support

For development questions or deployment assistance, please refer to the technical documentation or contact the development team.
