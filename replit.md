# Overview

This is a modern, styled HTML university weekly schedule (emploi du temps) that displays class schedules in a visual, color-coded table format. The application is built with pure HTML, CSS, and JavaScript to show a complete weekly timetable for university courses including lectures (Cours), practical sessions (TP), and tutorials (TD).

The application provides an interactive, responsive interface with color-coded course types, modern gradients, and smooth animations for an enhanced user experience.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture

**Technology Stack**: Pure HTML5, CSS3, and Vanilla JavaScript

**Design Approach**: Single-page application with embedded CSS and JavaScript
- Modern, gradient-based design system with purple/blue color scheme (#667eea to #764ba2)
- Color-coded course types for easy identification:
  - Yellow gradient for Cours Magistraux (lectures)
  - Pink/Magenta gradient for Travaux Pratiques (TP - practical sessions)
  - Cyan/Blue gradient for Travaux Dirigés (TD - tutorials)
- Responsive design with mobile-first approach and media queries
- Smooth animations and hover effects for enhanced user experience

**Schedule Structure**:
- Weekly view from Monday to Saturday
- Two main time slots: Morning (8h30-12h30) and Afternoon (14h30-18h30)
- Multiple sessions can be displayed in a single time slot
- Each session displays course title, professor name, and room number

**Styling Features**:
- Modern gradient backgrounds and borders
- Clear, readable typography with proper hierarchy
- Rounded corners, shadows, and smooth transitions
- Interactive hover effects on course sessions
- Legend showing course type color coding
- Fully responsive layout that adapts to mobile, tablet, and desktop screens

## State Management

Client-side only, using vanilla JavaScript for:
- Page load animations
- Interactive click effects on course sessions
- No external state management libraries

## Deployment

**Server**: Python 3.11 HTTP server on port 5000
- Simple static file serving
- No build process required
- Direct HTML/CSS/JavaScript execution

# Current Implementation

The schedule includes all weekly courses:
- **Monday**: Database course + TP sessions for both groups
- **Tuesday**: Web Development and Java lectures
- **Wednesday**: Web Development TPs + Java TP for G1
- **Thursday**: Java TP for G2
- **Friday**: TD sessions for Web Development, Java, and Database
- **Saturday**: No classes

Each course entry includes complete information: course name, professor, and room location.

# External Dependencies

**None** - This is a pure HTML/CSS/JavaScript application with no external libraries or frameworks.

All functionality is implemented using native web technologies for maximum compatibility and minimal load time.
