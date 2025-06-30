# Rent.bnb - Airbnb Clone Template

A beautiful, fully-featured Airbnb clone built with React, TypeScript, and Tailwind CSS. This template provides a production-ready foundation for building vacation rental platforms with modern design aesthetics and smooth user interactions.

![Rent.bnb Preview](https://nextgenbnb.netlify.app/)

## ✨ Features

### 🏠 Property Listings
- **Grid Layout**: Responsive property cards with hover effects
- **High-Quality Images**: Curated stock photos from Unsplash
- **Property Details**: Location, pricing, ratings, and availability
- **Interactive Cards**: Smooth animations and micro-interactions

### 🔍 Property Details
- **Image Gallery**: Full-screen photo viewer with multiple images
- **Detailed Information**: Complete property specifications
- **Host Profiles**: Superhost badges and hosting experience
- **Booking Interface**: Interactive reservation system with pricing breakdown
- **Real-time Feedback**: Loading states and success/error messages

### 🎨 Design & UX
- **Apple-level Aesthetics**: Clean, sophisticated visual presentation
- **Responsive Design**: Optimized for all device sizes
- **Modern UI Components**: Thoughtful hover states and transitions
- **Intuitive Navigation**: Easy-to-use interface with clear visual hierarchy

### 🏷️ Category System
- **Property Types**: Mansions, Cabins, Beach houses, City apartments, etc.
- **Visual Icons**: Lucide React icons for each category
- **Filtering Ready**: Foundation for advanced search functionality

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <https://github.com/devlance074/rentbnb.git>
   cd rentbnb
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory, ready for deployment.

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Categories.tsx   # Property category navigation
│   ├── Header.tsx       # Main navigation header
│   └── PropertyCard.tsx # Individual property listing card
├── pages/              # Route components
│   ├── Home.tsx        # Main listings page
│   └── PropertyDetail.tsx # Individual property page
├── data/               # Static data and mock content
│   └── properties.ts   # Property listings data
├── types.ts            # TypeScript type definitions
├── App.tsx             # Main application component
├── main.tsx            # Application entry point
└── index.css           # Global styles and Tailwind imports
```

## 🛠️ Technology Stack

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS for utility-first styling
- **Routing**: React Router DOM for navigation
- **Icons**: Lucide React for consistent iconography
- **Build Tool**: Vite for fast development and building
- **Code Quality**: ESLint with TypeScript support

## 🎨 Customization

### Adding New Properties

Edit `src/data/properties.ts` to add new property listings:

```typescript
{
  imageUrl: "https://images.unsplash.com/photo-...",
  images: ["image1.jpg", "image2.jpg", "image3.jpg", "image4.jpg"],
  location: "Your Location",
  title: "Property Title",
  price: 250,
  rating: 4.95,
  dates: "Mar 15-20",
  guests: 4,
  bedrooms: 2,
  beds: 2,
  bathrooms: 2,
  host: {
    name: "Host Name",
    isSuperhost: true,
    hostingSince: "3 years hosting",
    avatar: "https://images.unsplash.com/photo-..."
  },
  reviews: 45
}
```

### Styling Customization

The project uses Tailwind CSS. Customize the design by:

1. **Colors**: Modify the color scheme in `tailwind.config.js`
2. **Components**: Edit component files in `src/components/`
3. **Global Styles**: Update `src/index.css` for global styling

### Adding New Categories

Update the categories array in `src/components/Categories.tsx`:

```typescript
const categories = [
  { label: 'Your Category', icon: YourIcon },
  // ... existing categories
];
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 📱 Responsive Design

The template is fully responsive with breakpoints for:
- **Mobile**: < 640px
- **Tablet**: 640px - 1024px  
- **Desktop**: > 1024px

All components adapt seamlessly across different screen sizes.

## 🌟 Key Features Explained

### Property Cards
- Hover animations with image scaling
- Heart icon for favorites (ready for functionality)
- Star ratings and pricing display
- Click navigation to detail pages

### Property Detail Pages
- Full-screen image gallery
- Comprehensive property information
- Interactive booking widget with pricing breakdown
- Host information with badges
- Reservation system with loading states

### Navigation
- Sticky header with search functionality
- Category filtering system
- Responsive mobile menu (ready for implementation)

## 🚀 Deployment

This template is deployment-ready for:

- **Netlify**: Drag and drop the `dist` folder
- **Vercel**: Connect your Git repository
- **GitHub Pages**: Use the built files from `dist`
- **Any Static Host**: Upload the `dist` folder contents

### Environment Variables

For production deployment, you may want to add:

```env
VITE_API_URL=your-api-endpoint
VITE_ANALYTICS_ID=your-analytics-id
```

## 🔮 Future Enhancements

This template provides a solid foundation for adding:

- **User Authentication**: Login/signup functionality
- **Search & Filters**: Advanced property filtering
- **Booking System**: Real reservation management
- **Payment Integration**: Stripe or similar payment processing
- **Reviews System**: User-generated reviews and ratings
- **Host Dashboard**: Property management interface
- **Map Integration**: Interactive property maps
- **Messaging**: Host-guest communication

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2024 Rent.bnb Template

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Third-Party Assets

- **Images**: All images are sourced from [Unsplash](https://unsplash.com) and are free to use under the Unsplash License
- **Icons**: [Lucide React](https://lucide.dev) icons are used under the ISC License
- **Fonts**: System fonts are used for optimal performance and compatibility

## 📞 Support

If you encounter any issues or have questions:

1. Check the existing issues in the repository
2. Create a new issue with detailed information
3. Provide steps to reproduce any bugs
4. Include your environment details (Node.js version, browser, etc.)

## 🙏 Acknowledgments

- Design inspiration from Airbnb's excellent user interface
- [Unsplash](https://unsplash.com) for providing high-quality stock photos
- [Lucide](https://lucide.dev) for the beautiful icon set
- [Tailwind CSS](https://tailwindcss.com) for the utility-first CSS framework

---

*Happy coding! 🚀*

*Made with ❤ by DevLance for the developer community*

*Ready to create your own vacation rental platform? Start building with this template today!*