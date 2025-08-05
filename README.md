# 🧩 Microservice Java Francisco

Este repositorio contiene una arquitectura de microservicios desarrollada en **Java con Spring Boot**, diseñada para ser escalable, modular y fácil de mantener.

---

## 🚀 Tecnologías utilizadas

- Java 17+
- Spring Boot
- Spring Cloud (Eureka, Config Server, Zuul)
- Maven
- JPA / Hibernate
- MySQL / H2
- Docker (opcional)
- Swagger (documentación de APIs)

---

## 🧱 Estructura del proyecto

```bash
microservice-java-francisco/
├── microservicios-usuarios
├── microservicios-cursos
├── microservicio-examenes
├── microservicio-respuesta
├── microservicios-eureka
├── microservicios-zuul
├── commons-alumnos
├── commons-examenes
├── commons-microservicios
└── README.md
Cada carpeta representa un microservicio o módulo compartido. Los microservicios se comunican entre sí mediante REST y están registrados en el servidor Eureka.

⚙️ Cómo ejecutar el proyecto
Clona el repositorio:

bash
git clone https://github.com/francisco-atenas/microservice-java-francisco.git
Importa los proyectos en tu IDE (IntelliJ, Eclipse, VS Code).

Asegúrate de tener MySQL o H2 configurado.

Ejecuta primero:

microservicios-eureka

microservicios-config-server (si lo tienes)

Luego los demás microservicios.

Accede a las APIs vía Zuul Gateway:

http://localhost:8080/{nombre-servicio}/api/...
📚 Documentación
Las APIs están documentadas con Swagger en cada microservicio.

Puedes acceder a ellas en:

http://localhost:{puerto}/swagger-ui.html
📦 Contribuciones
¡Las contribuciones son bienvenidas! Puedes abrir issues o enviar pull requests para mejorar el proyecto.

🧑‍💻 Autor
Francisco Atenas Desarrollador backend apasionado por arquitecturas distribuidas y sistemas escalables.

¿Quieres que lo traduzca al inglés o que incluya ejemplos de endpoints? También puedo ayudarte a generar documentación Swagger si lo necesitas 😄.
