☀️ SolParaTodos - Campo Solar Interactivo

SolParaTodos es una simulación interactiva desarrollada en Unity que permite visualizar y controlar un campo de paneles solares. El proyecto está enfocado en la optimización gráfica, el realismo visual y la interactividad para demostrar el funcionamiento de sistemas de captación de energía renovable.

✨ Funcionalidades Principales

El proyecto cuenta con una interfaz intuitiva (UI) que permite controlar el entorno y el comportamiento de las estructuras fotovoltaicas mediante 3 funciones clave:

🌅 Simulación Diurna (Botón de "Día"): Establece el entorno en condiciones de pleno día, ajustando la iluminación global (Directional Light y Skybox) al máximo nivel de captación y activando la proyección de sombras realistas.

🌃 Simulación Nocturna (Botón de "Noche"): Cambia el entorno a horario nocturno, ocultando el sol, reduciendo la iluminación general y activando luces secundarias (LEDs de estado en inversores y baterías) para ilustrar el uso de energía almacenada.

⚙️ Seguimiento Solar (Animación de Trackers): Activa el movimiento mecánico de las estructuras. Los paneles rotan sobre sus ejes simulando un sistema de seguimiento que busca maximizar la eficiencia energética a lo largo del día.

🛠️ Apartado Técnico y Gráfico

Este proyecto fue construido priorizando el rendimiento y el realismo, utilizando las siguientes técnicas:

📐 Modelado 3D Optimizado (Blender)

Todos los objetos de la escena (paneles solares, inversores de corriente, banco de baterías y estructuras de soporte) fueron modelados desde cero en Blender. Se separaron los pivotes estratégicamente para permitir la articulación realista de los paneles y se ajustaron las coordenadas UV para soportar mapeo de texturas.

🎨 Shaders Personalizados

Se implementaron materiales y shaders específicos para simular las propiedades físicas de los materiales (PBR), destacando la alta reflectividad (Metálico) y rugosidad de las celdas de silicio, así como los acabados mate de las estructuras de aluminio.

🚀 Optimización con LOD (Level of Detail)

Para asegurar un rendimiento fluido al renderizar un campo solar completo, se implementó un sistema de LOD. Los modelos 3D reducen automáticamente su carga poligonal a medida que la cámara se aleja, ahorrando recursos de la GPU sin sacrificar la calidad visual de cerca.

📱 Experiencia de Usuario (UX/UI)

El proyecto incluye un flujo de navegación completo con Pantallas de Inicio (Splash Screens / Main Menu) dinámicas que introducen al usuario a la experiencia antes de cargar la escena principal de simulación, asegurando transiciones suaves y profesionales.

⚙️ Instalación y Uso

Clona este repositorio:

git clone https://github.com/tu-usuario/SolParaTodos.git


Abre el proyecto utilizando Unity Editor (versión recomendada: 2022.3 LTS o superior).

Dirígete a la carpeta Scenes y abre la escena principal (MainScene o Menu).

Haz clic en el botón de Play para iniciar la simulación e interactuar con la interfaz.

Desarrollado con pasión por las energías renovables y la tecnología 3D. 🌍⚡

<img width="1185" height="562" alt="image" src="https://github.com/user-attachments/assets/0039bc04-7761-4cbd-9947-b9041069bfcf" />
