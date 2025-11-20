# 📒 Address Book for PC  
### University of Salerno (UNISA)  
**Software Engineering Course**  
**Group 02 - University Project**  

---

## 🚀 Project Description  
This project consists of developing a desktop application dedicated to address book management. The goal is to provide an intuitive and functional tool that allows users to save, organize, and search contacts easily.  

## 📋 Main Features  
- **Registration and Login:** Secure access with user credentials.  
- **Contact Management:** Add, edit, delete, and view contacts.  
- **Advanced Search:** Custom filters to quickly find contacts.  
- **Export/Import:** Save contacts in standard formats (e.g., CSV).  
- **User-Friendly Interface:** JavaFX for a modern and appealing user experience.  

## 🛠️ Technologies Used  
- **Programming Language:** Java  
- **Database:** PostgreSQL  
- **Frameworks and Libraries:** JavaFX, dotenv-java  
- **Security:** BCrypt for password hashing, dotenv for credential management  
- **Version Control Tools:** Git/GitHub  
- **Build Management:** MAVEN  
- **IDE Used:** NetBeans 23  

## 👥 Development Team  
The project was created by **Group 02**, consisting of 4 students from the Software Engineering course at the University of Salerno (UNISA):  

- **Postiglione Vittorio**  
- **Quaranta Valeria**  
- **Sanzari Mattia**  
- **Zouhri Anuar**  

## 📦 Installation  

### **Clone the repository:**  
```bash
git clone https://github.com/CupoMeridio/Ingegneria-del-software-2024-2025.git
```

### **Configure the database:**  
The application uses a remote database through services provided by [Aiven](https://aiven.io), so setting up a local database is not required.

### **Environment variables configuration:**  
For security reasons, database credentials are managed via environment variables. Follow these steps:

1. **Copy the example file:**  
   ```bash
   cp .env.example .env
   ```

2. **Edit the .env file** with your database credentials:
   ```
   DB_HOST=your-database-host.com
   DB_PORT=5432
   DB_NAME=your-database-name
   DB_USER=your-username
   DB_PASSWORD=your-password
   DB_SSL=require
   ```

3. **⚠️ IMPORTANT:** The `.env` file is already included in `.gitignore` to avoid committing credentials to GitHub. Do not remove it from `.gitignore`.  

### **Build and run the project:**  
Open the project in NetBeans 23. MAVEN will automatically manage dependencies.  

### **Executable file available:**  
The repository contains the first release of the project. To run the .jar file you need to download and install the Java runtime. You can download it here: [Java Downloads | Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).  

## 📄 Documentation
The repository includes the full documentation produced during the project's design and development. This includes:

- Requirements analysis
- UML diagrams (use cases, class diagrams, sequence diagrams, etc.)
- Development plan
- Technical manual in HTML format