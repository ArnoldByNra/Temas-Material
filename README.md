# Woof — Temas de Material con Jetpack Compose

📝 Descripción del Proyecto
Este proyecto es una implementación práctica de la personalización de temas en Android utilizando Jetpack Compose y Material Design 3. El objetivo principal es demostrar cómo crear una experiencia visual cohesiva y adaptable mediante la configuración de esquemas de colores, tipografías personalizadas y formas.

La aplicación presenta una interfaz minimalista para mostrar una lista de perros, aplicando los principios de diseño moderno de Google para lograr una UI atractiva y accesible.

🛠️ Conceptos de Diseño Implementados
1. Material Design 3 (M3)
Implementación de los estándares más recientes de Material Design, utilizando componentes como `Scaffold` y `CenterAlignedTopAppBar` para estructurar la pantalla principal.

2. Esquemas de Color Dinámicos
Configuración de paletas de colores compatibles con modo claro y oscuro, asegurando que la aplicación sea legible y visualmente agradable en cualquier configuración del sistema.

3. Tipografía Personalizada
Integración de fuentes externas (Abril Fatface y Montserrat) para diferenciar la jerarquía visual, aplicando estilos específicos para títulos y cuerpo de texto a través de `Type.kt`.

4. Componentes Reutilizables
Creación de elementos de interfaz modulares, como `DogItem`, que encapsulan la lógica de presentación de datos (foto, nombre, edad y pasatiempo) para mantener un código limpio y mantenible.

🚀 Componentes Principales
- WellnessScreen: Punto de entrada que orquestra la disposición de los elementos en la pantalla.
- DogItem: Componente especializado en renderizar la información de cada perro con un diseño consistente.
- WoofTopAppBar: Barra superior alineada al centro que define la identidad visual de la app.
- Theme: Configuración centralizada de colores, formas y tipos que se aplica a toda la aplicación.

💻 Stack Tecnológico
- Lenguaje: Kotlin
- UI: Jetpack Compose (Material 3)
- Fuentes: Abril Fatface, Montserrat
- Herramientas: Android Studio, Gradle

💡 Conclusiones
- Identidad Visual: Se logró crear una interfaz con personalidad propia mediante el uso estratégico de tipografías y colores, alejándose del aspecto genérico de las apps estándar.
- Adaptabilidad: La implementación de temas permitió que la aplicación responda correctamente a los cambios de configuración del sistema (modo oscuro/claro).
- Eficiencia de Compose: El uso de Compose facilitó la creación de una UI declarativa, reduciendo drásticamente la cantidad de código necesaria comparado con el sistema de vistas XML tradicional.
- Estructura M3: La adopción de Material 3 permitió implementar componentes modernos de forma nativa, optimizando la experiencia de usuario y la navegación.
