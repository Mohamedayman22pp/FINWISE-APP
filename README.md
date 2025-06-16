# 💸 FinWise - Creator Banking Application

> **A Spring Boot-based financial management platform with gamified UI, designed specifically for content creators, freelancers, and digital entrepreneurs.**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Available-brightgreen)](https://finwise-springboot-app-665d5dc86747.herokuapp.com)
[![GitHub Stars](https://img.shields.io/github/stars/MK-2206/FINWISE-APP)](https://github.com/MK-2206/FINWISE-APP/stargazers)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

<div align="center">
  <img src="https://raw.githubusercontent.com/MK-2206/FINWISE-APP/main/screenshots/1.png" alt="FinWise Dashboard Preview" width="800">
    <img src="https://raw.githubusercontent.com/MK-2206/FINWISE-APP/main/screenshots/3.png" alt="FinWise Dashboard Preview" width="800">
  <img src="https://raw.githubusercontent.com/MK-2206/FINWISE-APP/main/screenshots/4.png" alt="FinWise Dashboard Preview" width="800">
  <img src="https://raw.githubusercontent.com/MK-2206/FINWISE-APP/main/screenshots/5.png" alt="FinWise Dashboard Preview" width="800">
  <img src="https://raw.githubusercontent.com/MK-2206/FINWISE-APP/main/screenshots/6.png" alt="FinWise Dashboard Preview" width="800">
    <img src="https://raw.githubusercontent.com/MK-2206/FINWISE-APP/main/screenshots/7.png" alt="FinWise Dashboard Preview" width="800">


  **Visit the [live demo](https://finwise-springboot-app-665d5dc86747.herokuapp.com) to see the full interface!**
</div>

---

## 🎯 What is FinWise?

FinWise is a full-stack banking application that transforms chaotic creator finances into an organized, gamified experience. Built with Spring Boot backend and modern frontend technologies, it's designed for content creators who juggle multiple income streams and irregular earnings.

### ✨ **Why FinWise?**
- 💳 **Professional Banking Features** - Account management with real database persistence
- 📊 **Creator-Focused Analytics** - Track income streams, expenses, and financial goals
- 🎮 **Gamified Experience** - Level up system and achievement unlocks
- 💡 **Smart Financial Tools** - Tax calculators, investment analyzers, brand deal evaluators
- 🚀 **Real-time Updates** - Live financial summaries and progress tracking

---

## 🌟 Features

### 💰 **Core Banking Operations**
- **Account Management** - Create accounts with initial balances
- **Deposit & Withdraw** - Real-time balance updates via REST API
- **Transaction History** - Complete audit trail of all financial activities
- **Multi-Account Support** - Separate business and personal accounts

### 📊 **Creator Analytics Dashboard**
- **Income Tracking** - Multiple revenue streams (sponsorships, ad revenue, merchandise)
- **Expense Categorization** - Creator-specific expense categories
- **Financial Summary Cards** - Real-time profit/loss calculations
- **Chart.js Visualizations** - Beautiful charts for income trends

### 🎯 **Creator-Specific Tools**
- **Investment Calculator** - ROI analysis for equipment, courses, trips
- **Tax Estimator** - Quarterly tax calculations for freelancers
- **Brand Deal Calculator** - Evaluate sponsorship opportunities
- **Creator Goals** - Visual progress tracking with animated bars

### 🎮 **Gamification System**
- **XP & Leveling** - Earn experience points for financial activities
- **Creator Ranks** - Progress from "Rising Creator" to "Creator Master"
- **Achievement Badges** - Unlock milestones as you grow
- **Progress Celebrations** - Confetti animations and motivational messages

---

## 🚀 Tech Stack

<div align="center">

| Backend | Database | Frontend | Build Tool | Deployment |
|---------|----------|----------|------------|------------|
| ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white) | ![H2](https://img.shields.io/badge/H2-316192?style=for-the-badge&logo=h2&logoColor=white) | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) | ![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white) | ![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white) |
| ![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) | ![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white) | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) | ![Spring Boot](https://img.shields.io/badge/Spring_Boot_Maven-6DB33F?style=for-the-badge&logo=spring&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) |

</div>

### Architecture Overview
- **Backend**: Spring Boot REST API with Java 17
- **Database**: H2 in-memory (development) / PostgreSQL (production)
- **ORM**: Spring Data JPA with Hibernate
- **Frontend**: Vanilla JavaScript with Chart.js for analytics
- **Styling**: Custom CSS with glassmorphism design patterns
- **Build**: Maven for dependency management
- **Deployment**: Heroku with PostgreSQL add-on

---

## 🧪 Quick Start

### Prerequisites
- **Java 17+** (for Spring Boot backend)
- **Maven 3.6+** (for dependency management)


### Local Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/MK-2206/FINWISE-APP.git
   cd FINWISE-APP
   ```

2. **Run using Maven**
   ```bash
   # Using Maven wrapper (recommended)
   ./mvnw spring-boot:run
   
   # Or using installed Maven
   mvn spring-boot:run
   ```

3. **Access the application**
   ```
   🌐 http://localhost:8080
   ```

4. **Or visit live demo**
   ```
   🚀 https://finwise-springboot-app-665d5dc86747.herokuapp.com
   ```

### First Time Setup
1. 🏦 Create your first account with initial balance
2. 💰 Make some deposits to see the system in action
3. 📊 Explore the creator dashboard and analytics
4. 🎯 Set up financial goals and watch progress bars
5. 🎉 Level up by completing financial activities!

---

## 📂 Project Structure

```
FINWISE-APP/
├── src/
│   ├── main/
│   │   ├── java/com/marcoslombog/mybank/
│   │   │   ├── App.java                        # Main Spring Boot Application
│   │   │   ├── controller/
│   │   │   │   └── AccountController.java      # REST API endpoints
│   │   │   ├── model/
│   │   │   │   └── Account.java               # JPA Entity
│   │   │   ├── repository/
│   │   │   │   └── AccountRepository.java     # Data Access Layer
│   │   │   └── exception/
│   │   │       └── ResourceNotFoundException.java
│   │   └── resources/
│   │       ├── application.properties         # Spring Boot configuration
│   │       ├── data.sql                      # Initial database setup
│   │       └── static/
│   │           └── index.html                # Frontend application
│   └── test/
│       └── java/                             # Unit tests
├── target/                                   # Compiled classes
├── pom.xml                                  # Maven dependencies
└── README.md
```

---

## 🧑‍💻 API Documentation

### REST Endpoints

| Method | Endpoint | Description | Request Body |
|--------|----------|-------------|--------------|
| `GET` | `/accounts/all` | List all accounts | - |
| `GET` | `/accounts/{id}` | Get account by ID | - |
| `POST` | `/accounts/new` | Create new account | `{"name": "John Doe", "balance": 1000.0}` |
| `PUT` | `/accounts/{id}` | Deposit/withdraw money | `amount` (double) |

### Example API Calls

```bash
# Get all accounts
curl -X GET http://localhost:8080/accounts/all

# Create new account
curl -X POST http://localhost:8080/accounts/new \
  -H "Content-Type: application/json" \
  -d '{"name": "Creator Account", "balance": 5000.0}'

# Deposit money
curl -X PUT http://localhost:8080/accounts/1?amount=500.0
```

---

## 📊 Frontend Features

### 🎨 **Modern UI Components**
- **Glassmorphism Design** - Frosted glass aesthetic with backdrop blur
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile
- **Dark Theme** - Easy on the eyes for late-night financial planning
- **Smooth Animations** - CSS transitions and JavaScript-powered effects

### 📈 **Financial Analytics**
- **Chart.js Integration** - Beautiful income and expense visualizations
- **Real-time Updates** - Data refreshes automatically via AJAX calls
- **Creator Metrics** - Specialized charts for creator economy insights
- **Goal Progress Bars** - Animated progress indicators

### 🎮 **Gamification Elements**
```javascript
// XP system that rewards financial activities
function updateXP(points) {
    currentXP += points;
    checkLevelUp();
    updateProgressBar();
    if (points > 50) createConfetti();
}

// Smart investment break-even analysis
function calculateBreakEven(cost, monthlyBoost) {
    const months = cost / monthlyBoost;
    const roi = (monthlyBoost * 12 / cost) * 100;
    return { months, roi };
}
```

---

## ☁️ Deployment

### Heroku Deployment
The application is deployed on Heroku with the following configuration:

- **Web Application**: https://finwise-springboot-app-665d5dc86747.herokuapp.com
- **Database**: PostgreSQL add-on for production persistence
- **Build**: Automatic deployment from GitHub main branch
- **Environment**: Production profile with optimized settings

### Deployment Commands
```bash
# Deploy to Heroku
git push heroku main

# View logs
heroku logs --tail

# Check application status
heroku ps
```

---

## 🤝 Contributing

We welcome contributions! Here's how to get started:

### 🚀 **Quick Contribution Guide**
1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request


## 🏆 Achievements & Milestones

<div align="center">

| Achievement | Description | Unlock Condition |
|-------------|-------------|------------------|
| 🏦 **Account Creator** | Create your first bank account | Create 1 account |
| 💰 **First Deposit** | Make your first deposit | Add funds to account |
| 📊 **Analytics Explorer** | View financial dashboard | Access analytics page |
| 🎯 **Goal Setter** | Set your first financial goal | Create 1 goal |
| 🚀 **Creator Level 5** | Reach Creator Master rank | Earn 2000+ XP |
| ⚖️ **Smart Investor** | Use investment calculator | Calculate 1 ROI |

</div>

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License - Feel free to use, modify, and distribute!
Perfect for learning, portfolio projects, and commercial use.
```

---

## 🙏 Acknowledgments

### 💫 **Built With Love By**
- **[MK-2206](https://github.com/MK-2206)** - Full-stack development, Spring Boot architecture, UI/UX design

---



  
### 💎 **Professional Creator Banking**

*"Transforming creator finances from chaos to success, one transaction at a time."*

**[✨ Try FinWise Now](https://finwise-springboot-app-665d5dc86747.herokuapp.com)** | **[🔧 Contribute](https://github.com/MK-2206/FINWISE-APP/blob/main/CONTRIBUTING.md)** | **[📖 API Docs](https://github.com/MK-2206/FINWISE-APP/wiki)**

---

**FinWise Banking © 2025** - Built with 💜 for the creator economy

</div>
