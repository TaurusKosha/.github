# SETUP.md

## 🚀 Setting Up TaurusKosha Projects
Follow these steps to set up your development environment for TaurusKosha repositories.

### Prerequisites
Ensure you have the following installed:
- **Git**: `https://git-scm.com/downloads`
- **Node.js & npm (for JavaScript/TypeScript projects)**: `https://nodejs.org/`
- **Python & pip (for AI/ML & backend projects)**: `https://www.python.org/`
- **Java (for Java-based services)**: `https://adoptopenjdk.net/`
- **Docker (for containerized environments)**: `https://www.docker.com/`

### 🔹 Clone the Repository
```sh
git clone https://github.com/tauruskosha/project.git
cd project
```

### 🔹 Install Dependencies
#### JavaScript/TypeScript (Node.js)
```sh
npm install  # or yarn install
```

#### Python
```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

#### Java
```sh
mvn clean install
```

### 🔹 Environment Configuration
Create a `.env` file and set up environment variables based on `.env.example`.

### 🔹 Running the Project
#### Node.js
```sh
npm run dev  # or yarn dev
```

#### Python
```sh
uvicorn main:app --reload
```

#### Java (Spring Boot)
```sh
mvn spring-boot:run
```

---

# CONTRIBUTING.md

## 📜 Contribution Guidelines
We welcome all contributors to **TaurusKosha**! Follow these guidelines to contribute effectively.

### 🛠️ Code of Conduct
- Be respectful & inclusive.
- Follow clean coding standards.
- Submit meaningful contributions.

### 🏗️ How to Contribute
1. **Fork the repository** & create a new branch.
2. **Make your changes**, ensuring they follow the coding guidelines.
3. **Commit with meaningful messages**:
   ```sh
   git commit -m "feat: Added authentication module"
   ```
4. **Push your branch** & create a **Pull Request (PR)**.
5. **Wait for review & feedback** from maintainers.

### 🔍 Code Formatting Standards
- **JavaScript/TypeScript**: Prettier + ESLint
- **Python**: Black + Flake8
- **Java**: Google Java Style Guide

### 🏆 Getting Started with Issues
- Check [GitHub Issues](https://github.com/tauruskosha/project/issues) for tasks.
- Comment on an issue before starting.

## 🚀 Join the Discussion
- **Discord**: [Join our community]
- **GitHub Discussions**: [Start a topic]

Let's build together! 🚀

