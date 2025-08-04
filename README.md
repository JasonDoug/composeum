# Composeum - Docker Compose Library

A modern, curated collection of reusable Docker Compose configurations for developers. Quickly find, copy, and deploy popular development stacks with ease.

## 🌟 Features

- **Curated Collection**: Hand-picked Docker Compose configurations for popular development stacks
- **Easy Search & Filter**: Find configurations by category, tags, or technology
- **One-Click Copy**: Copy Docker Compose files directly to your clipboard
- **Beautiful UI**: Modern, responsive interface built with React and Tailwind CSS
- **Categories Include**:
  - 🗄️ Databases (PostgreSQL, MySQL, MongoDB, Redis)
  - 🌐 Web Servers (Nginx, Apache)
  - 📊 Monitoring (Prometheus + Grafana, ELK Stack)
  - 🔄 CI/CD (Jenkins)
  - 📨 Message Queues (RabbitMQ, Apache Kafka)
  - 💾 Storage (MinIO)
  - 🛠️ Development Tools

## 🚀 Live Demo

Visit the live application: [Composeum](https://your-vercel-url.vercel.app)

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript
- **Styling**: Tailwind CSS, Radix UI
- **Build Tool**: Vite
- **Deployment**: Vercel
- **Package Manager**: pnpm

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jpotter702/composeum.git
   cd composeum
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   # or
   npm install
   ```

3. **Start the development server**
   ```bash
   pnpm dev
   # or
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Build & Deploy

### Local Build
```bash
pnpm build
pnpm preview
```

### Deploy to Vercel
The project is configured for easy deployment on Vercel:

1. Fork this repository
2. Connect your GitHub account to Vercel
3. Import the project
4. Deploy automatically with the included `vercel.json` configuration

## 📁 Project Structure

```
composeum/
├── public/
│   ├── assets/
│   │   └── thumbnails/     # Service thumbnails
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── ui/             # Reusable UI components
│   │   ├── ComposeCard.jsx # Main card component
│   │   └── ...
│   ├── data/
│   │   └── sampleData.js   # Docker Compose configurations
│   ├── lib/
│   │   └── utils.js        # Utility functions
│   └── App.jsx
├── vercel.json             # Vercel deployment config
└── package.json
```

## 🎨 Available Configurations

### Databases
- **PostgreSQL + pgAdmin** - Complete database setup with web interface
- **MySQL + phpMyAdmin** - MySQL with administration interface
- **MongoDB Replica Set** - High-availability MongoDB cluster
- **Redis Cache** - High-performance caching solution

### Web Servers
- **Nginx Reverse Proxy** - SSL termination and load balancing
- **Apache HTTP Server** - Traditional web server setup

### Monitoring & Observability
- **Prometheus + Grafana** - Complete metrics and visualization stack
- **ELK Stack** - Elasticsearch, Logstash, and Kibana for log analysis

### Development Tools
- **Node.js Development** - Hot reload and debugging setup
- **Jenkins CI/CD** - Continuous integration and deployment

### Message Queues
- **RabbitMQ** - Reliable message broker with management interface
- **Apache Kafka** - Distributed streaming platform

### Storage
- **MinIO** - S3-compatible object storage

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/new-compose-config
   ```
3. **Add your Docker Compose configuration**
   - Add the configuration to `src/data/sampleData.js`
   - Include a thumbnail image in `public/assets/thumbnails/`
   - Follow the existing data structure
4. **Commit your changes**
   ```bash
   git commit -m "Add new Docker Compose configuration for [service]"
   ```
5. **Push and create a Pull Request**

### Adding New Configurations

When adding new Docker Compose configurations, please ensure:

- **Complete Setup**: Include all necessary services and dependencies
- **Environment Variables**: Use sensible defaults for development
- **Documentation**: Add clear descriptions and usage notes
- **Security**: Use secure default passwords (document them clearly)
- **Best Practices**: Follow Docker Compose best practices

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Docker](https://docker.com) for containerization technology
- [React](https://reactjs.org) for the amazing frontend library
- [Tailwind CSS](https://tailwindcss.com) for utility-first styling
- [Radix UI](https://radix-ui.com) for accessible component primitives
- [Vercel](https://vercel.com) for seamless deployment

## 📞 Support

If you have questions or need help:

- Open an [issue](https://github.com/jpotter702/composeum/issues) on GitHub
- Start a [discussion](https://github.com/jpotter702/composeum/discussions)

---

Made with ❤️ for the developer community. Happy containerizing! 🐳
