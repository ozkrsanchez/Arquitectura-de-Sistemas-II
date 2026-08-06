# Examen Diagnóstico: Arquitectura de Sistemas II
**Objetivo:** Evaluar la suficiencia de conocimientos para el ingreso a Arquitectura de Sistemas II.

---

### SECCIÓN 1: Fundamentos y Pensamiento Arquitectónico

**1. Usted se encuentra diseñando un sistema de alta transaccionalidad. El cliente exige que el sistema nunca esté fuera de línea (Alta Disponibilidad), pero tiene un presupuesto limitado para infraestructura.<br><br>
¿Cuál de los siguientes conceptos describe mejor la situación del arquitecto?**<br>
   a) Requerimiento Funcional.<br>
   b) Trade-off (Compromiso).<br>
   c) Regla de compilación.<br>
   d) Deuda técnica.<br>
<br>
**2. Defina qué es un Atributo de Calidad (Requerimiento No Funcional) y mencione tres ejemplos que impacten directamente en la elección de una arquitectura de Microservicios.**<br>
   *Respuesta:* _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>

---

### SECCIÓN 2: Patrones y Estilos Arquitectónicos

**3. En el contexto de Clean Architecture (Arquitectura Limpia), ¿cuál es el propósito principal de la "Regla de Dependencia"?**<br>
   a) Que las capas externas dependan de los detalles de implementación de las capas internas.<br>
   b) Que las dependencias de código solo apunten hacia adentro, hacia los casos de uso y entidades.<br>
   c) Permitir que la base de datos controle la lógica de negocio.<br>
   d) Facilitar el acoplamiento entre la interfaz de usuario y los frameworks.<br>

**4. Compare la Arquitectura Monolítica con la de Microservicios. Identifique una ventaja y una desventaja crítica de cada una en términos de "Despliegue" y "Complejidad Operativa".**<br>
   *Respuesta:* _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>

**5. ¿Qué diferencia fundamental existe entre una arquitectura SOA (Service Oriented Architecture) y una arquitectura de Microservicios?**<br>
   a) SOA utiliza micro-bases de datos, mientras que Microservicios usa una base de datos central.<br>
   b) SOA suele enfocarse en la integración empresarial (ESB), mientras que Microservicios busca la autonomía y el despliegue independiente.<br>
   c) Los microservicios no pueden comunicarse por HTTP, SOA sí.<br>
   d) No hay diferencia; son términos intercambiables.<br>


---

### SECCIÓN 3: Comunicación e Integración

**6. Se requiere una comunicación en tiempo real entre servicios donde el emisor no necesita esperar una respuesta inmediata del receptor para continuar su proceso. ¿Qué estilo es el más adecuado?**<br>
   a) REST (Sincrónico).<br>
   b) gRPC (Sincrónico).<br>
   c) Event-Driven (Basado en Eventos/Asincrónico).<br>
   d) GraphQL (Query-based).<br>

**7. Explique brevemente en qué caso preferiría utilizar gRPC sobre REST para la comunicación interna entre microservicios.**<br>
   *Respuesta:* _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>

---

### SECCIÓN 4: Cloud, Contenedores y Modernización

**8. ¿Cuál es la función principal de un orquestador como Kubernetes en una arquitectura de contenedores?**<br>
   a) Compilar el código fuente en imágenes de Docker.<br>
   b) Gestionar el ciclo de vida, escalado, red y disponibilidad de los contenedores.<br>
   c) Reemplazar la necesidad de utilizar servicios de Cloud Computing.<br>
   d) Actuar como base de datos relacional para los microservicios.<br>

**9. En una arquitectura Serverless (FaaS), ¿quién es el responsable de gestionar el aprovisionamiento de los servidores y el escalado automático?**<br>
   a) El desarrollador mediante scripts de Terraform.<br>
   b) El equipo de infraestructura local.<br>
   c) El proveedor de la nube (Cloud Provider).<br>
   d) El orquestador de contenedores on-premise.<br>

---

### SECCIÓN 5: Documentación y Evaluación

**10. El Modelo C4 propone cuatro niveles de diagramación. ¿Cuáles son?**<br>
   a) Contexto, Contenedores, Componentes y Código.<br>
   b) Clases, Casos de Uso, Componentes y Cómputo.<br>
   c) Cliente, Canal, Capas y Código.<br>
   d) Concepto, Control, Conexión y Cierre.<br>

**11. ¿Qué es un ADR (Architecture Decision Record) y por qué es vital para la evolución de un sistema de software?**<br>
   *Respuesta:* _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>
   _________________________________________________________________________________________________________________________________________<br>   

---
