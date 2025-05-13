# Travel Agency Dashboard

Welcome to the **Travel Agency Dashboard**! This project is designed to provide a modern and interactive dashboard for managing travel agency operations. It leverages the power of **TypeScript**, **Docker**, and **CSS** to deliver a scalable and user-friendly experience.

## 🚀 Features

- **Dynamic Dashboard:** Manage key metrics and data for your travel agency in real-time.
- **TypeScript Driven:** Strongly-typed codebase for maintainability and scalability.
- **Dockerized Setup:** Easy deployment using Docker for consistent and isolated environments.
- **Custom Styling:** Enhanced and responsive user interface built with CSS.

## 🛠️ Technologies Used

- **TypeScript (88.5%)**: The core programming language used for the application.
- **Dockerfile (7.7%)**: Simplifies deployment and environment configuration.
- **CSS (3.8%)**: For styling and ensuring a modern and responsive design.

## 📂 Project Structure

```plaintext
├── src/                    # Source code for the application
│   ├── components/         # Reusable UI components
│   ├── pages/              # Page-level components
│   ├── services/           # API and data management logic
│   ├── utils/              # Utility functions
│   └── assets/             # Images, icons, and other static resources
├── Dockerfile              # Docker configuration
├── public/                 # Public resources (e.g., index.html)
├── styles/                 # Global and modular CSS files
└── README.md               # Project documentation

### Installation

Install the dependencies:

```bash
git clone https://github.com/ritikdevelop/Travel-Agency-Dashboard.git
cd Travel-Agency-Dashboard
```

### Development

Start the development server with HMR:

```bash
npm install
# or
yarn install
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm start
# or
yarn start
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.

---

Built with ❤️ using React Router.
