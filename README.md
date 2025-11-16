# Study Timer

A modern, responsive study timer application built with vanilla HTML, CSS, and JavaScript. Features subject tracking, analytics dashboard, and customizable study goals with local data persistence.

![Study Timer Screenshot](readme%20photos/Screenshot%20of%20timer.png)


## Features

- **Timer Functionality**: Start/pause/reset with customizable work sessions
- **Subject Tracking**: Track study time across multiple subjects (Maths, Coding, Econometrics, Finance)
- **Analytics Dashboard**: 7-day progress charts with interactive visualizations
- **Goal Setting**: Set and track daily study goals with progress indicators
- **Data Persistence**: All data saved locally in browser storage
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## How It's Made

**Tech Stack**: HTML5, CSS3, Vanilla JavaScript, SVG Charts

Built with a focus on performance and user experience, featuring:
- Custom SVG chart rendering for analytics
- Local storage API for data persistence
- Event-driven architecture for real-time updates
- Responsive grid layout with CSS Grid and Flexbox
- Component-based JavaScript structure

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Running the Application
1. Clone or download this repository
2. Open `studytime.html` in your web browser

## Customization

### Changing Images
Replace the background images in the project:

1. **Background Images**: Replace files in the root directory:
   - `forest.jpg` - Main background image
   - `market.jpg` - Secondary background
   - `orange.jpg` - Accent background
   - `jap.jpg` - Alternative background
   - `fish_on_water.jpg` - Additional background option

2. **Update References**: If you rename images, update the CSS references in the HTML file's `<style>` section

### Customizing Subjects
Modifying subjects is now extremely simple - just edit the configuration at the top of the JavaScript section in `studytime.html`:

```javascript
// Easy subject configuration - modify these arrays to change subjects
const SUBJECTS = ['Maths', 'Coding', 'Econometrics', 'Finance'];
const DEFAULT_SUBJECT = 'Maths'; // Must be one of the subjects above
```

**To add or remove subjects:**
1. Open `studytime.html` in a text editor
2. Find the configuration section at the top of the JavaScript (around line 298)
3. Modify the `SUBJECTS` array - add, remove, or rename subjects
4. Optionally change the `DEFAULT_SUBJECT` to your preferred starting subject
5. Save the file and refresh your browser

**Example:**
```javascript
const SUBJECTS = ['Physics', 'Chemistry', 'Biology', 'History'];
const DEFAULT_SUBJECT = 'Physics';
```

The application will automatically:
- Generate subject buttons in the dropdown menu
- Create analytics displays for each subject
- Handle data storage for all configured subjects
- Update all UI elements dynamically

### Changing Notification Sound
Replace `notification-sound.mp3` with your preferred audio file. The sound plays when the timer completes.


## About

**Daniel Bray**  
Email: daniel.bray@connect.qut.edu.au  
Phone: 0492426521  
LinkedIn: https://www.linkedin.com/in/daniel-nerome-bray/


