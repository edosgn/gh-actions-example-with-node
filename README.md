# 🏍 API de pruebas

Este proyecto es una API REST desarrollada en **Node.js** con el framework **Express.js** usando base de datos en cache **Redis**. Utiliza **CI/CD** automatizado con **GitHub Actions**.

---

---

## 🚀 Tecnologías utilizadas

- Node.js
- Express.js
- Docker/Docker compose/DockerHub
- GitHub Actions (CI/CD)
- Swagger (Documentación API)
- Postman (Pruebas)

---

## 📦 Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/edosgn/gh-actions-example-with-node.git
cd gh-actions-example-with-node
```

### 2. Instalar dependencias

```bash
npm install
```

### 3. Ejecutar localmente

```bash
node index.js
```

La API estará disponible en: `http://localhost:3000/api/v1`

---

## 🐳 Uso con Docker

### Construye y levanta los contenedores

```bash
docker compose up --build
```

---

## 🔁 CI/CD

- Se utiliza **GitHub Actions** para ejecutar pruebas y construir la imagen para enviarla a DockerHub.

---

## 📚 Documentación Swagger

Disponible en la ruta:

```
/api-docs
```

Ejemplo:
```
http://localhost:3000/api-docs
```

---

## 🧪 Colección de pruebas Postman

Disponible en la ruta:

```
/test
```
