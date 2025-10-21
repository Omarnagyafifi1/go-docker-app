

---

### 📘 `README.md`

````markdown
# 🐳 Go Docker App

A simple **Go** application containerized using **Docker**.

---

## 🚀 Project Features
- A minimal Go application that prints a welcome message.
- Built using a **multi-stage Dockerfile** to reduce image size.
- Docker image hosted on **Docker Hub**.
- Source code hosted on **GitHub**.

---

## 🛠️ Requirements
Make sure you have the following installed:
- [Go](https://go.dev/dl/)
- [Docker](https://www.docker.com/)
- [Git](https://git-scm.com/)

---

## ⚙️ Run Locally (Without Docker)
```bash
# Clone the repository
git clone https://github.com/Omarnagyafifi1/go-docker-app.git
cd go-docker-app

# Run the application
go run main.go
````

---

## 🐳 Run with Docker

### 1️⃣ Build the Docker image

```bash
docker build -t omarnagyafifi1/go-docker-app:1.0 .
```

### 2️⃣ Run the container

```bash
docker run -p 8080:8080 omarnagyafifi1/go-docker-app:1.0
```

### 3️⃣ Open in browser

```
http://localhost:8080
```

---

## ☁️ Pull from Docker Hub

You can also pull the pre-built image directly:

```bash
docker pull omarnagyafifi1/go-docker-app:1.0
docker run -p 8080:8080 omarnagyafifi1/go-docker-app:1.0
```

---

## 📂 Project Structure

```
go-docker-app/
│
├── main.go
├── Dockerfile
├── .dockerignore
└── README.md
```

---

## 🐋 Docker Hub Image
You can find the public image here:  
👉 [https://hub.docker.com/r/omarnagyafifi1/go-docker-app](https://hub.docker.com/r/omarnagyafifi1/go-docker-app)


## 👤 Author

**Omar Nagy Afifi**
🔗 [Docker Hub](https://hub.docker.com/u/omarnagyafifi1)
🔗 [GitHub](https://github.com/Omarnagyafifi1)

```


