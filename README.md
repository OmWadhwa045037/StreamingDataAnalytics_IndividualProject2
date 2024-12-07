# **EspoCRM-in-Docker**

EspoCRM is an open-source Customer Relationship Management (CRM) solution designed for managing sales, customer support, marketing, and other business processes. It provides an intuitive interface, high customizability, and robust performance, empowering businesses to streamline operations and manage relationships effectively.

---

## **Pre-requisites**
1. A system with Docker installed and configured.
2. Basic knowledge of command-line tools.

---

## **Steps**

### **1. Pull the EspoCRM Docker Image**

Run the following command to pull the official EspoCRM image:
```bash
docker pull espocrm/espocrm
```

### **2. Start the EspoCRM Instance**

Use this command to start an EspoCRM container:
```bash
docker run -d -p 8080:80 espocrm/espocrm
```

---

## **Access EspoCRM**

After starting the container, you can access the EspoCRM application in your web browser at:
```
http://localhost:8080
```

Follow the setup wizard to configure your database and start using EspoCRM.

---

## **Video Walkthrough**

[EspoCRM_Docker_Project.mp4](./EspoCRM_Docker_Project.mp4)

---

