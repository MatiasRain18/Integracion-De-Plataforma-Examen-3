🧪 Evaluación 3 - Integración de Plataformas

Caso Ferremas – Plan de pruebas e integración completa


---

✅ Proyecto

Este repositorio contiene el desarrollo del sistema para el caso Ferremas, correspondiente al Examen 3 de la asignatura Integración de Plataformas. Se implementaron todos los componentes funcionales con sus respectivas pruebas unitarias y de integración, cumpliendo con los requisitos definidos por el docente y las rúbricas oficiales de evaluación.


---

🛠️ Tecnologías utilizadas

Java 17

Spring Boot

MySQL (PhpMyAdmin)

Swagger UI (documentación y pruebas)

Postman (pruebas adicionales – opcional)



---

🧩 Componentes del sistema (8 en total)

1. producto-controller


2. usuario-controller


3. mensaje-contacto-controller


4. historial-precio-controller


5. webpay-controller


6. banco-central-controller


7. modelo de entidad y repositorios (Spring Data JPA)


8. persistencia en MySQL + validaciones




---

🔍 Pruebas realizadas

✅ Pruebas Unitarias

Se implementaron al menos 6 pruebas por componente.

Validan cada función individual como: crear usuario, producto, historial, simulaciones de dólar, entre otras.


✅ Pruebas de Integración

Se realizaron 6 pruebas de integración, incluyendo:

Producto + WebPay

Producto + Historial

Usuario + Mensaje

Banco Central (dólar + conversión)

Validación de producto duplicado

Flujo completo de WebPay (crear, confirmar, consultar)




---

❌ Prueba fallida registrada

Se dejó constancia de una única prueba fallida:

Error: Campo codigo_producto en la tabla producto aparecía como null.

Causa: El campo no se estaba mapeando correctamente en el modelo.

Solución propuesta: Validar que la entidad Producto reciba correctamente el codigoProducto y no dependa solo del autogenerado.



---

📄 Documentación entregada

Plan de Pruebas de Integración (Excel)

Registro de defectos (1 falla documentada)

Evidencias con Swagger UI

Evaluación de cumplimiento total de requerimientos

Control de versiones y responsables

Este archivo README.md como resumen del desarrollo


--------

👥 Integrantes del grupo

Matías Enrique Rain Cheuquecoy

Benjamín Celis Poblete

Matías Saez Carrasco
