# Herramientas y Tecnologías Utilizadas

El desarrollo de este proyecto se basará en una combinación de tecnologías modernas de **frontend** y **backend**, junto con una arquitectura de **cliente-servidor**. Las herramientas seleccionadas buscan facilitar el desarrollo, garantizar la escalabilidad del sistema y optimizar el flujo de trabajo colaborativo. A continuación, se detallan las herramientas y tecnologías elegidas para cada componente del sistema:

1. **Lenguajes de Programación y Tecnologías de Desarrollo**

   - **Frontend:**  
     Se empleará **JavaScript**, particularmente mediante la biblioteca **React**, complementado con **HTML** y **CSS**. JavaScript, junto con React, se selecciona por su eficiencia en la creación de interfaces de usuario interactivas y reactivas, permitiendo una rápida respuesta del lado del cliente. React es especialmente beneficioso por su capacidad de dividir la interfaz en componentes reutilizables, lo cual facilita el mantenimiento y la escalabilidad del frontend. HTML y CSS aportan estructura y estilo, respectivamente, asegurando una experiencia de usuario coherente y atractiva.

   - **Backend:**  
     Para el servidor, se utilizará **Python** junto con el framework **Django**. La elección de Django responde a su enfoque en la rapidez de desarrollo y en la seguridad, además de su patrón de arquitectura **MVC (Modelo-Vista-Controlador)** que organiza el flujo de datos de forma estructurada. Django proporciona también una integración nativa con bases de datos relacionales, lo cual facilita la administración de los datos y contribuye a la robustez del sistema.

2. **Arquitectura del Proyecto**

   Este proyecto seguirá la arquitectura **cliente-servidor**, en la cual el frontend desarrollado en React funcionará como el cliente, enviando solicitudes HTTP al backend en Django, que actuará como el servidor. La arquitectura cliente-servidor permite una clara separación de responsabilidades, simplificando el desarrollo y manteniendo la escalabilidad y seguridad. Esta disposición asegura que el cliente pueda actualizar la interfaz sin afectar la lógica central del servidor y, a su vez, permite que éste gestione los datos de manera segura y eficiente.

3. **Entornos de Desarrollo (IDE)**

   Se utilizarán los entornos **VS Code** y **Cursor** como IDE principales para el desarrollo del proyecto. VS Code se ha elegido por su flexibilidad y por la amplia gama de extensiones disponibles que facilitan la integración con herramientas de control de versiones, la depuración de código y el soporte para múltiples lenguajes de programación (incluyendo JavaScript, Python y SQL). Además, se destaca por su alta compatibilidad con lectores de pantalla, en particular con **NVDA**, el cual será utilizado por uno de los miembros del equipo con discapacidad visual. Esta funcionalidad adicional permite que todos los integrantes participen plenamente en el desarrollo. Por su parte, Cursor será utilizado como complemento para el desarrollo de prototipos y la escritura ágil de código, potenciando la eficiencia en el flujo de trabajo.

4. **Frameworks y Librerías**

   - **React:**  
     Seleccionado para el desarrollo de la interfaz de usuario, React permite la creación de componentes reutilizables y facilita la actualización eficiente del DOM virtual, lo cual optimiza el rendimiento y la experiencia del usuario en la aplicación.
     
   - **Django:**  
     Este framework para el desarrollo web en Python ofrece un sistema completo para la construcción de aplicaciones seguras y escalables, además de proporcionar soporte directo para la gestión de usuarios, autenticación y el manejo de formularios, entre otras funcionalidades avanzadas.

5. **Sistema de Control de Versiones**

   Se empleará **Git** como sistema de control de versiones, con el repositorio alojado en **GitHub**. Git permite un registro detallado de cada modificación en el código, garantizando la trazabilidad de los cambios y facilitando la colaboración entre los integrantes del equipo. GitHub proporciona, además, un espacio centralizado para la documentación del proyecto y el manejo de issues o problemas, optimizando la gestión del proyecto y el control de calidad.

6. **Base de Datos**

   El sistema utilizará **MySQL** como motor de base de datos. MySQL se selecciona por su alta eficiencia y rendimiento en la gestión de datos relacionales, además de su flexibilidad y capacidad de integrarse sin problemas con Django. La estructura de datos estará diseñada para optimizar las consultas y garantizar la consistencia de los datos, asegurando la escalabilidad para manejar volúmenes elevados y permitiendo la implementación de transacciones seguras.

7. **Herramientas de Documentación**

   La documentación del proyecto se desarrollará en **Markdown**, un lenguaje de marcado ligero que facilita la creación de documentos estructurados y permite su visualización en plataformas colaborativas como GitHub. Markdown fue elegido por su simplicidad y compatibilidad con múltiples herramientas de edición y revisión, lo que garantiza que la documentación esté siempre actualizada y sea fácilmente accesible por todos los integrantes del equipo.

8. **WampServer**

   Se utilizará para crear un entorno de servidor local durante el desarrollo del proyecto, que permita ejecutar y probar tanto el backend como la base de datos. WampServer facilitará la creación de un servidor local para el desarrollo de la aplicación web, simulando un entorno de servidor real. Esto permite probar la interacción de las diferentes partes del sistema en un entorno controlado antes de su implementación en producción, además de configurar y gestionar bases de datos MySQL de manera local, acelerando el desarrollo y mejorando la eficiencia en la fase de pruebas.
