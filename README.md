# AI Resume Analyzer

AI Resume Analyzer is a web application that allows users to upload their resumes and receive an analysis based on various criteria, including ATS (Applicant Tracking System) compatibility, keyword matching, and overall score. The app provides visual feedback and suggestions to help users improve their resumes for job applications.

## Features
- Upload PDF resumes for instant analysis
- ATS compatibility check with visual indicators
- Resume scoring and keyword matching
- Detailed feedback and suggestions
- Modern, responsive UI built with React and Vite

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm or yarn

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Aahana04/hello_world.git
   cd ai-resume-analyzer
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

### Running the App
Start the development server:
```sh
npm run dev
# or
yarn dev
```
The app will be available at `http://localhost:5173` by default.

### Building for Production
To build the app for production:
```sh
npm run build
# or
yarn build
```

### Docker Support
A `Dockerfile` is provided for containerized deployment. Build and run with:
```sh
docker build -t ai-resume-analyzer .
docker run -p 5173:5173 ai-resume-analyzer
```

## Project Structure
```
app/
  components/      # Reusable React components
  lib/             # Utility libraries (PDF parsing, etc.)
  routes/          # Application routes
  app.css          # Global styles
  root.tsx         # App root
  routes.ts        # Route definitions
constants/         # App-wide constants
public/            # Static assets (images, icons)
types/             # TypeScript type definitions
Dockerfile         # Docker configuration
vite.config.ts     # Vite configuration
```

## License
This project is licensed under the MIT License.

## Author
- [Aahana04](https://github.com/Aahana04)
