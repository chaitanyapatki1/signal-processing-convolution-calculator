# Signal Processing Convolution Calculator

A modern, interactive web application for computing and visualizing discrete signal convolution operations. This frontend implementation provides a comprehensive interface for signal processing education and analysis.

![Signal Processing Lab](https://img.shields.io/badge/Signal%20Processing-Lab-blue)
![React](https://img.shields.io/badge/React-18.3.1-61dafb)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-3178c6)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.1-38bdf8)

## 🌟 Live Demo

Visit the live application: [https://signal-processing-co-mnh9.bolt.host](https://signal-processing-co-mnh9.bolt.host)

## 📋 Features

### Core Functionality
- **Interactive Signal Input**: Manual entry with real-time validation and preview
- **Convolution Computation**: Step-by-step calculation with detailed trace
- **Multiple Data Structures**: Array, Linked List, and Map representations
- **Linear Search**: Find values in signals with visual highlighting
- **Signal Visualization**: Interactive plotting with downloadable charts
- **Queue-based Trace**: Step-by-step computation tracking

### User Experience
- **Modern Dark Theme**: Professional interface with electric blue accents
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Engaging micro-interactions and transitions
- **Real-time Feedback**: Instant validation and status updates
- **Intuitive Navigation**: Step-by-step workflow guidance

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/signal-processing-convolution-calculator.git
   cd signal-processing-convolution-calculator
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application.

### Building for Production

```bash
npm run build
npm run preview
```

## 🎯 Usage Guide

### 1. Enter Signals
- Input your discrete signals x[n] and h[n]
- Use comma-separated values or individual value editors
- Try the provided sample signals for quick testing

### 2. Compute Convolution
- Click "Compute Convolution" to perform the operation
- The system calculates y[n] = x[n] * h[n] using discrete convolution

### 3. View Computation Trace
- Examine step-by-step calculations in queue format
- Each step shows the mathematical operations performed

### 4. Explore Output Formats
- **Dynamic Array**: Traditional vector representation
- **Linked List**: Node-based data structure visualization
- **Map Lookup**: Key-value pair interface with search functionality

### 5. Search Functionality
- Perform linear search on input signals
- Visual highlighting of search results and matches

### 6. Signal Visualization
- Interactive plots showing input and output signals
- Downloadable charts for documentation and analysis

## 🏗️ Architecture

### Technology Stack
- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS for responsive design
- **Icons**: Lucide React for consistent iconography
- **Build Tool**: Vite for fast development and building
- **Deployment**: Bolt Hosting for seamless deployment

### Project Structure
```
src/
├── components/           # React components
│   ├── Header.tsx       # Application header
│   ├── NavigationMenu.tsx # Step navigation
│   ├── SignalInput.tsx  # Signal input interface
│   ├── ConvolutionComputer.tsx # Computation engine
│   ├── TraceDisplay.tsx # Step-by-step trace
│   ├── OutputDisplay.tsx # Multiple output formats
│   ├── SearchComponent.tsx # Linear search functionality
│   └── PlotComponent.tsx # Signal visualization
├── types/               # TypeScript type definitions
│   └── index.ts        # Core interfaces and types
├── App.tsx             # Main application component
├── main.tsx            # Application entry point
└── index.css           # Global styles
```

### Key Components

#### Signal Processing Engine
- Implements discrete convolution algorithm: `y[n] = Σ x[k] * h[n-k]`
- Generates comprehensive computation traces
- Supports multiple output data structures

#### Interactive Visualization
- Canvas-based plotting with custom rendering
- Real-time signal preview and validation
- Downloadable chart generation

#### Data Structure Demonstrations
- Dynamic array (vector) representation
- Linked list with node visualization
- Hash map with key-value lookup interface

## 🔧 Development

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

### Code Quality
- TypeScript for type safety
- ESLint for code consistency
- Responsive design principles
- Accessibility best practices

## 📚 Educational Value

This application serves as an excellent educational tool for:
- **Digital Signal Processing**: Understanding convolution operations
- **Data Structures**: Visualizing arrays, linked lists, and maps
- **Algorithm Analysis**: Linear search implementation and complexity
- **Web Development**: Modern React and TypeScript patterns

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Follow the existing code style and TypeScript conventions
2. Add appropriate comments for complex algorithms
3. Test your changes across different screen sizes
4. Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classical signal processing education
- Built with modern web technologies for accessibility
- Designed for both educational and practical applications

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/yourusername/signal-processing-convolution-calculator/issues) page
2. Create a new issue with detailed information
3. Provide steps to reproduce any bugs

---

**Made with ❤️ for signal processing education and modern web development**
