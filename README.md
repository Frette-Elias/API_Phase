# API_Phase

## 📖 Om Prosjektet

En nettside hvor man kan finne været i sitt området. Lokasjon og favorittplasser vil bli lagret å husket med innlogging av bruker

## ✨ Funksjoner

- Vise været på hvilken som helst lokasjon

## 🌐 Live Demo

**Nettside:** [https://din-nettside.com](https://din-nettside.com)

## 💻 Teknologi

- Frontend: HTML, CSS, JavaScript
- Backend: Spring / Java
- Database: MongoDB / Docker.
- Hosting: Coming....

## 📁 Prosjektstruktur

```
my-spring-mongodb-app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── myapp/
│   │   │               ├── MyAppApplication.java
│   │   │               ├── config/
│   │   │               │   ├── MongoConfig.java
│   │   │               │   └── WebConfig.java
│   │   │               ├── controller/
│   │   │               │   ├── UserController.java (REST API)
│   │   │               │   └── WebController.java (HTML sider)
│   │   │               ├── model/
│   │   │               │   └── User.java
│   │   │               ├── repository/
│   │   │               │   └── UserRepository.java
│   │   │               └── service/
│   │   │                   ├── UserService.java
│   │   │                   └── impl/
│   │   │                       └── UserServiceImpl.java
│   │   └── resources/
│   │       ├── application.properties
│   │       ├── static/
│   │       │   ├── css/
│   │       │   │   ├── styles.css
│   │       │   │   └── bootstrap.min.css
│   │       │   ├── js/
│   │       │   │   ├── app.js
│   │       │   │   ├── user-service.js
│   │       │   │   ├── components/
│   │       │   │   │   ├── user-list.js
│   │       │   │   │   └── user-form.js
│   │       │   │   └── lib/
│   │       │   │       ├── jquery.min.js
│   │       │   │       └── bootstrap.min.js
│   │       │   ├── images/
│   │       │   │   └── logo.png
│   │       │   └── favicon.ico
│   │       └── templates/
│   │           ├── index.html
│   │           ├── users.html
│   │           ├── fragments/
│   │           │   ├── header.html
│   │           │   └── footer.html
│   │           └── error/
│   │               └── 404.html
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── myapp/
│                       ├── MyAppApplicationTests.java
│                       ├── controller/
│                       │   ├── UserControllerTest.java
│                       │   └── WebControllerTest.java
│                       └── service/
│                           └── UserServiceTest.java
├── pom.xml
├── Docs/
│   ├── api.md 
│   ├── user-guide.md 
│   └── technical.md 
└── README.md 
```

## 🚀 Status

- 🔄 Under utvikling

## 📚 Dokumentasjon

- [API Dokumentasjon](docs/api.md)
- [Brukerguide](docs/user-guide.md)
- [Teknisk oversikt](docs/technical.md)

## 🤝 Bidrag

Dette er et aktivt utviklingsprosjekt. Bidrag og forslag er velkomne!

1. Fork repositoryet
2. Opprett en feature branch
3. Commit endringene dine
4. Åpne en Pull Request

## 📄 Lisens

Fyll inn her... 

## 👤 Forfattere

**Elias Frette & Edvar Motrøen ** - [GitHub](https://github.com/Frette-Elias/) & [GitHub](https://github.com/h571569/)

---

⭐ Gi prosjektet en stjerne hvis du liker det!
