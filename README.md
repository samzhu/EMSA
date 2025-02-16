# EMSA
**Evolve, Modernize, Spring, AI**

EMSA is an open-source platform that leverages artificial intelligence to transform legacy code into modern Spring Boot architectures. It automates and simplifies the process of evolving outdated codebases, empowering developers to update, optimize, and secure their applications using the latest technologies.

## Features

- **AI-Powered Modernization**: Analyze and transform legacy code using advanced AI techniques.
- **Automated Code Evolution**: Automatically refactor and optimize code for improved scalability and maintainability.
- **Customizable Workflows**: Tailor the modernization process with flexible, developer-friendly workflows.

## Getting Started

### Prerequisites
- Java 21 or higher
- Gradle 8.12.1+
- Docker (optional)

## Installation

1. **Clone the Repository:**
   ```bash
   git clone git@github.com:samzhu/emsa.git
   cd emsa
   ```

2. **Build the Project:**
   Use the Gradle Wrapper to build the project:
   ```bash
   ./gradlew build
   ```

3. **Run the Application:**
   Start the application using the BootRun task:
   ```bash
   ./gradlew bootRun
   ```

## Usage

After starting the application, you can:
- Upload legacy code for analysis.
- Configure modernization options.
- Trigger the AI-driven transformation process.
- Monitor progress and review the modernized output via provided REST APIs or a web interface.

## Contributing

Contributions are welcome! To contribute:
- Fork the repository.
- Create a feature branch or bugfix branch.
- Submit a pull request detailing your changes.

For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the Spring community for their robust framework.
- Thanks to the contributors of various AI libraries that make this project possible.
