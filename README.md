# fastapi-mongodb-k8s-demo
A comprehensive microservice demonstration project showcasing modern containerized application development and deployment practices

## Tech Stack:
- Backend: FastAPI (Python async framework)
- Database: MongoDB
- Containerization: Docker
- Orchestration: Kubernetes
- Package Management: Helm
- Local K8s: Minikube

## Project Structure:
- app/                 # FastAPI application source code
- docker/              # Dockerfiles and container configs
- k8s/                 # Kubernetes YAML manifests
- helm/                # Helm charts for deployment
- docs/                # Documentation
- README.md            # Setup and usage instructions

---

> ## Original Tasks:
> 1. 建立一個個人repo，並使用pull request/merge方式儲存以下的功能
> 2. 一個以fastapi提供簡易服務的server，asynchronized
> 3. 該簡易服務server須提供一個基於mongodb儲存資料的簡易的CURD api
> 4. api可以使用post帶入資料儲存或進行操作
> 5. 使用dockerfile將上述server打包成image
> 6. 將mongodb server + fastapi server建立於本機的minikube中(使用Helm)，並可以順利在瀏覽器 or postman上呼叫該server提供的api
> 7. 最終在repo中至少需要有：server source code, dockerfiles, k8s yaml files, 執行helm所需檔案
