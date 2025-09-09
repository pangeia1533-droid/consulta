# Online Medical Consultation Platform

## Overview

This is a web-based medical consultation platform designed for Brazilian Portuguese users. The application facilitates the generation of medical documents (Atestado and Laudo) through an intuitive web interface. Built as a single-page application with modern web technologies.

## Recent Changes

**September 09, 2025**: Complete redesign and implementation of medical document generation system
- Created comprehensive HTML interface with dynamic form switching
- Implemented two main document types: Atestado (Medical Certificate) and Laudo (Medical Report)
- Added responsive design with modern CSS styling
- Integrated form validation and user feedback systems

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology**: Pure HTML/CSS/JavaScript single-file implementation
- **Design Pattern**: Single-page application with dynamic form switching
- **Responsive Design**: Mobile-first approach with flexbox layouts
- **Styling**: CSS3 with modern gradients, animations, and responsive breakpoints
- **Localization**: Brazilian Portuguese language support

### User Interface Design
- **Theme**: Modern gradient-based design with purple/blue primary colors and green accent colors
- **Layout**: Centered container design with maximum width constraints and card-based forms
- **Typography**: Segoe UI font family for cross-platform compatibility
- **Visual Elements**: Rounded corners, box shadows, smooth animations, and hover effects
- **Forms**: Dynamic form switching without page reloads, with proper validation and feedback

### Document Types
- **Atestado (Medical Certificate)**: Patient name, CPF, consultation date, CID code, days off work, observations
- **Laudo (Medical Report)**: Patient name, CPF, consultation date, CID code, clinical description, medical recommendations, doctor signature

### Data Architecture
- **Client-side Processing**: All form handling and validation done in JavaScript
- **Form Validation**: Required field validation with user-friendly error messages
- **Data Formatting**: Automatic CPF formatting and date handling
- **Confirmation System**: Alert-based confirmation after form submission

## Technical Implementation

### Web Server
- **Server**: Python built-in HTTP server on port 5000
- **Deployment**: Simple static file serving for development
- **Workflow**: Configured with automatic restart capabilities

### JavaScript Features
- Dynamic form switching between document types
- Real-time CPF formatting with mask (000.000.000-00)
- Form validation with comprehensive error checking
- Smooth animations and transitions
- Default date setting to current date

### CSS Features
- Flexbox-based responsive layouts
- CSS Grid for form organization
- CSS animations and transitions
- Mobile-responsive breakpoints at 768px
- Modern color schemes with gradients
- Box shadows and visual depth

## External Dependencies

### Frontend Dependencies
- **Browser APIs**: Standard web APIs for DOM manipulation, form handling, and date formatting
- **CSS Framework**: Custom CSS implementation without external frameworks
- **Font System**: System fonts (Segoe UI, Tahoma, Geneva, Verdana, sans-serif)

### Server Dependencies
- **Python 3.11**: For built-in HTTP server functionality
- **No additional packages**: Uses only Python standard library

## File Structure
```
/
├── index.html          # Main application file (HTML + CSS + JavaScript)
├── replit.md          # Project documentation
└── workflow config    # Python HTTP server on port 5000
```