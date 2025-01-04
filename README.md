# webApp
Full Stack Web Application using java spring boot MVC and Reactjs
project-root/
├── backend/          # Spring Boot project
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/backend/
│   │   │   │   ├── config/         # Configuration classes (e.g., Security, Kafka)
│   │   │   │   ├── controller/     # REST controllers
│   │   │   │   ├── dto/            # Data Transfer Objects (DTOs)
│   │   │   │   ├── entity/         # JPA entities
│   │   │   │   ├── exception/      # Custom exception handling
│   │   │   │   ├── repository/     # Spring Data JPA repositories
│   │   │   │   ├── service/        # Business logic
│   │   │   │   └── BackendApplication.java # Main Spring Boot application
│   │   │   ├── resources/
│   │   │   │   ├── static/         # Static resources (e.g., HTML, CSS if needed)
│   │   │   │   ├── templates/      # Templates for rendering (if using Thymeleaf)
│   │   │   │   ├── application.yml # Configuration for all environments
│   │   │   │   ├── logback-spring.xml # Logging configuration
│   │   │   │   └── keystore.p12    # SSL certificate
│   │   └── test/                   # Unit and integration tests
│   ├── target/                     # Compiled output (generated after build)
│   └── pom.xml                     # Maven dependencies and project configuration
│
└── frontend/         # React project
    ├── public/
    │   ├── index.html  # Main HTML file
    │   └── favicon.ico # Application icon
    ├── src/
    │   ├── components/  # Reusable React components
    │   │   ├── Header.js
    │   │   ├── Footer.js
    │   │   └── Login.js
    │   ├── pages/       # Page-level components
    │   │   ├── HomePage.js
    │   │   ├── Dashboard.js
    │   │   └── NotFound.js
    │   ├── services/    # API service for connecting to backend
    │   │   └── apiService.js
    │   ├── oktaConfig.js # Okta configuration
    │   ├── App.js        # Main application file
    │   ├── index.js      # React entry point
    │   └── App.css       # Global styles
    ├── node_modules/     # Node.js dependencies
    ├── .env              # Environment-specific variables (e.g., Okta config)
    ├── package.json      # React project dependencies and scripts
    ├── package-lock.json # Dependency tree lockfile
    └── webpack.config.js # Webpack configuration (if needed)
