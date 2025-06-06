PMDM-RETROFIT
Este proyecto es una aplicación desarrollada en Kotlin para Android, como parte de las actividades del módulo de Programación Multimedia y Dispositivos Móviles (PMDM). La aplicación está diseñada para practicar la integración de servicios web utilizando la biblioteca Retrofit, permitiendo realizar solicitudes HTTP y manejar respuestas de APIs RESTful.

🧠 Descripción
La aplicación permite:

Realizar solicitudes HTTP GET, POST, PUT y DELETE a servicios web.

Parsear respuestas JSON y mapearlas a objetos de datos en Kotlin.

Mostrar la información obtenida de la API en la interfaz de usuario.

Esto proporciona una comprensión práctica de cómo consumir APIs RESTful en aplicaciones Android utilizando Retrofit.

📁 Estructura del Proyecto
css
Copiar
Editar
PMDM-RETROFIT/
├── .idea/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── ...
│   │   │   └── res/
│   │   │       └── ...
│   │   └── ...
│   └── build.gradle.kts
├── gradle/
├── .gitattributes
├── .gitignore
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
└── settings.gradle.kts
.idea/: Configuraciones del proyecto para el IDE Android Studio.

app/src/main/java/: Contiene el código fuente de la aplicación, incluyendo actividades, fragmentos y clases de datos.

app/src/main/res/: Contiene los recursos de la aplicación, como layouts, strings y estilos.

build.gradle.kts, settings.gradle.kts: Archivos de configuración del proyecto utilizando Kotlin DSL para Gradle.

🚀 Instrucciones de Ejecución
Clonar el repositorio:

bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PMDM-RETROFIT.git
Importar el proyecto en Android Studio:

Abre Android Studio.

Selecciona "Open an existing project" y navega hasta la carpeta del proyecto clonado.

Espera a que Gradle sincronice y configure el proyecto.

Ejecutar la aplicación:

Conecta un dispositivo Android o inicia un emulador.

Haz clic en el botón "Run" (▶️) en Android Studio para compilar y ejecutar la aplicación.

🛠️ Tecnologías Utilizadas
Kotlin: Lenguaje de programación principal.

Android SDK: Framework para el desarrollo de aplicaciones móviles en Android.

Retrofit: Biblioteca para realizar solicitudes HTTP y manejar APIs RESTful.

Gson: Biblioteca para la conversión entre JSON y objetos de datos.

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

👨‍💻 Autor
Iván Núñez Rodríguez - GitHub
