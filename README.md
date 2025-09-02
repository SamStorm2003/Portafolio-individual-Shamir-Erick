# Portafolio-individual-Shamir-Erick-Condori-Troche

## 1. Portfolio Digital Personal

## Resumen Ejecutivo  
El proyecto TuEx Market es una plataforma de marketplace orientada a la comunidad universitaria, cuyo objetivo principal es conectar a estudiantes emprendedores con clientes. La iniciativa busca fomentar el espíritu emprendedor dentro de las universidades, ofreciendo un espacio donde los estudiantes puedan publicar, promocionar y vender sus productos de manera sencilla, segura y confiable. El proyecto no solo pretende ser un marketplace, sino también un ecosistema que impulse la economía estudiantil y el emprendimiento juvenil.

Durante el desarrollo de la aplicación se implementaron funcionalidades clave como la gestión de usuarios mediante registro y autenticación, el proceso de pago simulado con la API de Stripe con carrito de compras y actualización de inventario, así como la integración con redes sociales para compartir productos en plataformas como Facebook e Instagram. Se utilizaron tecnologías modernas como Laravel 12, MySQL, TailwindCSS y Livewire, además de pruebas unitarias con PHPUnit para asegurar calidad y estabilidad en el sistema.

Mi contribución personal dentro del proyecto fue como desarrollador frontend-backend y apoyo en la organización de la metodologia ágil del equipo. Implementé funcionalidades completas en frontend y backend, especialmente en las historias de usuario US-008 (Proceso de Pago Simulado) y US-013 (Integración con Redes Sociales). Además, participé activamente en las ceremonias Scrum, colaboré en la documentación de los sprints (60%), realicé commits clave en GitHub y apoyé en la planificación de los sprints. Mi aporte fue integral, combinando habilidades técnicas con la colaboración organizacional, lo que me permitió crecer tanto en el aspecto profesional como en el trabajo en equipo. 

---

## Contribuciones Técnicas  

### Tecnologías Utilizadas  
- **Frontend:** Livewire, TailwindCSS  
- **Backend:** Laravel 12
- **Base de datos:** MySQL  
- **Herramientas:** GitHub, Stripe API

### Contribuciones Clave del Código  
## Commits Destacados

A continuación se presentan los *commits* que evidencian mi participación en el desarrollo del proyecto, incluyendo implementación de funcionalidades clave y mejoras en la integración con servicios externos:

