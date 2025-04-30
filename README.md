# Converter Tools

An online file conversion tool that supports multiple file format conversions.

## Features

- Support for multiple file format conversions
- Simple and intuitive interface
- Fast conversion
- Free to use

## Supported Conversions

- Currency conversion
- Volume conversion
- Length conversion
- Weight conversion
- Temperature conversion
- Time zone conversion
- MP4 to MP3 conversion
- JPG to DXF conversion
- PNG to JPG conversion

## Project Structure

```
converter-tools/
├── frontend/           # Frontend React application
│   ├── public/        # Static files
│   ├── src/           # Source files
│   │   ├── components/  # Reusable components
│   │   ├── pages/      # Page components
│   │   ├── contexts/   # React contexts
│   │   ├── i18n/       # Internationalization
│   │   └── App.tsx     # Main application component
│   └── package.json   # Frontend dependencies
├── backend/           # Backend Node.js application
│   ├── src/          # Source files
│   │   ├── routes/   # API routes
│   │   ├── services/ # Business logic
│   │   └── index.js  # Main server file
│   └── package.json  # Backend dependencies
└── README.md         # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/converter-tools.git
cd converter-tools
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd ../backend
npm install
```

### Running the Application

1. Start the backend server:
```bash
cd backend
npm start
```

2. Start the frontend development server:
```bash
cd frontend
npm start
```

The application will be available at `http://localhost:3000`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 