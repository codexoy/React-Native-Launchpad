# React Native Launchpad

**Production-Ready Foundation for Modern Mobile Apps**

Version: 2.1.0 | React Native + Expo | TypeScript | MIT License

## Overview

React Native Launchpad is an enterprise-grade starter template that combines the power of Expo with robust development tools. Built for teams that value type safety, performance, and developer experience, this template provides everything needed to launch your mobile app with confidence.

## Core Technology Stack

- **Framework**: React Native with Expo and File-Based Routing
- **Language**: TypeScript with enhanced type definitions
- **Package Manager**: Bun for lightning-fast dependencies
- **State Management**: Redux Toolkit for global state + Context API for local state
- **Data Fetching**: React Query for server state management
- **Internationalization**: i18next with multi-language support
- **Code Quality**: Biome for linting and formatting
- **Authentication**: Secure token management with expo-secure-store

## Key Features

### Development Excellence
- Type-safe environment with Total TypeScript Reset
- Expo Router for file-based navigation
- Environment variables with full TypeScript support
- Custom hooks for reusable logic
- Component testing infrastructure

### Production Capabilities
- Secure authentication flow
- API service layer with Axios
- Cookie and session management
- Responsive design utilities
- Performance-optimized bundles

### Developer Tools
- Biome for unified linting and formatting
- Expo Application Services (EAS) build scripts
- Dependency analysis with Knip
- Pre-configured development and production builds

## Quick Start

### Prerequisites
- Node.js 16 or higher
- Bun package manager
- Expo CLI
- Android Studio or Xcode

### Installation
```bash
# Clone the template
git clone https://github.com/codexoy/React-Native-Launchpad.git
cd react-native-launchpad

# Install dependencies
bun install

# Setup environment
cp .env.example .env
# Configure your environment variables
```

### Development
```bash
# Start development server
bun start

# Platform-specific development
bun android
bun ios
bun web
```

## Build and Deployment

### Development Builds
```bash
# Android development build
bun android:dev-build

# iOS development build  
bun ios:dev-build

# Local development builds
bun android:dev-build:local
bun ios:dev-build:local
```

### Production Builds
```bash
# Android release
bun android:release

# iOS release
bun ios:release

# Preview builds
bun android:preview
bun ios:preview
```

## Code Quality

### Linting and Formatting
```bash
# Run Biome check
bun check

# Format code
bun format

# Find unused code and dependencies
bun knip
```

### Testing
```bash
# Run test suite
bun test

# Update dependencies
bun update-packages
```

## Configuration

### Environment Setup
Create your `.env` file from the template:
```env
API_BASE_URL=your_api_url
AUTH_TOKEN_KEY=your_token_key
APP_ENV=development
```

### TypeScript Configuration
The template includes enhanced TypeScript types via Total TypeScript Reset, providing better IntelliSense and type checking.

### Internationalization
Add new languages by creating translation files in the i18n configuration:
```json
{
  "welcome": "Welcome",
  "auth": {
    "login": "Sign In",
    "register": "Create Account"
  }
}
```

## Customization Guide

1. **Update App Configuration**: Modify `app.json` with your app details
2. **Configure API Endpoints**: Update services with your backend URLs
3. **Customize Theme**: Modify design tokens in constants
4. **Add Features**: Extend Redux slices and React Query mutations
5. **Update Assets**: Replace default images and icons with your brand assets
