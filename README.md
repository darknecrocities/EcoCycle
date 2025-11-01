# EcoCycle   Waste Management & Rewards Platform

## Overview
EcoCycle is a community-focused waste management platform that encourages sustainable practices through gamification and rewards. Users can log their waste disposal activities, track their environmental impact, earn EcoCoins, compete with others on a leaderboard, unlock achievements, and redeem their EcoCoins for cryptocurrencies while learning about environmental sustainability.

## Core Features

### Authentication
- Internet Identity integration for secure user login and logout
- Clear user feedback during authentication process
- Smooth transitions between authenticated and unauthenticated states
- User session management and persistent login state

### Settings Management
- Secure settings page or modal where authenticated users can view, enter, update, and remove their Gemini API key
- Default Gemini API key (`AIzaSyABa_hinTbT-zYeJsjpzU5HNZb05YE8zSQ`) pre-filled in the settings interface
- API key storage in frontend local storage with secure handling
- Clear instructions and feedback informing users that the Gemini API key is securely stored locally and is required for AI-powered waste recognition
- Validation and testing functionality for entered API keys
- Option to update or remove saved API keys with immediate effect on waste recognition feature

### Waste Logging
- Users can log waste disposal events with details such as waste type, quantity, and disposal method
- Support for different waste categories (recyclables, compostables, general waste, hazardous materials, electronics waste)
- Simple form interface for quick logging of disposal activities
- History view of all logged waste events

### AI-Powered Waste Recognition (Gemini Feature)
- Image upload functionality allowing users to take or upload photos of waste items
- Real Gemini 2.5 Flash API integration using the current saved API key (default or user-updated) for waste image analysis
- Smart waste type recommendations based on uploaded images using actual AI recognition
- Option to accept AI suggestions or manually override the recommended waste category
- Auto-fill capability for waste logging form based on AI recommendations
- Visual display of uploaded images and AI analysis results
- Always uses the latest API key saved in settings for all recognition requests
- Clear feedback when API key is required for AI features

