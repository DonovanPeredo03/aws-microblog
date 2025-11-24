# AWS Microblog Project 

Proyecto académico que implementa un **microblog** utilizando servicios de AWS:
- **Amazon S3** para alojar el frontend estático.
- **AWS Lambda** para la lógica del backend.
- **Amazon API Gateway** para exponer los endpoints REST.
- **Amazon DynamoDB** como base de datos NoSQL.

---

## Estructura del repositorio
aws-microblog/ ├── frontend/         
# Archivos estáticos (HTML, JS, CSS) │  
├── index.html │   ├── app.js │   └── style.css ├── backend/         
# Código de Lambda y dependencias │  
├── lambda_function.js │   ├── package.json │   └── package-lock.json ├── infra/            
# Scripts de despliegue con AWS CLI │   
├── deploy.sh │   └── dynamodb_setup.sh ├── docs/            
# Documentación y diagramas 
└── README.md  




