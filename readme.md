## Autores

- *Nahuel Argandoña* 🇦🇷 - 🐣 [Mi Github](https://github.com/Aubar48)
- *Gastón Cane* 🇦🇷 - 🐣 [Mi Github](https://github.com/GasmauC)
- *Eric Heredia* 🇦🇷 - 🐣 [Mi Github](https://github.com/Eric-Heredia)
- *Sofia Auzqui* 🇦🇷 - 🐣 [Mi Github](https://github.com/Sofyauzqui)

<figure><img src="./ispc.jpeg" alt="logo" style="height: 200px;"></figure>


## Proyecto IoT de Monitorización Ambiental y Detección de Plagas
Este proyecto de Internet de las Cosas (IoT) se enfoca en la monitorización ambiental y la detección de plagas mediante el uso de sensores, un simulador en Wokwi, una base de datos MySQL en Clever Cloud, y una API alojada en Render. El objetivo es crear un sistema que recoja datos en tiempo real y los guarde para análisis posterior.

Descripción general
El sistema IoT monitorea parámetros ambientales (como temperatura, humedad, etc.) utilizando sensores conectados a un microcontrolador simulado. Los datos recogidos son enviados a una API, donde se almacenan en una base de datos MySQL para su análisis y monitorización en tiempo real. Además, este sistema tiene como finalidad identificar condiciones que podrían favorecer la aparición de plagas.

Enlaces del proyecto
Simulador en Wokwi
Este simulador permite probar el funcionamiento del sistema de sensores y microcontrolador sin necesidad de hardware físico.

Código del proyecto en GitHub
Aquí se encuentra el código completo, incluyendo la conexión entre el simulador y la base de datos MySQL.

API Online en Render
La API permite interactuar con el sistema, recibir datos de los sensores y enviarlos a la base de datos. Puedes probar las respuestas del servidor con este enlace.

Clever Cloud - Base de Datos MySQL
La base de datos MySQL está alojada en Clever Cloud, donde se almacenan los datos enviados por el sistema IoT.

Componentes del sistema
Simulador Wokwi: Simula un sistema de sensores y un microcontrolador que recoge los datos ambientales.
API en Render: Recibe los datos del simulador y los envía a la base de datos.
Base de datos MySQL en Clever Cloud: Almacena los datos recibidos desde la API para ser analizados posteriormente.
Cómo usar el proyecto
Simulador: Accede al simulador en Wokwi aquí y observa cómo los sensores recopilan los datos.
API: La API está disponible en Render, donde puedes realizar consultas para obtener los datos almacenados.
Base de Datos: La base de datos está alojada en Clever Cloud y se conecta mediante la API. Los datos son almacenados de manera automática cuando el simulador está en ejecución.
Instalación
Simulador Wokwi
Abre el enlace al simulador.
Ejecuta el simulador para ver el sistema funcionando.
Código API
Clona este repositorio:
bash
Copiar código
git clone https://github.com/GasmauC/IoT.git
Instala las dependencias:
bash
Copiar código
npm install
Ejecuta el servidor:
bash
Copiar código
npm start
Base de Datos MySQL
No necesitas configurarla manualmente, ya que está alojada en Clever Cloud y conectada automáticamente con la API en Render.
Futuras mejoras
Añadir más tipos de sensores para ampliar las variables ambientales monitorizadas.
Mejorar la precisión en la detección de plagas utilizando algoritmos de machine learning.
Crear una interfaz gráfica para visualizar los datos en tiempo real.

