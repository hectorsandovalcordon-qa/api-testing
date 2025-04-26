# API Automation Project - DemoQA

Este proyecto tiene como objetivo automatizar pruebas de API utilizando diferentes herramientas de testing de software de calidad (QA).  
La API pública utilizada es [DemoQA Swagger API](https://demoqa.com/swagger/), ideal para probar operaciones como autenticación, creación, consulta y eliminación de usuarios.

## 🔧 Tecnologías utilizadas

- **Postman**: Creación y ejecución de colecciones de pruebas.
- **Katalon Studio**: Automatización avanzada con o sin código.
- **Rest Assured (Java + Maven)**: Pruebas de API programáticas.
- **SoapUI**: Simulación de pruebas para servicios SOAP/REST.
- **Apache JMeter**: Simulación de carga y rendimiento sobre endpoints.

## 📁 Estructura del proyecto
```
api-automation-project/ ├── README.md ├── .gitignore ├── postman/ │ └── DemoQA_TestCollection.json ├── katalon/ │ └── scripts/ ├── restassured/ │ ├── src/test/java/ │ │ └── api/ │ │ └── DemoQATests.java │ └── pom.xml ├── soapui/ │ └── DemoQA-SoapUI-Project.xml ├── jmeter/ │ └── DemoQA_JMeterTest.jmx └── docs/ └── HowToRun.md
```

## ✅ Casos de prueba principales

| # | Caso de prueba | Descripción |
|:--|:---------------|:------------|
| 1 | Login exitoso | Validar autenticación correcta y obtención de token. |
| 2 | Crear usuario | Crear un nuevo usuario y validar los datos de respuesta. |
| 3 | Obtener usuario | Consultar datos de un usuario creado. |
| 4 | Eliminar usuario | Borrar un usuario existente y validar la eliminación. |
| 5 | Manejo de errores | Crear usuarios con datos inválidos y validar errores. |
| 6 | Carga masiva | Simular múltiples registros concurrentes (pruebas de carga). |

## 🚀 Mejoras futuras

- Integración con **GitHub Actions** para ejecución automática de pruebas.
- Generación de reportes de resultados con **Allure Reports**.
- Cobertura de pruebas para escenarios edge y validaciones de seguridad.
- Adición de pruebas de performance con simulaciones de usuarios concurrentes.
