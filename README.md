# Sistema de Reconocimiento Facial

## ¿De qué trata este proyecto?

Este es mi proyecto de grado. Es una aplicación web que permite identificar personas a través de su rostro usando inteligencia artificial. El sistema captura la imagen del usuario desde el navegador, la envía a una API que analiza el rostro con FaceNet (una red neuronal de reconocimiento facial) y devuelve si la persona fue reconocida o no.

## Tecnologías utilizadas

- **Frontend:** React.js
- **Backend principal:** Laravel (PHP)
- **API de reconocimiento facial:** Flask (Python) + FaceNet
- **Base de datos:** MySQL

## Estructura del proyecto

```
├── front/        # Aplicación React (interfaz de usuario)
├── Back/         # Backend Laravel (lógica de negocio y API REST)
├── Flask/        # Microservicio Python para reconocimiento facial con FaceNet
└── Base de datos/ # Scripts SQL
```

## ¿Cómo funciona?

1. El usuario abre la app en el navegador y permite el acceso a la cámara.
2. Se captura una foto del rostro.
3. La imagen se envía al microservicio Flask.
4. FaceNet analiza el rostro y lo compara con los registros guardados.
5. El sistema devuelve si el rostro fue reconocido.

## Autor

**Sergio Alejandro Poma Chuquimia**  
Ingeniero de Sistemas Informáticos — UNIVALLE, La Paz, Bolivia  
[LinkedIn](https://www.linkedin.com/in/sergiopoma-chuquimia)
