# HTML Viewer

A modern, minimalistic HTML editor and live preview tool built with vanilla JavaScript, Tailwind CSS, and Font Awesome icons. Perfect for quickly testing HTML code, prototyping, or learning web development.

## ✨ Features

- **📝 Live Code Editor**: Full-screen code editor with monospace font and syntax highlighting support
- **👁️ Real-time Preview**: Instant HTML rendering in a secure sandboxed iframe
- **🌙 Dark Mode Support**: Automatic detection and switching based on system preferences
- **📱 Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **⚡ Keyboard Shortcuts**: Quick navigation with keyboard commands
- **🎨 Modern UI**: Clean, minimalistic interface with smooth animations
- **🔒 Safe Rendering**: Sandboxed iframe prevents malicious code execution
- **💾 No Storage Required**: Runs entirely in the browser without server dependencies

## 🚀 Getting Started

1. **Download or copy the HTML file**
2. **Open in any modern web browser**
3. **Start coding!** - The editor comes with sample HTML to get you started

No installation, dependencies, or server setup required!

## 📖 How to Use

### Basic Usage

1. **Write/Edit Code**: Use the full-screen editor to write or paste your HTML code
2. **Preview**: Click the blue eye icon (👁️) in the bottom-right corner to see your HTML rendered
3. **Go Back**: Click the gray arrow icon (←) to return to the editor

### Sample Code

The editor starts with sample HTML code demonstrating:
- Basic HTML structure
- CSS styling
- Responsive design patterns
- Typography and layout

### Views

- **Editor View**: Full-screen code editing with syntax highlighting
- **Preview View**: Live rendering of your HTML in a secure iframe

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + Enter` | Toggle between editor and preview |
| `Escape` | Return to editor (when in preview mode) |

## 🛠️ Technical Details

### Built With

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Flexbox layout, animations, and responsive design
- **JavaScript (ES6+)**: Modern JavaScript features and APIs
- **Tailwind CSS**: Utility-first CSS framework
- **Font Awesome**: Professional icon library

### Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### Dependencies

All dependencies are loaded from CDN:
- **Tailwind CSS**: `https://cdn.tailwindcss.com`
- **Font Awesome**: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`

### Security Features

- **Sandboxed iframe**: Prevents malicious code from affecting the parent page
- **Blob URLs**: Secure content rendering without external dependencies
- **CSP Compatible**: Works within Content Security Policy restrictions

## 🎨 Customization

### Colors

The app uses a clean color palette:
- **Primary**: `#5D5CDE` (Blue-purple)
- **Light Background**: `#FFFFFF` (White)
- **Dark Background**: `#181818` (Dark gray)

### Fonts

- **Editor**: Monaco, Menlo, Ubuntu Mono (monospace)
- **UI**: System font stack for optimal readability

## 📱 Mobile Support

- Touch-friendly interface
- Responsive design adapts to all screen sizes
- Font sizes optimized to prevent zoom on mobile inputs
- Gesture support for navigation

## 🔧 Advanced Features

### Dark Mode

Automatically detects system preference:
```javascript
window.matchMedia('(prefers-color-scheme: dark)')
