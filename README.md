# TaskOrbit

TaskOrbit is a modern task management and team collaboration platform built with Next.js, TypeScript, and TailwindCSS. It provides an intuitive interface for managing projects, tracking tasks, and collaborating with team members.

## Features

- 📊 Interactive Dashboard
- 🎯 Task Management
- 👥 Team Collaboration
- 📈 Project Analytics
- 📱 Responsive Design
- 🌓 Dark/Light Mode Support
- 📊 Gantt Chart Integration
- 🔄 Drag and Drop Interface

## Tech Stack

- **Frontend**
  - Next.js 15.5
  - React 18
  - TypeScript
  - TailwindCSS
  - Material-UI Components
  - Recharts for data visualization
  - Gantt Task React for project timelines
  - React DnD for drag and drop functionality

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v18 or higher)
- npm or yarn

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/spencer2502/TaskOrbit.git
   cd TaskOrbit
   ```

2. **Install dependencies**
   ```bash
   # Navigate to the client directory
   cd client
   
   # Install dependencies
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
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## Project Structure

```
client/
├── public/           # Static files
├── src/
│   ├── app/         # Next.js app directory
│   │   ├── (components)/  # Shared components
│   │   │   ├── Navbar/   # Navigation components
│   │   │   └── Sidebar/  # Sidebar components
│   │   ├── layout.tsx    # Root layout
│   │   └── page.tsx     # Home page
│   └── ...
├── tailwind.config.ts    # Tailwind configuration
├── tsconfig.json         # TypeScript configuration
└── package.json         # Project dependencies
```

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run ESLint for code quality

## Styling

TaskOrbit uses TailwindCSS for styling with custom configurations:
- Responsive design patterns
- Dark/Light mode support
- Custom color schemes
- Consistent spacing system

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Spencer - [@spencer2502](https://github.com/spencer2502)

Project Link: [https://github.com/spencer2502/TaskOrbit](https://github.com/spencer2502/TaskOrbit)