1. [Implementación inicial del Checkout con Stripe](https://github.com/Jhoel777ar/marketplace-lpz/commit/83b217bdc4eb89fbbbdfcd8ca57bdad9a411d87d)  
2. [Integración del Checkout funcionando con la base de datos](https://github.com/Jhoel777ar/marketplace-lpz/commit/cb46b115ad15edbc7d3a69f10bf310e04b954186)  
3. [Actualización de inventario luego de la venta con Stripe](https://github.com/Jhoel777ar/marketplace-lpz/commit/3ddd64adf5ca5ae4ed3fa38b0485c0b033421c9c)  
4. [Solicitud de dirección del usuario antes del pago con Stripe](https://github.com/Jhoel777ar/marketplace-lpz/commit/51c16b894f1294b622a5adf18c3c1e1ab247066b)  
5. [Integración con redes sociales funcional, asegurando privacidad de datos autorizados](https://github.com/Jhoel777ar/marketplace-lpz/commit/39589ab7b2cb1f2598523650b3c71d2020e57ed2#diff-94b897eb35168c09076b979d6cf9fa2c1bbc711829e0de33f1feded85115de2c)



## Desafíos Técnicos Resueltos  

1. **Problema:** Integración inicial con Stripe no funcionaba correctamente.  
   **Solución:** Revisé la configuración de las claves de API, modos de prueba y endpoints; ajusté la inicialización del SDK de Stripe en Laravel.  
   **Aprendizaje:** Comprendí la importancia de verificar credenciales y configuraciones antes de implementar pasarelas de pago externas, y aprendí a manejar errores de integración de manera sistemática.  

2. **Problema:** Los datos de venta no se guardaban correctamente en la base de datos.  
   **Solución:** Depuré el flujo de almacenamiento, ajustando los modelos Eloquent y validaciones de las relaciones entre tablas (ventas, detalles de venta).  
   **Aprendizaje:** Mejoré mi manejo de Eloquent ORM y validaciones de integridad de datos en Laravel, asegurando consistencia en el registro de transacciones.  

3. **Problema:** La integración con redes sociales (Instagram, Facebook, etc) no funcionaba correctamente al inicio.  
   **Solución:** Reconfiguré el flujo OAuth y revisé permisos de la API, ajustando la importación y exportación de datos para que se compartieran únicamente los autorizados por el usuario.  
   **Aprendizaje:** Aprendí a manejar correctamente OAuth y permisos de terceros, así como la validación de datos sensibles al importar y compartir información de redes sociales.
---
## Aplicación de la Metodología Ágil

**Rol ejercido:** Desarrollador Frontend-Backend, apoyo Scrum Master  

**Participación en ceremonias Scrum:**  
- Daily meetings: participación activa reportando avances y bloqueos.  
- Sprint Planning: Planificar y estimar historias de usuario.  
- Retrospectivas: aporté sugerencias para mejorar el flujo de trabajo y la organización del sprint.  

**Métrica personal de contribución:**  
**Métrica personal de contribución:**  
Mi contribución principal consistió en implementar de manera completa las historias de usuario **US-008 (Proceso de Pago Simulado)** y **US-013 (Integración con Redes Sociales)**, asegurando que todas las funcionalidades cumplieran con sus criterios de aceptación, incluyendo ingreso de dirección, métodos de pago, confirmación de pedido, actualización de inventario y autenticación OAuth para redes sociales, además de la importación y compartición de datos de manera segura, demostrando así un aporte integral tanto en frontend como en backend.

---

## Desarrollo de Habilidades Blandas  
- **Comunicación:** Mejoré en la explicación de avances durante dailys.  
- **Liderazgo:** Coordiné con el equipo para la integración de módulos críticos.  
- **Resolución de problemas:** Propuse soluciones ante bloqueos técnicos.  
- **Adaptabilidad:** Me ajusté a cambios de requerimientos en medio de sprint.  

---

## Artefactos y Evidencia  

- ![Api de Stripe funcionando antes de pagar](https://drive.google.com/uc?id=1mWWsYBYSkUZbxQ9amIYtVYVrMK1T7M_A)
- ![Api de Stripe funcionando antes de pagar 2da parte](https://drive.google.com/uc?id=1Pa3OWKWijLrd0tSA22otweEpsuuKN2tw)
- ![Checkout y formulario de envio antes de pagar 2](https://drive.google.com/uc?id=1GW5Omb3G1idUoghOGuF3rFjNgqDAm9Bg)
- ![Checkout y formulario de envio antes de pagar](https://drive.google.com/uc?id=1MiUv4rj0wA3gatpeBqYq92hvUxSzCkjg)
- ![Copia de enlace del producto a Instagram](https://drive.google.com/uc?id=1DPiWA5GqIix4ePrzYOHZPJ-D8GmfMlUh)
- ![Integración de redes sociales](https://drive.google.com/uc?id=1cfWa99dnzKKHXLfxD3Lo_a1rRBH1XOCT)
- ![Número único para cada venta de Stripe](https://drive.google.com/uc?id=14I2H8HxEXlVbvk9Mpwcxq3-e2d6AqR8F)
- ![Prueba dentro de Stripe](https://drive.google.com/uc?id=1DcrPDYiy1HeFH9ON8fGXsIkDaoT7BnoC)
- ![Prueba dentro de Telegram](https://drive.google.com/uc?id=10yM8ZwLRJzxaVKGdVDA829bMn0QHgQov)
- ![Prueba dentro de WhatsApp](https://drive.google.com/uc?id=1fFVIN21ENOdzV4YCZzKVyqpj6tZgzHpc)

- **Documentacion creada**
- Mi trabajo quedó reflejado en los *commits* documentados en el repositorio de GitHub, los cuales respaldan de manera verificable mi aporte en el desarrollo del proyecto. Asimismo, la documentación complementaria de mis avances y contribuciones se encuentra registrada en los entregables correspondientes a los **Sprints 1, 2 y 3**, lo que garantiza la trazabilidad de mi participación dentro del proceso ágil.
- **Reconocimientos recibidos**
- Reconocimiento del equipo por resolver integración con API externa Stripe y la mejora dentro de la integracion de redes sociales. 

---

## Reflexión y Crecimiento Futuro  
- **Autoreflexion sobre aprendizajes**
  Durante el desarrollo de este proyecto logré fortalecer significativamente mis conocimientos en **Laravel**, **Livewire** y en el **consumo de APIs**, lo cual me permitió comprender de manera más integral la interacción entre tecnologías de frontend y backend. Esta experiencia fue clave para consolidar mis habilidades técnicas y aplicarlas en la construcción de soluciones más eficientes y completas.
- **Plan de crecimiento personal:**
  Enfocarme en pruebas automatizadas y arquitectura limpia dentro del entorno Laravel.
- **Impacto en visión profesional:**
  Este proyecto reafirmó mi interés en ser desarrollador fullstack especializado en integración de sistemas.

# 2. Declaración de Compromiso de Aprendizaje

## Habilidades Técnicas (próximos 6 meses)  
1. Dominar pruebas automatizadas con PHPUnit y Jest.  
2. Implementar CI/CD con GitHub Actions.  
3. Profundizar en arquitectura de microservicios.  

## Prácticas Ágiles  
1. Documentar de forma más clara cada historia de usuario.  
2. Aplicar retrospectivas personales tras cada sprint.  
3. Facilitar discusiones técnicas en dailys y plannings.  

## Colaboración  
1. Mejorar mi feedback constructivo hacia compañeros.  
2. Asumir un rol más activo en resolución de conflictos.  
3. Promover espacios de brainstorming colaborativos.  

## Métricas de Éxito  
- 3 proyectos con pruebas automatizadas implementadas.  
- Participar en 5 retrospectivas con aportes concretos.  
- 2 presentaciones técnicas al equipo.  

## Socio de Responsabilidad  
- **Nombre del socio:** Luis Fernando Villca Mamani 

## Fecha de Revisión  
- **Dentro de 3 meses:** 15 de diciembre de 2025 


