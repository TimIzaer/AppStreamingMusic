<p align="center">
  <img src="http://i.imgur.com/oRGwu.png" alt="Beatstream Screenshot" width="800"/>
</p>

<h1 align="center">🎧 Beatstream</h1>

<p align="center">
  <strong>Streaming de música desde tu servidor a cualquier navegador moderno</strong><br>
  Disfruta tu biblioteca musical en cualquier lugar, sin depender de servicios externos.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Go-blue?style=for-the-badge&logo=go">
  <img src="https://img.shields.io/badge/Frontend-Node.js-green?style=for-the-badge&logo=node.js">
  <img src="https://img.shields.io/badge/Docker-Supported-blue?style=for-the-badge&logo=docker">
  <img src="https://img.shields.io/github/license/youruser/beatstream?style=for-the-badge">
</p>

---

## 🚀 Descripción

**Beatstream** es una aplicación que te permite transmitir música desde tu computadora o servidor directamente a tu navegador web.

- 📡 Streaming en tiempo real  
- 🌐 Acceso desde cualquier navegador moderno  
- 🎶 Organización automática de tu biblioteca  
- ⚡ Interfaz rápida y minimalista  

---

## ✨ Características

- 🎧 Reproducción de música vía web  
- 📁 Indexación automática de archivos  
- 🌍 Acceso remoto desde cualquier dispositivo  
- ⚡ Alto rendimiento gracias a Go  
- 🐳 Soporte completo con Docker  

---

## 📦 Instalación

### 🐳 Docker (Recomendado)

**Requisitos:** Docker

```bash
docker run -d \
  -p 8080:8080 \
  -v /ruta/a/tu/musica:/music \
  darep/beatstream:latest
```

👉 Abre en tu navegador:
```
http://localhost:8080
```


## 💻 Instalación Manual

Requisitos:
```
Go 1.22+
Node.js 20+
TagLib (libtagc)
git clone https://github.com/isairey/AppStreamingMusic
cd BAppStreamingMusic/frontend
npm install
npm run build
cd ..
go run .
```

---

## 👉 Abre:
```
http://localhost:8080
```

## ⚙️ Desarrollo

### 🔧 Configuración
```
cp .env.example .env
```

### ▶️ Ejecutar Backend
```
go run .
```

---

## 🎨 Ejecutar Frontend (modo desarrollo)
```
cd frontend
npm install
npm run dev
```

---

## 🐳 Desarrollo con Docker
```
cp .env.example .env
docker compose up
```

---

## 📁 Estructura del Proyecto
```
Beatstream/
├── frontend/        # Aplicación web (Node.js)
├── backend/         # Servidor en Go
├── .env.example     # Variables de entorno
├── docker-compose.yml
└── README.md
```

---

## 🧠 Cómo funciona

- Se monta tu carpeta de música
- Beatstream indexa automáticamente los archivos
- Accedes desde el navegador
- Disfrutas tu música desde cualquier lugar 🎶

---

## 🔐 Seguridad

- Acceso mediante login
- Tus archivos permanecen en tu servidor
- Sin dependencia de servicios externos

---

## 📌 Roadmap

- Sistema de playlists
- Modo offline
- App móvil
- Recomendaciones inteligentes

 ---
 
## 👨‍💻 Autor

**Isai Reyes**

---

## 📜 Licencia

License MIT.
