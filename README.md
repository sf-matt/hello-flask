# 🧪 Hello Flask

This repository contains a flask application that serves a single page.

## 🚀 Features

- Flask app

---

## 🛠️ Build Instructions

Clone the repo and build the image locally:

### 🔧 Root Version (UID 0)

```bash
docker build -t youruser/hello-flask:latest .
```

---

## 🧪 Local Test

Run the container:

```bash
docker run -p 5000:5000 youruser/hello-flask:latest
```

Then hit the endpoint:

```bash
curl "http://localhost:5000/"
```

---

## 🐳 Docker Hub

If pushed to Docker Hub, use these images directly in Kubernetes:

```yaml
image: youruser/hello-flask:latest
```

---

## 🛡️ Tags

`flask` • `demo-app`