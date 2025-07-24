

# React Accordion Component

![Project Preview](./public/project-image.png)

## About

A responsive and interactive accordion component built with React. This project demonstrates essential React concepts through a clean, collapsible FAQ interface with smooth state management.

## How It Works

The accordion displays a list of FAQ items that can be expanded/collapsed by clicking. Only one item can be open at a time, creating a smooth user experience. Each item shows a question with an expand/collapse icon, and clicking reveals the answer below.

## React Concepts Learned

- **useState Hook** - Managing component state for open/closed accordion items
- **Props & Props Drilling** - Passing data and functions between parent and child components
- **Component Composition** - Breaking down UI into reusable, modular components
- **Conditional Rendering** - Showing/hiding content based on state
- **Event Handling** - Managing click events and state updates
- **Controlled Components** - Managing state from parent component
- **Key Prop** - Proper list rendering with unique identifiers

## Project Structure

```
Accordian-Component/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── manifest.json
│   └── project-image.png
├── src/
│   ├── components/
│   │   ├── App.js
│   │   └── test.js
│   ├── index.js
│   └── styles.css
├── package.json
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ashifulalam/accordian-component.git
cd accordian-component
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm start
```

The application will open in your browser at `http://localhost:3000`.


