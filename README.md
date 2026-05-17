Soraya Perfumes y Cosméticos (Est. 1991)
Este repositorio contiene la arquitectura web estática completa para la tienda online "Soraya Perfumes y Cosméticos".
El sistema está diseñado para funcionar de manera 100% autogestionable y sin base de datos en servidor backend, almacenando todos los artículos, imágenes optimizadas y configuraciones públicas dentro del localStorage del navegador y permitiendo la descarga de la web compilada lista para ser servida a través de GitHub Pages.
📂 Archivos del Proyecto
Nombre del Archivo
Tipo de Acceso
Propósito
index.html
Público (Clientes)
Tienda online de lujo. SPA fluida de una sola página para máxima velocidad. Integra el carrito, catálogo reactivo, información de la marca y la generación automática de pedidos listos para procesar por WhatsApp.
Gestor.html
Privado (Administrador)
Panel administrativo local seguro. Permite añadir nuevos artículos, autocomprimir fotografías mediante Canvas, editar productos con vistas de bottom-sheet y exportar el nuevo código fuente para refrescar la tienda en segundos.
README.md
Interno
Este archivo de documentación técnica con instrucciones de despliegue y flujo de trabajo en producción.

🔑 Credenciales por Defecto del Administrador
Para acceder al Panel del Gestor (Gestor.html), introduce los siguientes datos:
• Usuario / Email: admin@soraya.es
• Contraseña: Soraya1991
🚀 Guía de Despliegue en GitHub Pages (Paso a Paso)
Sigue estos sencillos pasos para tener tu tienda premium online funcionando en internet de manera gratuita:
1.	Crea una Cuenta de GitHub si todavía no tienes una (es totalmente gratis).
2.	Crea un Nuevo Repositorio:
• Nómbralo como desees (ej: soraya-perfumes).
• Asegúrate de marcarlo como Público.
3.	Sube los archivos de este proyecto:
• Sube index.html, Gestor.html y este README.md directamente en la raíz (carpeta principal) de tu repositorio.
4.	Activa GitHub Pages:
• Entra en la pestaña Settings (Configuración) en la parte superior derecha de tu repositorio.
• En el menú lateral izquierdo, haz clic en Pages.
• En la sección Build and deployment, bajo Branch, cambia "None" por la rama principal (usualmente main o master) y la carpeta a / (root).
• Pulsa en Save.
5.	¡Tu web está lista! En pocos segundos GitHub te proveerá de un enlace público del tipo:
https://tu-usuario.github.io/tu-repositorio/
🔄 Flujo de Trabajo Diario (Cómo Actualizar la Tienda)
Cuando desees añadir, editar precios o cambiar productos de tu catálogo, sigue este procedimiento para actualizar los productos de tus clientes:
Explicación detallada de la gestión:
1.	Abre Gestor.html en tu navegador desde tu ordenador o servidor local.
2.	Inicia sesión con tu contraseña.
3.	Añade o edita tus productos. El sistema reducirá automáticamente el peso de tus fotos convirtiéndolas a JPEG de excelente resolución a un ancho máximo de 600px, asegurando que carguen instantáneamente en el móvil de tus compradores.
4.	Haz clic en la pestaña 📥 Exportar del menú del gestor.
5.	Pulsa el botón Generar index.html Actualizado. Se descargará un archivo index.html que contiene todas tus imágenes y productos embebidos.
6.	Entra en GitHub, edita o sube el archivo nuevo arrastrándolo para sobreescribir el index.html antiguo.
7.	¡Listo! Tus clientes verán el catálogo actualizado inmediatamente.
💳 Métodos de Pago Habilitados
Por motivos de agilidad administrativa y para evitar el cobro de comisiones de intermediarios, la tienda está configurada estrictamente para procesar compras por:
• 📱 Bizum Directo (Configurable con tu número móvil en la sección del Gestor).
• 🏦 Transferencia Bancaria (Configurable con tu IBAN y titular en el Gestor).
Al rellenar tu carrito y pulsar "Solicitar Pedido por WhatsApp", la tienda redactará una plantilla de pedido con formato premium y enviará al comprador directo a tu número de WhatsApp para finiquitar la compra de forma íntima y segura.
