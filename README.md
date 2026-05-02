# DevOps Lab 🚀

Мой pet-проект для изучения DevOps практик.

## 🛠 Стек
- **Ansible** — автоматизация установки Docker
- **Docker** — контейнеризация
- **Kubernetes** — оркестрация (Kind)
- **Prometheus + Grafana** — мониторинг
- **GitHub Actions** — CI/CD

## 📁 Структура
├── kubernetes/
│ ├── deployment.yaml
│ └── service.yaml
├── first-playbook.yml
├── install-docker-platform.yml
├── install-nginx.yml
└── inventory.ini

text

## 🚀 Запуск
```bash
# Установка Docker
ansible-playbook install-docker-platform.yml

# Запуск приложения в K8s
kubectl apply -f kubernetes/
