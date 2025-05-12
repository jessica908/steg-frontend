# Frontend Application

This is the frontend application built with React, Vite, and modern web technologies. The application features a modern UI with Material-UI and Tailwind CSS, along with various powerful features and integrations.

## 🚀 Features

- Modern React application using Vite as the build tool
- Beautiful UI components using Material-UI and Tailwind CSS
- Responsive design with mobile-first approach
- Advanced routing with React Router
- State management using Recoil
- Markdown support with react-markdown
- Date and time handling with date-fns
- Form handling and validation
- Accessibility features with Radix UI components

## 🛠️ Tech Stack

- **Framework:** React 18
- **Build Tool:** Vite
- **Styling:** 
  - Tailwind CSS
  - Material-UI
  - Emotion
- **UI Components:**
  - Radix UI
  - Headless UI
  - Heroicons
  - Tabler Icons
- **State Management:** Recoil
- **Routing:** React Router DOM
- **HTTP Client:** Axios
- **Date Handling:** date-fns
- **Markdown:** react-markdown with remark-gfm
- **Animations:** Framer Motion
- **Development Tools:**
  - ESLint
  - PostCSS
  - TypeScript

## 📦 Installation

1. Clone the repository
2. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## 🚀 Development

To start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

## 🏗️ Building for Production

To create a production build:

```bash
npm run build
```

The build output will be in the `build-output` directory.

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run clean` - Clean build output directory

## 🔧 Configuration

The project uses several configuration files:

- `vite.config.js` - Vite configuration
- `tailwind.config.js` - Tailwind CSS configuration
- `tsconfig.json` - TypeScript configuration
- `eslint.config.js` - ESLint configuration
- `postcss.config.js` - PostCSS configuration

## 📚 Dependencies

The project uses a variety of dependencies for different purposes:

- **UI Components:** @mui/material, @radix-ui/*, @headlessui/react
- **Icons:** @heroicons/react, @tabler/icons-react, lucide-react
- **State Management:** recoil
- **Routing:** react-router-dom
- **HTTP Client:** axios, axios-auth-refresh
- **Date Handling:** date-fns, react-day-picker
- **Markdown:** react-markdown, remark-gfm
- **Utilities:** jszip, lodash.debounce, tailwind-merge

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request
