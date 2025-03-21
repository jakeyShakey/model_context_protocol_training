# Model Context Protocol (MCP) Presentation

This repository contains a presentation about the Model Context Protocol (MCP) built using [Slidev](https://sli.dev/), a modern presentation tool for developers.

## Prerequisites

Before you can run this presentation, you need to have the following installed:

- [Node.js](https://nodejs.org/) (v14 or above)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)
- [Git](https://git-scm.com/) (for version control)

## Getting Started

Follow these steps to run the presentation locally:

1. **Clone this repository** (if you haven't already)

   ```bash
   git clone <repository-url>
   cd mcp
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the presentation**

   ```bash
   npm run dev
   ```

   This will start the development server and open the presentation in your default web browser. If it doesn't open automatically, you can access it at [http://localhost:3030](http://localhost:3030).

## Navigation Controls

Once the presentation is running:

- **Arrow keys**: Navigate between slides (left/right)
- **Space**: Next slide
- **Shift + Space**: Previous slide
- **o**: Toggle overview mode
- **d**: Toggle dark mode
- **p**: Toggle presenter mode

## Editing the Presentation

The main content of the presentation is in the `slides.md` file. You can edit this file to modify the presentation content.

## Git Version Control

This project includes a `.gitignore` file configured to exclude unnecessary files like `node_modules` and build artifacts.

### Setting up Git for this project

If you're starting from scratch:

1. **Initialize a Git repository**

   ```bash
   git init
   ```

2. **Add your files**

   ```bash
   git add .
   ```

3. **Commit your changes**

   ```bash
   git commit -m "Initial commit"
   ```

4. **Add a remote repository** (replace with your actual repository URL)

   ```bash
   git remote add origin https://github.com/yourusername/your-repo-name.git
   ```

5. **Push to the remote repository**

   ```bash
   git push -u origin main
   ```

### Making changes

After making changes to your presentation:

```bash
git add .
git commit -m "Description of your changes"
git push
```

## Building for Production

To build the presentation for production deployment:

```bash
npm run build
```

This will generate a static version of the presentation in the `dist` folder that you can deploy to any static hosting service.

## Exporting to PDF

To export the presentation to PDF:

```bash
npm run export
```

This will generate a PDF version of your presentation.

## Learn More About Slidev

- [Slidev Documentation](https://sli.dev/)
- [Slidev GitHub Repository](https://github.com/slidevjs/slidev)

## About Model Context Protocol (MCP)

The Model Context Protocol (MCP) is a standardized interface for connecting AI models to external data and tools. This presentation provides an overview of MCP, its architecture, and implementation guidelines. 