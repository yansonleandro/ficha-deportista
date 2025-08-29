# Ficha Deportista

## Descripción del Proyecto
Este proyecto es una aplicación web llamada "Ficha Deportista" que permite gestionar la información de deportistas. Incluye funcionalidades para la autenticación de usuarios, entrada de datos de deportistas y visualización de deportistas guardados. La aplicación utiliza Firebase para la autenticación y Firestore para el almacenamiento de datos.

## Estructura del Proyecto
- `index.html`: Contiene la estructura HTML de la aplicación, incluyendo secciones para la autenticación de usuarios, entrada de datos y visualización de deportistas.
- `README.md`: Este archivo proporciona información sobre cómo configurar y utilizar la aplicación.

## Pasos para Crear el Proyecto en Firebase e Integrarlo

1. **Crear un Proyecto en Firebase**:
   - Ve a la [Consola de Firebase](https://console.firebase.google.com/).
   - Haz clic en "Agregar proyecto" y escribe un nombre para tu proyecto (por ejemplo, "Ficha Deportista").
   - Sigue las instrucciones para configurar Google Analytics si lo deseas, luego haz clic en "Crear proyecto".

2. **Agregar Firebase a Tu Aplicación Web**:
   - En la Consola de Firebase, selecciona tu proyecto.
   - Haz clic en el ícono de "Web" para agregar una aplicación web.
   - Registra tu aplicación proporcionando un apodo y haz clic en "Registrar aplicación".
   - Firebase te proporcionará un objeto de configuración. Copia esta configuración ya que la necesitarás en tu `index.html`.

3. **Habilitar la Autenticación**:
   - En la Consola de Firebase, navega a "Construir" > "Autenticación".
   - Haz clic en "Comenzar" y luego en "Método de inicio de sesión".
   - Habilita la autenticación "Email/Contraseña" y guarda los cambios.

4. **Configurar Firestore**:
   - En la Consola de Firebase, navega a "Construir" > "Firestore Database".
   - Haz clic en "Crear base de datos" y elige "Iniciar en modo de prueba" para fines de desarrollo.
   - Haz clic en "Siguiente" y luego en "Listo".

5. **Integrar Firebase en Tu Proyecto**:
   - Abre tu archivo `index.html`.
   - Reemplaza el marcador de posición en la sección de configuración de Firebase con el objeto de configuración que copiaste anteriormente.
   - Asegúrate de haber incluido los scripts de Firebase en tu archivo HTML, como se muestra en tu código existente.

6. **Probar Tu Aplicación**:
   - Abre `index.html` en un navegador web.
   - Prueba las funcionalidades de autenticación y entrada de datos para asegurarte de que todo funcione correctamente.

7. **Desplegar Tu Aplicación** (opcional):
   - Puedes desplegar tu aplicación utilizando Firebase Hosting.
   - Instala Firebase CLI ejecutando `npm install -g firebase-tools`.
   - Ejecuta `firebase login` para iniciar sesión en tu cuenta de Firebase.
   - Navega a tu directorio de proyecto en la terminal y ejecuta `firebase init` para configurar la hosting de Firebase.
   - Sigue las instrucciones para configurar tus ajustes de hosting.
   - Finalmente, ejecuta `firebase deploy` para desplegar tu aplicación.

Siguiendo estos pasos, podrás crear un proyecto en Firebase e integrarlo con tu aplicación "Ficha Deportista".