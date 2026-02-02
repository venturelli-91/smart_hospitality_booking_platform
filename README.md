# Smart Hospitality Booking Platform - Pousada Encanto da Serra 🏨

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Flowbite](https://img.shields.io/badge/Flowbite-FFDD00?style=for-the-badge&logo=flowbite&logoColor=black)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)
[![Zustand](https://img.shields.io/badge/zustand-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://github.com/pmndrs/zustand)
[![Env Variables](https://img.shields.io/badge/Environment--Variables-ECD53F?style=for-the-badge&logo=dotenv&logoColor=black)](https://nextjs.org/docs/basic-features/environment-variables)
![CORS](https://img.shields.io/badge/CORS-000000?style=for-the-badge&logo=mozilla&logoColor=white)

## 📝 Description

This project is a complete reservation system for Pousada Encanto da Serra, integrating a modern and responsive frontend with a robust backend for data processing and storage. Customers can make reservations through an intuitive form, and all information is stored in a PostgreSQL database.

The frontend was developed with Next.js, React, TypeScript, Tailwind CSS, and Flowbite, offering an attractive and responsive interface. The backend uses Express, Sequelize, and PostgreSQL to create a RESTful API that processes and stores reservations securely and efficiently.

## ✨ Screenshots

<p>
  <img src="https://github.com/venturelli-91/hotel_reservation/raw/main/Prints-ReadME/hotel1_project.png" alt="Screenshot 1" width="32%" />
  <img src="https://github.com/venturelli-91/hotel_reservation/raw/main/Prints-ReadME/hotel2_project.png" alt="Screenshot 2" width="32%" />
  <img src="https://github.com/venturelli-91/hotel_reservation/raw/main/Prints-ReadME/hotel3_project.png" alt="Screenshot 3" width="32%" />
</p>
<p>
  <img src="https://github.com/venturelli-91/hotel_reservation/raw/main/Prints-ReadME/hotel4_project.png" alt="Screenshot 4" width="32%" />
  <img src="https://github.com/venturelli-91/hotel_reservation/raw/main/Prints-ReadME/hotel5_project.png" alt="Screenshot 5" width="32%" />
  <img src="https://github.com/venturelli-91/hotel_reservation/raw/main/Prints-ReadME/hotel6_project.png" alt="Screenshot 6" width="32%" />
</p>

## 🔍 Features

### Frontend

- **Reservation Form**: Intuitive interface for customers to fill in their information
- **Data Validation**: Real-time verification of user-entered data
- **Responsive Design**: Consistent experience across mobile devices, tablets, and desktops
- **Visual Feedback**: Confirmation and error messages to keep the user informed

### Backend

- **RESTful API**: Endpoints to create, read, update, and delete reservations
- **Data Persistence**: Secure storage of information in PostgreSQL
- **Data Validation**: Information verification before saving to the database
- **Flexible Configuration**: Easily adaptable to different environments through environment variables

## 🛠️ Architecture

The system follows a modern client-server architecture:

```
Reservation_Hotel/
├── frontend/                # Next.js/React Application
│   ├── public/              # Static files
│   ├── src/                 # Frontend source code
│   │   ├── components/      # React components
│   │   ├── services/        # API communication services
│   │   ├── store/           # State management with Zustand
│   │   └── ...
├── backend/                 # Express server
│   ├── models/              # Sequelize models
│   └── ...
```

## 🚀 Technologies Used

### Frontend

<p>
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nextjs-colored-dark.svg" width="48" height="48" alt="Next.js" />
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="48" height="48" alt="React" />
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="48" height="48" alt="TypeScript" />
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tailwindcss-colored.svg" width="48" height="48" alt="Tailwind CSS" />
  <img src="https://flowbite.com/docs/images/logo.svg" width="48" height="48" alt="Flowbite" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="Context API" width="48" height="48"/>
</p>

### Backend

<p>
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/express-colored-dark.svg" width="48" height="48" alt="Express" />
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="48" height="48" alt="PostgreSQL" />
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="48" height="48" alt="Node.js" />
  <img src="https://sequelize.org/img/logo.svg" width="48" height="48" alt="Sequelize" />
  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="48" height="48" alt="TypeScript" />
  <img src="https://raw.githubusercontent.com/motdotla/dotenv/master/dotenv.png" width="48" height="48" alt="dotenv" />
  <img src="https://i.imgur.com/6WSYgYm.png" width="48" height="48" alt="CORS" />
</p>

## 🏃‍♂️ How to Run the Project

### Prerequisites

- Node.js (v14+)
- PostgreSQL
- npm or yarn

### Database Configuration

1. Install PostgreSQL
2. Create a database called `reservations`
3. Configure the credentials in the `.env` file of the backend

### Backend

```bash
# Navigate to the backend directory
cd backend

# Install dependencies
npm install

# Configure environment variables
# Create an .env file with the necessary variables:
# - Database connection
# - Other sensitive configurations
# NEVER share or expose this file publicly

# Test the database connection
npm run setup

# Start the server
npm run dev
```

### Frontend

```bash
# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

Access the application at http://localhost:3000.

## 📊 API Endpoints

- **POST /api/reservations**: Create a new reservation
- **GET /api/reservations**: List all reservations
- **GET /api/reservations/:id**: Get details of a specific reservation

## 🔧 Data Model

```typescript
// Reservation Model
interface Reservation {
	id: number;
	nomeCompleto: string;
	email: string;
	telefone: string;
	dataEntrada: string;
	dataSaida: string;
	qtdPessoas: number;
	createdAt: Date;
	updatedAt: Date;
}
```

## 🌟 Future Features

- **Admin Panel**: Interface to manage reservations
- **Authentication**: Login system for administrators
- **Email Notifications**: Automatic confirmation sending
- **Visual Calendar**: Viewing available dates
- **Payment System**: Integration with payment gateways

## 👨‍💻 Contributing

Fork this repository and feel free to contribute to this amazing project =D.

## 📬 Contact

- **Developer**: Aurélio Venturelli
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/aurelioventurelli/)
- **GitHub**: [GitHub Profile](https://github.com/venturelli-91)

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for more information.
