📋 Sistema de gestión de tareas - Tachalo 

Programa que permite al usuario administrar su asignación de tareas de manera fácil, automática y estar al tanto de ellas, utilizando el método CRUD.
Este sistema permite mostrar una estructura en sus bloques de código más organizado, por pestañas y el funcionamiento es óptimo.

🚀 Características

- ✅ Agregar tareas con ID automático
- ✅ Listar tareas con su fecha de creación
- ✅ Completar y eliminar tareas por ID
- ✅ Validación de las entradas del usuario
- ✅ Guarda las tareas registradas en formato JSON (Para comprobarlo debe ejecutar el proyecto en su terminal con el comando "dotnet run".)


🛠️ Tecnologías Lenguaje: C# Plataforma: .NET (cualquier versión que soporte consola). 

Compilador: dotnet, Visual Studio o csc.

📦 Requisitos previos .NET SDK (recomendado 6.0 o superior) Visual Studio Community O Visual Studio Code con extensión C#.

⁉️ ¿Cómo encontrar la carpeta donde se aloja el código? Al ingresar al proyecto encontrarás las partes que lo componen.

▶️ Cómo ejecutar

Opción 1: Con Visual Studio (más sencillo) Crea un nuevo proyecto de Aplicación de consola (.NET). Copia todo el código en el archivo Program.cs. Compila y ejecuta con F5 o el botón Iniciar (▶️). 

Opción 2: Con Visual Studio Code / terminal:

" git clone https://github.com/JuTevan25/Tachalo
cd Tachalo
dotnet run "

Clona el repositorio (o descarga el archivo .cs): git clone https://github.com/JuTevan25/Tachalo.git Autor: Juan Esteban Venegas Torres

Github: https://github.com/JuTevan25

## Estructura

- `Program.cs`: menú e interacción con el usuario
- `Tarea.cs`: modelo de una tarea
- `GestorTarea.cs`: lógica para agregar, listar, completar y eliminar

