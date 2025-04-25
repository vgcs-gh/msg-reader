# msg-reader

Forked from https://github.com/Rasalas/msg-reader

## Features

- Open and read *.msg and *.eml files directly in your browser
- View HTML content and inline images
- Pin important messages
- Multiple file support with message list
- Sort messages by date
- Drag & drop support

## Project Structure

The project is organized into several modules:

- `MessageHandler.js` - Manages message state and storage
- `UIManager.js` - Handles UI updates and rendering
- `FileHandler.js` - Manages file operations and drag & drop
- `utils.js` - Contains MSG file processing and utility functions
- `main.js` - Initializes and orchestrates the application
- `electron.js` - Electron main process for desktop application


## Usage

### Clone the repository

```bash
git clone https://github.com/vgcs-gh/msg-reader.git && cd msg-reader
```

### Install the dependencies

```bash
npm install
```

### Run the application

```bash
npm run start:web
```
A browser window should open with the application running.

## Development

### Clone the repository

```bash
git clone https://github.com/vgcs-gh/msg-reader.git && cd msg-reader
```

### Install the dependencies

```bash
npm install
```

### Run the application in development mode

```bash
npm run dev
```

A browser window should open with the application running.

The application will automatically reload when changes are made to the source code.

## Build Process

The application uses browserify to bundle the JavaScript modules and tailwindcss for styling.

### Build Commands

- `npm run build` - Builds both JavaScript and CSS
- `npm run build:js` - Bundles JavaScript modules
- `npm run build:css` - Compiles Tailwind CSS
- `npm run dev` - Runs development server with live reload
- `npm run start:web` - Runs msg-reader in a browser tab
- `npm run start:electron` - Runs msg-reader in an electron window
