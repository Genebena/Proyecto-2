# Proyecto-2
Este repositorio contiene el desarrollo y despliegue de la plataforma web interactiva para la Copa Piecitos Bike, un evento deportivo presencial de ciclismo infantil llevado a cabo en Plaza Viva Guayarte, Guayaquil. El sitio web está diseñado para actuar como un canal digital directo para centralizar las inscripciones, detallar el cronograma y estructurar de forma clara las categorías y costos de taquilla.

# Integrantes

• Genesis Benavides
• Roy Garcia

 Institución

• Entidad: Escuela Superior Politécnica del Litoral (ESPOL)
• Facultad: Facultad de Ingeniería en Electricidad y Computación
• Materia: Desarrollo de aplicaciones web y móviles [SOFG1006]
• Fecha: 16 de octubre de 2026

# Análisis del Proyecto

Se seleccionó el evento de ciclismo infantil "Copa Piecitos Bike" debido a su enfoque comunitario y familiar. El análisis del afiche promocional permitió identificar retos operativos importantes: la necesidad de segmentar estrictamente las disciplinas por edades para garantizar la seguridad de los menores, estructurar de forma clara los costos de taquilla y centralizar la captación de inscripciones.

#  Planificación (Arquitectura de Información)

La plataforma está organizada en las siguientes secciones lógicas:
1. Inicio / Hero: Presenta el título oficial del evento, el mensaje motivacional ("El inicio de una vida deportiva") y la ubicación destacada.
2. Sobre el Evento: Reseña del evento como espacio seguro enfocado en la sana competencia y la recreación al aire libre.
3. Categorías y Disciplinas: Detalles de los rangos oficiales de competencia:
	• Walk Bike: Para niños de 3, 4 y 5 años (bicicletas de balance sin pedales).
	• RIN 20: Para niños de 6, 7 y 8 años (bicicletas de cadena estándar).
4. Cronograma y Horarios: Información de la jornada deportiva (Fecha: 10 de Octubre de 14H00 a 17H00).
5. Costos y Taquilla: Valores de participación ($15.00 para competidores y $3.00 para la entrada de adultos/espectadores).
6. Inscripciones y Contacto: Enlaces a formularios web de registro y canales de atención de soporte (WhatsApp: 0982902627).

# Diseño y Justificación Técnica

Se utilizó la plantilla Phantom de HTML5 UP debido a las siguientes ventajas arquitectónicas:
• Alineación con la información: Su diseño central compuesto por tarjetas (tiles) funciona de manera ideal como una vitrina para mostrar dinámicamente las diferentes subcategorías por edad.
• Ergonomía móvil: Cuenta con una navegación limpia (menú hamburguesa) que optimiza la carga y reduce la fricción en teléfonos móviles, el principal dispositivo de consulta de los representantes.
• Mantenibilidad: Su modularidad facilita el renderizado y la escalabilidad del código.

#  Implementación

El desarrollo y la personalización técnica se realizaron con Visual Studio Code y GitHub Codespaces. Se reestructuró por completo el archivo principal index.html sustituyendo el contenido genérico por el sistema de cuadrícula interactiva <section class="tiles">.
La estructura del código divide de manera limpia las páginas y vistas de la competencia:
• Categoría Walk Bike: Bloques independientes para 3, 4 y 5 años (walk-bike-3-anos.html, etc.).
• Categoría Rin 20: Bloques independientes para 6, 7 y 8 años (rin-20-6-anos.html, etc.).

 #Despliegue
 

• Entorno Local: Durante el desarrollo se utilizó un servidor virtualizado con la extensión Live Server mapeando la aplicación al puerto 5500.
• Entorno de Producción: El código se encuentra desplegado de forma pública y segura en la nube para el acceso de evaluadores y usuarios finales.

# Bibliografía

• Escuela Superior Politécnica del Litoral [ESPOL]. (2026). Proyecto 02 - Fase 3: Desarrollo - Sprint 1: Lineamientos y Rúbrica de Evaluación. Sistema de Gestión de Aprendizaje Canvas.
• Multiverse / Phantom: A responsive HTML5/CSS3 template de HTML5 UP.
• Organización Copa Piecitos Bike. (2026). Afiche oficial, reglamentos de categorías infantiles y cronograma de competencia en Guayarte. Guayaquil, Ecuador.
