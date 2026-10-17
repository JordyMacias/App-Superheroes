# Superheroes
 
App Android que muestra una lista desplazable de superhéroes, construida con **Jetpack Compose** y **Material Design 3**. Es el resultado del ejercicio práctico [Build Superheroes app](https://developer.android.com/codelabs/basic-android-kotlin-compose-practice-superheroes) del curso Android Basics with Compose.
 
## Características
 
- Lista de héroes con `LazyColumn`
- Cada elemento muestra nombre, descripción e imagen dentro de una `Card`
- Barra superior centrada con `Scaffold` y `CenterAlignedTopAppBar`
- Tema claro y oscuro con paleta, formas y tipografía (Cabin) personalizadas
- Diseño edge-to-edge (barra de estado y navegación transparentes)
## Tecnologías
 
- Kotlin
- Jetpack Compose
- Material Design 3
- Android Studio
## Requisitos
 
- Android Studio (versión reciente)
- SDK mínimo: 24 (Android 7.0)
## Estructura del proyecto
 
```
app/src/main/
├── java/com/example/superheroes/
│   ├── MainActivity.kt          # Actividad, Scaffold y top app bar
│   ├── HeroesScreen.kt          # HeroListItem y HeroesList
│   ├── model/
│   │   ├── Hero.kt              # Data class del héroe
│   │   └── HeroesRepository.kt  # Datos de ejemplo
│   └── ui/theme/
│       ├── Color.kt
│       ├── Shape.kt
│       ├── Theme.kt
│       └── Type.kt
└── res/
    ├── drawable/                # Imágenes de los héroes
    ├── font/                    # Cabin Regular y Bold
    └── values/strings.xml       # Nombres y descripciones
```
 
## Cómo ejecutarlo
 
1. Clona el repositorio:
```bash
   git clone https://github.com/JordyMacias/App-Superheroes
```
2. Ábrelo en Android Studio.
3. Espera a que termine la sincronización de Gradle.
4. Ejecuta la app en un emulador o en un dispositivo físico con el botón **Run**.
## Capturas de pantalla
 
| Tema claro | Tema oscuro |
| :---: | :---: |
| <img width="720" height="1600" alt="WhatsApp Image 2026-10-17 at 10 09 51 AM" src="https://github.com/user-attachments/assets/57b5fcce-7b19-4d13-954c-242234d661fe" /> | <img width="720" height="1600" alt="WhatsApp Image 2026-10-17 at 9 46 32 AM" src="https://github.com/user-attachments/assets/db47e4ba-44e9-497c-a4ea-f7c0ae6e497c" /> |
 
## Créditos
 
- Ejercicio y recursos (imágenes, colores y datos de ejemplo): [Android Developers](https://developer.android.com/codelabs/basic-android-kotlin-compose-practice-superheroes)
- Fuente: [Cabin](https://fonts.google.com/specimen/Cabin) (Google Fonts)
