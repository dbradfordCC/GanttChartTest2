# Implementation Planner

An interactive Gantt chart tool for planning software implementation projects. This tool helps project managers visualize implementation timelines based on organization size and selected product mix.

## Features

- **Dynamic timeline calculation** based on organization size
- **Customizable product selection** to tailor the implementation plan
- **Interactive Gantt chart** visualization
- **PDF export functionality** for sharing and documentation

## Getting Started

### Prerequisites

- Node.js (version 14.x or higher recommended)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/implementation-planner.git
cd implementation-planner
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will open in your browser at [http://localhost:3000](http://localhost:3000).

## Usage

1. **Adjust organization size** using the slider (10-1000 employees)
2. **Select product components** to include in the implementation
3. **View the dynamically updated Gantt chart**
4. **Export as PDF** for documentation and sharing

## Deployment

This project can be easily deployed to Vercel:

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Vercel will automatically detect the React application and deploy it

## Built With

- [React](https://reactjs.org/) - The web framework used
- [Tailwind CSS](https://tailwindcss.com/) - For styling
- Browser's native print functionality for PDF export

## License

This project is licensed under the MIT License

## Acknowledgments

- Inspired by real-world software implementation projects
- Built to simplify project planning for implementation managers
