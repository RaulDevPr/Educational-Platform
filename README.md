# Educative-Platform
YouTube-style educational platform with role-based access (student/teacher). Students submit videos (max 3/subject) pending approval. Teachers moderate content. Common functions: comments, watch video details. Development: C#/WinForms + Entity Framework for data persistence. Focus: functionality over UI.


---------------------------------------------------------------------------------
DESCRICIÓN COMPLETA/FULL DESCRIPTION

ESP:
Plataforma educativa de contenido multimedia al estilo "YouTube", en la cual, tu rango de acciones viene definido por tu rol de acceso: estudiante o profesor.

Los estudiantes pueden subir videos asociados a asignaturas (hasta 3 por contenido), los cuales quedan pendientes de aprobación, mientras que los profesores tienen permisos para revisar, aprobar o rechazar estos videos, proporcionando una justificación en caso de denegación. De esta forma conseguimos implementar un sistema de moderación que filtre la calidad del contenido y/o favorezca un ambiente saludable en la plataforma.
Además, permite comentar los videos y visualizar detalles como el autor, la fecha de subida y la descripción, creando un espacio interactivo para el aprendizaje.
Falta una UI pulida y detallada debido a que la finalidad del proyecto no és la experiencia visual del usuario, sino desarrollar las funcionalidades necesarias que subyacen a esta.

La aplicación está desarrollada en C# con Windows Forms, empleando Entity Framework para la persistencia de datos, y siguiendo una estructura de capas (GUI, servicios y entidades). Aunque la lógica básica de autenticación, registro y moderación está implementada, algunas funcionalidades como la búsqueda de videos o la reproducción de contenido aún no están completas.



ENG:
Educational multimedia platform in a "YouTube-style", where your range of actions is defined by your access role: student or teacher.

Students can upload videos associated with subjects (up to 3 per content), which remain pending approval, while teachers have permissions to review, approve or reject these videos, providing justification in case of rejection. This implements a moderation system that filters content quality and/or promotes a healthy platform environment.

Additionally, it allows commenting on videos and viewing details like the author, upload date and description, creating an interactive learning space. The UI lacks polish because the project's purpose isn't visual user experience but developing the underlying functionalities.

The application is developed in C# with Windows Forms, using Entity Framework for data persistence, and follows a layered structure (GUI, services and entities). While basic authentication, registration and moderation logic is implemented, some features like video search or content playback remain incomplete.
