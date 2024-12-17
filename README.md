 Hola, Soy **Alejandro de la Rosa David**🧑🏽‍💻... Esta readme.md será muy sencillo debido a que es la evidencia y representación del ejercicio:

**"4. Defina la estructura de una aplicación cliente servidor en tecnología Microsoft .NET y justifique la selección. La aplicación registrará los datos básicos de una persona en la plataforma por medio de un formulario el cual debe permitir adjuntar archivos.
Indique cómo estructuraría el aplicativo del lado del servidor (API)"**

Como podrán ver en nuestro código y representación, esta sería la estructura de nuestras capas, como VCS no tiene prioridad de orden de carpetas sin uso de extensiones, decidí graficar también el "orden correcto" por este medio:

proyecto.API/
├── Controllers/
│   └── PersonController.cs        **# Controlador para manejar solicitudes HTTP relacionadas con la persona.**
├── Models/
│   └── Person.cs                 **# Modelo que define los datos de una persona.**
│   └── FileAttachment.cs         **# Modelo para representar archivos adjuntos.**
├── Services/
│   └── PersonService.cs          **# Lógica de negocio para procesar la persona y archivos adjuntos.**
├── Repositories/
│   └── PersonRepository.cs       **# Repositorio para realizar operaciones CRUD sobre la persona.**
├── Data/
│   └── ApplicationDbContext.cs  **# Contexto de la base de datos, configurando las entidades.**
├── appsettings.json              **# Configuraciones de la aplicación (cadenas de conexión, etc.).**

Muchas gracias por la atención prestada 
