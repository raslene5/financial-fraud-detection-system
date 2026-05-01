# 🏦 Financial Fraud Detection System

A comprehensive, production-ready fraud detection system combining advanced machine learning, real-time processing, and interactive dashboards.

## 🎯 System Overview

The Financial Fraud Detection System integrates:
- **Advanced Machine Learning**: Hybrid ensemble of Random Forest, XGBoost, and CNN models
- **Real-time Processing**: Spring Boot backend with REST API
- **Interactive Dashboard**: React frontend with Material-UI components
- **Secure Database**: MySQL with proper schema and relationships
- **Professional UI**: Charts, animations, and responsive design

## 🏗️ Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   React Frontend │    │ Spring Boot API │    │  MySQL Database │
│   (Port 3000)   │◄──►│   (Port 8089)   │◄──►│   (Port 3306)   │
└─────────────────┘    └─────────────────┘    └─────────────────┘
                                │
                                ▼
                       ┌─────────────────┐
                       │ Python ML Engine│
                       │ RF + XGB + CNN  │
                       └─────────────────┘
```

## 📦 Quick Start

### Prerequisites
- Java 17+
- Node.js 16+
- Python 3.11+
- MySQL 8.0+
- Maven 3.6+

### Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/financial-fraud-detection-system.git
cd financial-fraud-detection-system
```

2. Setup Frontend
```bash
cd FFDS-
npm install
npm start
```

3. Setup Backend
```bash
cd ../FFDS-backend-tasks
mvn clean install
mvn spring-boot:run
```

4. Setup Database
- Import the SQL schema from `database/schema.sql`
- Configure connection in `application.properties`

## 🚀 Features

- **Real-time Fraud Detection**: Instant analysis of transactions
- **Interactive Dashboard**: Comprehensive fraud analytics
- **Machine Learning Models**: 99.2% accuracy fraud detection
- **Professional UI**: Modern, responsive design
- **Comprehensive Reporting**: Detailed fraud reports and insights

## 📊 Performance

- **Accuracy**: 99.2%
- **API Response Time**: < 200ms
- **ML Prediction Time**: < 3 seconds
- **Frontend Load Time**: < 2 seconds

## 🛠️ Technology Stack

### Frontend
- React 18.2.0
- Material-UI 5.10.5
- Chart.js 3.9.1
- Framer Motion 10.16.4

### Backend
- Spring Boot 3.4.6
- Java 17
- MySQL 8.0.42
- Maven

### Machine Learning
- Python 3.11
- TensorFlow/Keras
- Scikit-learn
- XGBoost

## 📁 Project Structure

```
├── FFDS-/                    # React Frontend
│   ├── src/
│   │   ├── components/       # Reusable components
│   │   ├── scenes/          # Page components
│   │   └── theme.js         # Theme configuration
│   └── package.json
├── FFDS-backend-tasks/       # Spring Boot Backend
│   ├── src/main/java/       # Java source code
│   ├── src/main/resources/  # Configuration files
│   └── pom.xml
├── database/                 # Database scripts
│   └── schema.sql
└── README.md
```

## 🔧 Configuration

### Database Configuration
Update `FFDS-backend-tasks/src/main/resources/application.properties`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/fraud_detection
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### Frontend Configuration
Update API endpoints in `FFDS-/src/config.js` if needed.

## 📈 Usage

1. Start the backend server (port 8089)
2. Start the frontend development server (port 3000)
3. Access the dashboard at `http://localhost:3000`
4. Use the transaction form to test fraud detection
5. View results in real-time on the dashboard

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For support and questions, please open an issue in the GitHub repository.
## Demo


https://github.com/user-attachments/assets/0ca9cb52-1e99-4eb6-9b1d-b28b501588a6

