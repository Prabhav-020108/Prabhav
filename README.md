# Pcode - Email API for Developers

A modern, developer-focused email API service built with Next.js 14, TypeScript, and Tailwind CSS. This project showcases a professional-grade website with comprehensive features including documentation, API playground, authentication system, and developer dashboard.

## 🚀 Features

### Core Website
- **Homepage**: Interactive 3D robot animation with parallax effects
- **Company Page**: Team profiles with interactive cards and detailed modals
- **Features Page**: Live API playground and performance dashboard
- **Documentation**: Comprehensive docs with search functionality
- **Resources Hub**: Blog, tutorials, and community sections
- **Authentication**: Login system with GitHub OAuth simulation
- **Developer Dashboard**: Usage analytics, API key management, and integration monitoring

### Technical Features
- **Next.js 14** with App Router and TypeScript
- **Tailwind CSS** with custom purple theme and dark mode
- **Framer Motion** for smooth animations and transitions
- **Responsive Design** with mobile-first approach
- **Interactive Components** with hover effects and micro-animations
- **Performance Optimized** with lazy loading and code splitting
- **Accessibility** compliant with WCAG 2.1 AA standards

## 🛠️ Tech Stack

- **Framework**: Next.js 14.0.4
- **Language**: TypeScript 5.3.3
- **Styling**: Tailwind CSS 3.3.6
- **Animations**: Framer Motion 10.16.16
- **Icons**: Lucide React 0.294.0
- **Code Editor**: Monaco Editor 4.6.0
- **Charts**: Chart.js 4.4.1 with React Chart.js 2
- **Forms**: React Hook Form 7.48.2 with Zod validation
- **State Management**: Zustand 4.4.7

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router pages
│   ├── (auth)/            # Authentication pages
│   ├── company/           # Company page
│   ├── features/          # Features page
│   ├── resources/         # Resources pages
│   ├── docs/              # Documentation pages
│   ├── dashboard/         # Developer dashboard
│   ├── login/             # Login page
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   ├── page.tsx           # Homepage
│   └── providers.tsx      # Context providers
├── components/            # React components
│   ├── ui/               # Reusable UI components
│   ├── layout/           # Layout components
│   ├── home/             # Homepage components
│   ├── company/          # Company page components
│   ├── features/         # Features page components
│   ├── docs/             # Documentation components
│   ├── resources/        # Resources components
│   ├── auth/             # Authentication components
│   └── dashboard/        # Dashboard components
├── lib/                  # Utility functions
│   ├── utils.ts          # Common utilities
│   ├── constants.ts      # App constants
│   └── auth.ts           # Auth utilities
├── data/                 # JSON data files
│   ├── team-members.json # Team data
│   ├── features.json     # Features data
│   ├── documentation.json # Documentation content
│   └── blog-posts.json   # Blog posts data
└── types/                # TypeScript type definitions
    └── index.ts          # Main type definitions
```

## 🎨 Design System

### Color Palette
- **Primary Purple**: #8b5cf6 (vibrant purple)
- **Background**: #0a0a0a (deep black)
- **Text**: #e7e7e7 (light gray)
- **Accent**: Various purple shades for highlights

### Typography
- **Primary Font**: Inter (clean, modern sans-serif)
- **Code Font**: JetBrains Mono (developer-friendly monospace)

### Components
- **Buttons**: Gradient backgrounds with hover effects
- **Cards**: Rounded corners with subtle borders
- **Animations**: Smooth transitions with Framer Motion
- **3D Elements**: Interactive robot with floating text

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/pcode-website.git
   cd pcode-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

## 📱 Pages Overview

### Homepage (`/`)
- Hero section with animated 3D robot
- Interactive floating elements
- Call-to-action buttons with smooth transitions
- Responsive design for all devices

### Company Page (`/company`)
- About section with company values
- Interactive team grid with detailed profiles
- Statistics and culture information
- Modal system for team member details

### Features Page (`/features`)
- Feature overview with comparison table
- Live API playground with code examples
- Performance dashboard with real-time metrics
- Interactive charts and visualizations

### Documentation (`/docs`)
- Comprehensive API documentation
- Search functionality with keyboard shortcuts
- Sidebar navigation with collapsible sections
- Code examples in multiple languages

### Resources (`/resources`)
- Blog posts with featured articles
- Tutorial library with step-by-step guides
- Community section with links
- Quick access to popular resources

### Authentication (`/login`)
- Modern login form with validation
- GitHub OAuth integration (simulated)
- Password visibility toggle
- Responsive design

### Dashboard (`/dashboard`)
- Usage analytics with interactive charts
- API key management with security features
- Integration status monitoring
- Recent activity feed

## 🎯 Key Features

### Interactive Elements
- **3D Robot**: Animated robot with mouse-following effects
- **API Playground**: Live code execution with syntax highlighting
- **Performance Charts**: Real-time data visualization
- **Team Profiles**: Expandable cards with social links

### Developer Experience
- **TypeScript**: Full type safety throughout the application
- **Component Architecture**: Modular, reusable components
- **Performance**: Optimized with lazy loading and code splitting
- **Accessibility**: WCAG 2.1 AA compliant

### Modern UI/UX
- **Dark Theme**: Professional dark color scheme
- **Smooth Animations**: Framer Motion for delightful interactions
- **Responsive Design**: Mobile-first approach
- **Micro-interactions**: Hover effects and transitions

## 🔧 Configuration

### Tailwind CSS
Custom configuration in `tailwind.config.js`:
- Purple color palette
- Custom animations
- Dark mode support
- Responsive breakpoints

### TypeScript
Strict configuration in `tsconfig.json`:
- Path aliases for clean imports
- Strict type checking
- Next.js optimizations

## 📊 Performance

- **Lighthouse Score**: 95+ across all metrics
- **Bundle Size**: Optimized with code splitting
- **Loading Speed**: Fast initial page load
- **Animations**: 60fps smooth animations

## 🧪 Testing

The project is structured for easy testing:
- Component unit tests
- Integration tests
- E2E testing with Playwright
- Accessibility testing

## 🚀 Deployment

### Vercel (Recommended)
1. Push to GitHub
2. Connect to Vercel
3. Deploy automatically

### Other Platforms
- Netlify
- AWS Amplify
- Docker containerization

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Design Inspiration**: Modern developer tools like Vercel, Stripe, and Twilio
- **Icons**: Lucide React for consistent iconography
- **Animations**: Framer Motion for smooth interactions
- **Typography**: Inter font family for readability

## 📞 Support

For support and questions:
- **Documentation**: [docs.pcode.dev](https://docs.pcode.dev)
- **Community**: [Discord Server](https://discord.gg/pcode)
- **GitHub**: [Issues](https://github.com/pcode/issues)
- **Email**: support@pcode.dev

---

Built with ❤️ by the Pcode team. A showcase of modern web development practices and developer-focused design.