# Personal Digital Assistants (PDAs)

This project showcases a simple React application that displays profile cards for popular personal digital assistants (PDAs) like Alexa, Cortana, and Siri. The application is styled using the Bulma CSS framework.

## Features

- **React Components**: The project uses React components to create reusable and modular UI elements.
- **Bulma for Styling**: The main CSS framework is used to style the application, providing a clean and responsive design.
- **Dynamic Props**: Each profile card dynamically displays information passed as props, such as the title, handle, image, and description.

## How It Works

1. **Bulma Integration**:
   The `bulma` package is installed and imported in the `App.jsx` file to style the application. This provides pre-designed CSS classes for layout and components.

```jsx
import "bulma/css/bulma.css";
```

2. Profile Cards:
   The `ProfileCard` component is used to display individual PDAs. It accepts props such as `title`, `handle`, `image`, and `description` to render unique content for each card.

3. Images:
   Images for Alexa, Cortana, and Siri are imported and passed as props to the `ProfileCard` component.

4. Main Layout
   The `App.jsx` file organizes the profile cards into a responsive grid layout using Bulma's column classes.

## How to Run

1. Clone the repository:

```linux
git clone git@github.com:luisc8487/personal-digital-assistants.git
cd pdas
```

2. Install dependencies:

```linux
npm install
```

3. Go to `pdas` folder and follow the instructions from their

## Dependencies

- **React**: A JavaScript library for building user interfaces.
- **Bulma**: A modern CSS framework based on Flexbox for styling.
