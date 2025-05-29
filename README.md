# Diploma Project: Animatica

This repository contains materials and description of my diploma project named **Animatica**.

### 🎓 Thesis Title

**Software for Image Animation Based on Neural Networks**

The project integrates a modern frontend, a RESTful backend, and an ML engine to generate animation
from image and driving video.

## 🔧 Project Structure

The project is split into three main components:

- [`Animatica-frontend`](https://github.com/kefirchk/Animatica-frontend): Streamlit-based user interface.
- [`Animatica-backend`](https://github.com/kefirchk/Animatica-backend): FastAPI backend for API routing, user management, and orchestration.
- [`Animatica-ml-engine`](https://github.com/kefirchk/Animatica-ml-engine): Python-based ML engine for image animation.

![system design](demo/system%20design.png)

## 🧠 Key Features

- 🔍 Automatic image animation
- 👤 User authentication and authorization
- 💳 Payment and subscription support
- 🚀 RESTful API for frontend/backend communication
- 📦 Dockerized architecture for easy deployment

## 💡 Technologies Used

| Layer         | Stack                                           |
|---------------|-------------------------------------------------|
| Frontend      | Streamlit, HTML, CSS                            |
| Backend       | Python, FastAPI, PostgreSQL, SQLAlchemy, JWT    |
| ML Engine     | Python, PyTorch, OpenCV, pre-trained FOMM model |
| DevOps        | Docker, Docker Compose, Unicorn, GitHub Actions |

## 📁 Installation

Clone the repositories:

```bash
git clone https://github.com/kefirchk/Animatica-frontend
git clone https://github.com/kefirchk/Animatica-backend
git clone https://github.com/kefirchk/Animatica-ml-engine
```

Follow installation guides in each repo. \
Alternatively, launch the full stack using Docker Compose.

## 📸 Demo

![demo](demo/demo.gif)

## 👨‍🎓 Author
__Alexey Klimovich__ \
Bachelor's Thesis, BSUIR, FCSN, 2025 \
📧 __Email__: _prostolex2004@mail.ru_ \
🐙 __GitHub__: _kefirchk_
