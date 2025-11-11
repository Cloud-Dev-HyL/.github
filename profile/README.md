# **Proyecto Luca: Innovación Ágil en Consultoría Contable y Tributaria**

## **"El código es nuestro oficio. La agilidad, nuestra mentalidad."**

Este repositorio documenta un proyecto de software concebido no sólo para resolver un problema de negocio, sino para hacerlo de una manera que honra los principios fundamentales de nuestro manifiesto. Es un proyecto de índole privado, desarrollado en estrecha colaboración con una firma de consultoría contable y tributaria, donde la calidad es ley.

## **El Desafío: Agilidad en un Mundo de Reglas**

La industria contable y tributaria se define por su rigidez: regulaciones inmutables, plazos inflexibles y una aversión cultural al riesgo. El desarrollo de software tradicional (en cascada) intenta reflejar esto, construyendo sistemas monolíticos que fallan, en muchos casos, ante el primer cambio de ley.

Nuestro desafío fue aplicar una metodología fluida y adaptativa en un dominio que, por naturaleza, no lo es.

## **Nuestra Brújula: El Manifiesto Ágil**

No adoptamos "Agile" como una etiqueta de moda. Volvemos a la fuente. Cada decisión de arquitectura, cada *sprint* y cada conversación con el cliente interno se enfocó desde los cuatro valores fundamentales.

### **1\. Individuos e Interacciones sobre Procesos y Herramientas**

En el sector de la consultoría, los "procesos" son todo. Nosotros elegimos priorizar la conversación.

* **En la práctica:** Celebramos sesiones de *pair programming* no solo entre desarrolladores, sino sesiones de *pair review* entre un desarrollador y un contador (nuestro *Product Owner*).

### **2\. Software Funcionando sobre Documentación Exhaustiva**

La documentación contable es densa. La documentación de requisitos tradicional intenta imitarla.

* **En la práctica:** En lugar de un documento de especificaciones de 300 páginas, entregamos un módulo funcional en el *Sprint 1*.

### **3\. Colaboración con el Cliente sobre Negociación Contractual**

Este es un proyecto privado; la confianza es nuestro activo más valioso.

* **En la práctica:** El cliente no fue un espectador, fue un miembro del equipo. Se integró a nuestro *trabajo* y retrospectivas. No existían "solicitudes de cambio" formales; existía una conversación continua sobre la priorización del *backlog* para maximizar el valor entregado.

### **4\. Respuesta ante el Cambio sobre Seguir un Plan**

En el mundo tributario, el "cambio" tiene nombre: "Cambios Normativos". Ocurre anualmente y sin previo aviso.

* **En la práctica:** Nuestra arquitectura se diseñó para el cambio. Aplicando principios como **SOLID**, los procesos no están "quemados" en el código. Son componentes intercambiables y modulares.

## **Principios que Guiaron Nuestro Código**

De los 12 principios ágiles, abrazamos con especial énfasis:

* **"Nuestra mayor prioridad es satisfacer al cliente mediante la entrega temprana y continua de software con valor."** Entregamos valor en *sprints* de tres semanas. El cliente vio progreso tangible y pudo ajustar sus operaciones de forma incremental.  
* **"Aceptamos que los requisitos cambien... Los procesos ágiles aprovechan el cambio para proporcionar ventaja competitiva al cliente."** Cada cambio regulatorio no fue un problema para el proyecto, fue una oportunidad para demostrar la resiliencia de nuestra arquitectura.  
* **"La atención continua a la excelencia técnica y al buen diseño mejora la agilidad."** La agilidad no es una excusa para el código desordenado; es su antítesis. Un código limpio, bien factorizado y cubierto por pruebas unitarias no es un lujo; es el mecanismo que *permite* la respuesta rápida al cambio.  
* **"La simplicidad \--el arte de maximizar la cantidad de trabajo no realizado-- es esencial."** No construimos un ERP. Construimos la solución exacta que el cliente necesitaba, evitando la sobre-ingeniería y enfocándonos en el *core business value*.

## **Stack Tecnológico (Conceptual)**

La metodología es independiente de las herramientas, pero las herramientas correctas la potencian.

* **🖥️  Backend:** \[ej. GCP Serverless, Node.js, Spring Boot\] \- Elegido por su rendimiento y ecosistema maduro.  
* **🌐  Frontend:** \[ej. React, Angular, Vue\] \- Para una UI reactiva que permite a los contadores trabajar sin recargar la página.  
* **📦  Base de Datos:** \[ej. Firestore, SQL Server\] \- Priorizando la integridad transaccional (ACID).  
* **🔄  CI/CD:** \[ej. GCP, Jenkins, GitLab CI\] \- La automatización de *builds* y *deploys* es la columna vertebral de la "entrega continua".


