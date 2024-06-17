# Dev Restaurant Web App

Welcome to the Dev Restaurant Web App repository! This project is a comprehensive example of building a Progressive Web App (PWA) with a strong emphasis on accessibility, mobile-first design, and modern web development practices. The Dev Restaurant Web App is designed to provide users with an intuitive and engaging platform to discover and review restaurants, integrating a range of advanced web development concepts and techniques.

## Project Overview

The Dev Restaurant Web App is crafted to offer an extensive and accessible platform for browsing and discovering restaurants. Leveraging a mobile-first approach, this application ensures an optimal user experience on all devices. Additionally, the project highlights the importance of Progressive Web Apps (PWAs) by incorporating features such as offline capabilities, push notifications, and background synchronization.

## Key Features

### Accessibility
- Ensured the app is accessible to all users, including those with disabilities.
- Implemented ARIA roles and properties to enhance screen reader compatibility.
- Focus management and tab order improvements to facilitate keyboard navigation.

### Mobile-First Approach
- Designed the user interface with a mobile-first mindset to ensure a seamless experience across all device sizes.
- Utilized responsive design techniques to adapt the layout to different screen sizes and orientations.

### Progressive Web Apps (PWA)
- Implemented key PWA features such as Service Workers, Web App Manifest, and caching strategies to enhance performance and offline capabilities.
- Added installability features to allow users to install the app on their devices.

### Web Architecture
- Adopted a structured web architecture to separate concerns and improve maintainability.
- Used an application shell architecture to provide a reliable and performant user experience.

### Dependency Management
- Utilized npm to manage project dependencies and ensure consistency across development environments.
- Configured Webpack for bundling and optimizing the application’s assets.

### Code Style
- Established a consistent code style using ESLint and Prettier.
- Enforced coding standards to maintain code quality and readability.

### URL Router
- Implemented a URL routing system to handle client-side navigation.
- Enabled deep linking to specific pages within the application.

### API Integration
- Integrated with a third-party API to fetch and display restaurant data.
- Handled API requests and responses to provide dynamic content.

### Offline Capabilities
- Configured Service Workers to cache assets and API responses.
- Implemented caching strategies to ensure the app works offline and loads quickly.

### IndexDB
- Utilized IndexDB for local storage of restaurant data.
- Performed CRUD (Create, Read, Update, Delete) operations on IndexDB to manage user data.

### User Interactions
- Added a "favorite" button to allow users to save their favorite restaurants.
- Displayed data from IndexDB to show liked restaurants.

### Notifications
- Implemented Web Push Notifications to keep users informed about new content.
- Used Web Sockets for real-time updates and notifications.

## Implementation Details

### Responsive Design
- **CSS Grid System and Media Queries**: Used to build a mobile-first, responsive layout ensuring compatibility across different screen sizes and devices.

### Accessibility Enhancements
- **Semantic HTML**: Ensured the use of semantic elements to enhance accessibility.
- **Focus Management**: Implemented to improve navigation for keyboard users.
- **Screen Reader Support**: Verified compatibility with popular screen readers.

### Progressive Web Apps (PWA)
- **Service Workers**: Utilized to cache assets and API responses, allowing for offline access and improved performance.
- **Web App Manifest**: Included to provide metadata about the application and enable installation on user devices.

### Performance Optimization
- **Web Performance Auditing**: Used tools like Lighthouse to audit and optimize the app's performance, focusing on load times and interactivity.

### CI/CD Pipeline
- **GitHub Actions**: Set up for automated testing and deployment, ensuring a streamlined and efficient release process.

## Technologies Used

- **HTML/CSS/JavaScript**: The core technologies for front-end development.
- **CSS Grid System and Media Queries**: For creating a responsive layout.
- **Service Workers**: For enabling offline capabilities and improving performance.
- **Lighthouse**: For performance auditing and optimization.
- **Jest and Cypress**: For unit, integration, and end-to-end testing.
- **GitHub Actions**: For setting up the CI/CD pipeline.
- **Webpack**: For bundling and optimizing assets.
- **ESLint and Prettier**: For enforcing consistent code style and standards.

## Learning Experience

Building the Dev Restaurant Web App was an enriching experience that covered a wide range of web development concepts. From configuring Webpack to handling API requests, each step provided valuable insights into creating modern web applications. Implementing PWA features such as Service Workers and Web App Manifest enhanced my understanding of offline capabilities and performance optimization.

The project also emphasized the importance of accessibility and responsive design, ensuring the app is usable and enjoyable for all users. Working with IndexDB for local storage and managing CRUD operations deepened my knowledge of client-side databases and data persistence.

Overall, this project has equipped me with the skills and confidence to develop robust, user-friendly, and performant web applications.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/nielshn/dev-restaurant-web-app.git
   ```
2. **Navigate to the project directory**:
   ```sh
   cd dev-restaurant-web-app
   ```
3. **Install depedencies**:
   ```sh
   npm install
   ```
4. **Build the project**:
   ```sh
   npm run build
   ```
5. **Start the development server**:
   ```sh
   npm run start-dev
   ```
6. **Serve the build locally**:
   ```sh
   npm run build-serve
   ```
Alternatively, you can check the scripts defined in the package.json file to understand how to run the project:
```json
{
  "scripts": {
    "start": "node server.js",
    "start-dev": "webpack-dev-server --mode development",
    "build": "webpack --mode production",
    "build-serve": "serve -s dist"
  }
}
```
---

## Conclusion
The Dev Restaurant Web App is a testament to the power and flexibility of modern web development techniques. By focusing on accessibility, mobile-first design, and PWA features, this project demonstrates how to build a web app that is both user-friendly and technologically advanced.

Feel free to explore the repository and provide any feedback or suggestions. Thank you for your interest in the Dev Restaurant Web App!

---------
Thank you for checking out the Dev Restaurant Web App repository. We hope you find this project useful and informative. If you have any questions or need further assistance, feel free to reach out.

Happy coding!
