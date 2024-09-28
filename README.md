
# Social Dashboard Platform

You can view the live version of the application here:

🔗 [Social Dashboard](https://social-dashboard-orcin.vercel.app/)

A dynamic internal social network platform built with **Next.js** and **Chakra UI**, designed for professional and clean UI/UX. The platform includes event management, posting, and friend request features, making it an ideal space for internal team collaboration and engagement.

## Features

- **Event Creation and Management**: Users can create events, choose from predefined categories, and view detailed information about each event.
- **Posts**: Users can post updates and interact with other users' posts by commenting and liking.
- **Friend Requests**: Users can send and accept friend requests to grow their internal network.
- **Responsive Design**: Built with responsive and adaptive UI for seamless experience on different screen sizes.
- **Custom Themes**: The UI is styled using a custom color theme with black, gray, and gold tones.

## Tech Stack

- **Next.js**: A powerful React framework for server-side rendering and building modern web applications.
- **Chakra UI**: For building the UI components with accessible and customizable design tokens.
- **React Icons**: For rendering dynamic icons based on event categories.
- **Tailwind CSS**: For additional styling and customization based on the project's theme.

## Getting Started

To get a local copy of the project up and running, follow these steps.

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v14 or later)
- **npm** or **yarn**

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/social-dashboard.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd social-dashboard
   ```

3. **Install dependencies**:

   If you're using npm:

   ```bash
   npm install
   ```

   Or if you're using yarn:

   ```bash
   yarn install
   ```

### Running the App

To start the development server, run:

```bash
npm run dev
```

Or with yarn:

```bash
yarn dev
```

The application will be available at:

```
http://localhost:3000
```

## Hosted Link

You can view the live version of the application here:

🔗 [Social Dashboard](https://social-dashboard-orcin.vercel.app/)

## Custom Theme

The app utilizes a custom theme with the following colors:

- **Primary Background Color**: `#262626` (Gray)
- **Accent Color**: `#FEA026` (Gold)
- **Text Color**: `#FFFFFF` (White)

### Screenshots

1. **Dashboard**:
   ![Dashboard](screenshots/dashboard.png)

## Folder Structure

```
/components
  - EventsSidebar.js        # Handles event creation and event details modal
/pages
  - index.js                # Main entry point for the dashboard
/styles
  - globals.css             # Global styles using Tailwind CSS
  - theme.js                # Chakra UI custom theme configuration
```

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/social-dashboard/issues) if you want to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Next.js** for making server-side rendering simple.
- **Chakra UI** for offering a customizable component library.
- **React Icons** for easy integration of icons into React projects.
