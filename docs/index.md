# Python App - Crocs

## 📖 Overview
Aplicación Flask que expone información del servidor con endpoints REST y health checks.

## 🏗️ Arquitectura
- **Lenguaje**: Python 3.12
- **Framework**: Flask 3.1.3
- **Containerización**: Docker (Alpine Linux)
- **Orquestación**: Kubernetes (EKS)
- **Auto-scaling**: HPA configurado

## 📡 API Endpoints
- `GET /api/v1/details` - Retorna message, timestamp y hostname
- `GET /api/v1/healthz` - Health check (status: up)

## 🚀 Deployment
- **Kubernetes ConfigMaps**: Configuración centralizada
- **Persistent Storage**: PVCs para datos persistentes
- **Ingress**: Enrutamiento de tráfico
- **Load Balancer**: Balanceo de carga disponible

## 🔧 Stack Tecnológico
- Python 3.12 Alpine
- Flask 3.1.3
- Kubernetes (EKS)
- Docker

## 📊 Monitoramiento
- HPA: Auto-escalado basado en métricas
- Health checks integrados

## 👤 Propietario
- **Equipo**: backend
- **Owner**: @scoronadovasco

## 📝 Links
- GitHub: [scoronadovasco/python-app](https://github.com/scoronadovasco/python-app)