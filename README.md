
# 🚀 Roboshop Ansible Roles

This project automates the deployment of the Roboshop microservices application using Ansible Roles on AWS EC2 instances. It includes the setup and configuration of all required services such as MongoDB, Redis, MySQL, RabbitMQ, Catalogue, User, Cart, Shipping, Payment, and Frontend with Nginx. The project follows a modular role-based structure, making it easy to manage, maintain, and reuse.

---

## 📸 Project Screenshot

<img width="1920" height="1080" alt="Roboshop-ansible-Roles" src="https://github.com/user-attachments/assets/f84bb7d1-a470-4dee-9e7c-136ef7da0e65" />


## 📌 Services

- MongoDB
- Catalogue
- Redis
- User
- Cart
- MySQL
- Shipping
- RabbitMQ
- Payment
- Frontend

---

## 🛠️ Tools & Technologies

- Ansible
- AWS EC2
- Linux (RHEL 9)
- Nginx
- MongoDB
- Redis
- MySQL
- RabbitMQ
- Node.js
- Maven
- Python

---

## 📂 Project Structure

```text
Roboshop-Ansible-Roles/
├── inventory.ini
├── roboshop.yaml
├── README.md
└── roles/
    ├── common/
    ├── mongodb/
    ├── catalogue/
    ├── redis/
    ├── user/
    ├── cart/
    ├── mysql/
    ├── shipping/
    ├── rabbitmq/
    ├── payment/
    └── frontend/
```

---

## 🚀 Deployment

Deploy all services:

```bash
ansible-playbook -i localhost, roboshop.yaml -e '{"instances":["mongodb","catalogue","redis","user","cart","mysql","rabbitmq","shipping","payment","frontend"]}'
```

Deploy a single service:

```bash
ansible-playbook -e component=frontend roboshop.yaml
```

Replace `frontend` with any required component.

---

## 📸 Project Screenshot

> Add your project screenshot here.

```md
![Roboshop Application](images/roboshop-home.png)
```

---

## 👨‍💻 Author

**Uppalapu Sai Chaitanya**

GitHub: **https://github.com/chaitanya77711**
