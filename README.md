# Real-time-Object-Detection-System
  - YOLOv8 object detection pipeline  
  - REST inference API using FastAPI  
  - Web UI with Streamlit and webcam support  
  - Containerized using Docker  
  - Deployed on Kubernetes (local cluster)
# Project Structure
```
object-detection-yolo/
├── frontend/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   └── Dockerfile
├── k8s/
│   ├── backend-deployment.yaml
│   ├── backend-service.yaml
│   ├── frontend-deployment.yaml
│   └── frontend-service.yaml
├── README.md
