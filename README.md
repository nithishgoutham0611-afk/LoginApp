# LoginApp
# LoginApp
## 📂 Project Structure
login_page/
│
├── Deployment Descriptor: login_page   # Deployment details
│
├── JAX-WS Web Services                 # (Not used in your case, can be ignored)
│
├── Java Resources/
│   └── src/main/java/
│       └── com.tap/
│           └── Login.java              # Java Servlet (handles login validation)
│
├── build/                              # Auto-generated build files (ignore in repo)
│
├── src/
│   └── main/
│       ├── java/                       # Java source code
│       └── webapp/                     # Web application files
│           ├── META-INF/               # Metadata (not usually edited)
│           ├── WEB-INF/                # Configuration files
│           │   └── web.xml             # Deployment descriptor (maps servlet)
│           │
│           ├── homepage.html           # Welcome page (after login success)
│           └── NewFile.html            # Login page (form with username & password)
│
└── lib/                                # (optional) External JAR libraries (if any)

A simple login web application built using **HTML**, **CSS**, and **Java Servlets**.  
The app validates user credentials and redirects to a welcome home page upon successful login.

---

## 🚀 Features
- Login form with **username** and **password** fields  
- Backend validation using **Java Servlets (doPost & doGet methods)**  
- Displays a **welcome page** when login is successful  
- Styled with **HTML + CSS**

---

## 🛠️ Technologies Used
- **Frontend**: HTML, CSS  
- **Backend**: Java Servlets  
- **Server**: Apache Tomcat  
- **IDE**: Eclipse / IntelliJ IDEA  

---



