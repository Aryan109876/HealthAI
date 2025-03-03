# AI-Powered Healthcare Platform

A comprehensive healthcare platform that uses AI to provide personalized health recommendations, track user health metrics, and predict potential health risks.

## Features

- **Dashboard**: Overview of health metrics, AI recommendations, and health score
- **Health Metrics Tracking**: Visualize various health data like heart rate, steps, sleep, etc.
- **AI-driven Symptom Checker**: Analyze symptoms and get potential conditions with recommendations
- **Personalized Health Plans**: AI-generated exercise and diet plans
- **Health Risk Assessment**: AI-powered analysis of potential health risks with preventive actions
- **User Profile**: Manage personal information and connected devices

## Tech Stack

- **Frontend**: React with TypeScript
- **Backend**: Python with Flask
- **Data Visualization**: Chart.js
- **UI Components**: Custom components with Tailwind CSS
- **Icons**: Lucide React

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- Python 3.6 or higher
- npm or yarn

### Installation

1. Clone the repository
2. Install frontend dependencies:
   ```
   npm install
   ```
3. Install Python dependencies:
   ```
   pip install flask flask-cors
   ```

### Running the Application

1. Start the Python backend:
   ```
   npm run start-api
   ```
   This will start the Flask server on http://localhost:5000

2. In a separate terminal, start the frontend:
   ```
   npm run dev
   ```
   This will start the React app on http://localhost:5173

## Project Structure

- `/src`: React frontend code
  - `/components`: Reusable UI components
  - `/pages`: Main application views
  - `/services`: API service functions
  - `/types`: TypeScript interfaces
  - `/data`: Mock data (for development)
- `/api`: Python backend code
  - `app.py`: Main Flask application
  - `/data`: Data storage for the backend

## AI Features

The platform uses Python-based AI algorithms to:

1. **Analyze health metrics** and identify patterns
2. **Generate personalized recommendations** based on user data
3. **Predict potential health risks** using statistical models
4. **Create customized health plans** tailored to individual needs
5. **Analyze symptoms** and suggest possible conditions

## License

MIT