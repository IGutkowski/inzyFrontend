# DIY IoT Projects and Tutorials Platform  

A web-based platform for sharing IoT projects and DIY tutorials. The platform enables users to publish projects, browse and search for ideas, create auto-generated shopping lists, and support creators through donations.  


## 🛠️ Tech Stack  
- **Frontend:** ReactJS + Vite ([Repo](https://github.com/IGutkowski/inzyFrontend))  
- **Backend:** Java Spring ([Repo](https://github.com/Jacbski/inzyBackend))  
- **Database:** MongoDB  Atlas

## 🎯 Features  
- **Project browsing and search** – Explore projects with filtering, pagination, and search functionalities.  
- **Project creation and publishing** – Users can submit and share IoT projects.  
- **Personalized shopping lists** – Required components are listed in auto-generated shopping list for easy access.  
- **Donations system** – Support project creators via Stripe donations.  
- **Favorite projects management** – Bookmark and manage favorite projects.  
- **Content reporting and rating system** – Report inappropriate content for moderation and rate projects.  

## 🛠 Installation and Setup  

### **1️⃣ Backend (Java Spring) Setup**  
Ensure you have **Java 17+**, **Maven** installed.  

Clone the backend repository:  
```bash
git clone https://github.com/Jacbski/inzyBackend.git
cd inzyBackend
```
Build and run the backend:
```bash
mvn clean install
mvn spring-boot:run
```

### **2️⃣ Frontend (React) Setup**
Ensure you have **Node.js** and **npm** installed.

Clone the frontend repository:  
```bash
git clone https://github.com/IGutkowski/inzyFrontend.git
cd inzyFrontend
```
Install dependencies:
```bash
npm install
```
Run the applcation:
```bash
npm start
```
or

```bash
vite
```

