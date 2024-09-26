# Markdown Editor with Live Preview

This is a real-time Markdown editor built using **Node.js** and **React**. The editor allows users to write Markdown text on the left side, and it displays the rendered HTML output in real-time on the right side.

## Features

- **Live Markdown to HTML Conversion**: As the user types Markdown, the editor converts it to HTML and displays it live in a preview pane.
- **Backend Markdown Processing**: Markdown to HTML conversion is handled on the backend using a Node.js server.
- **Customizable Markdown**: You can write any valid Markdown in the editor, and it will be rendered in HTML in the preview pane.

## Project Structure

This project is split into two parts:

1. **Frontend**: Built with React, located in the `/frontend` folder.
2. **Backend**: A Node.js server that processes the Markdown input and converts it to HTML, located in the `/backend` folder.

## Installation

To set up and run the project locally, follow these steps:

### Prerequisites

Make sure you have the following installed:

- Node.js (v14+)
- npm (v6+)

### Backend Setup

1. Navigate to the `/backend` folder:
    ```bash
    cd backend
    ```
2. Install backend dependencies:
    ```bash
    npm install
    ```
3. Start the backend server:
    ```bash
    npm start
    ```
   The backend server will be running on `http://localhost:3000`.

### Frontend Setup

1. Open a new terminal window and navigate to the `/frontend` folder:
    ```bash
    cd frontend
    ```
2. Install frontend dependencies:
    ```bash
    npm install
    ```
3. Start the React frontend:
    ```bash
    npm start
    ```
   
## Usage

- Type Markdown text in the left pane (textarea).
- The rendered HTML will appear in the right pane in real-time.

### Example Markdown

You can try the following Markdown examples in the editor:

```markdown
# Heading 1
## Heading 2
**Bold text**

- List item 1
- List item 2

[Link to Google](https://www.google.com)
