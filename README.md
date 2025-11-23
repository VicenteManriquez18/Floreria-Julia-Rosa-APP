 # FloreriaJuliaRosa
 Trabajo de Desarrollo de aplicaciones moviles
 # Florería Julia Rosa - App de Android
​
 Esta aplicación es el componente cliente para el sistema de la Florería Julia Rosa. Permite a los usuarios registrarse, iniciar sesión, ver productos y, a los administradores, gestionar el inventario y los pedidos.
​
 ## Configuración del Proyecto
​
 ### Android
​
 1.  **Clonar el repositorio:**
     `git clone https://github.com/VicenteManriquez18/Floreria-Julia-Rosa-APP`
​
 2.  **Abrir en Android Studio:**
     Abre Android Studio, selecciona "Open an Existing Project" y elige la carpeta del proyecto que acabas de clonar.
​
 3.  **Sincronizar Gradle:**
     Android Studio debería sincronizar el proyecto automáticamente. Si no lo hace, puedes forzar la sincronización haciendo clic en el icono del elefante de Gradle con una flecha azul en la barra superior.
​
 4.  **Ejecutar la aplicación:**
     Una vez sincronizado, puedes ejecutar la aplicación en un emulador o en un dispositivo físico.

​
 ### Backend (Xano)
​
 El backend está desarrollado en Xano. Para que la aplicación funcione, es necesario asegurarse de que los endpoints estén correctamente configurados y activos.
​
 1.  **Snapshot de Xano:**
     La snapshot mas reciente se encuentra en el repositorio, es el archivo .tar.
​
 2.  **Variables de Entorno:**
     Asegúrate de que las URLs de la API en la aplicación de Android coincidan con las de tu instancia de Xano.
​
 ## Variables y URLs Necesarias
​
 La aplicación se conecta a dos URLs base de la API de Xano. Estas están definidas en el archivo `app/src/main/java/com/juliarosa/floreria/api/RetrofitClient.kt`.
​
 *   **URL Base de Autenticación (`AUTH_BASE_URL`):**
     `https://x8ki-letl-twmt.n7.xano.io/api:yZp7H977/`
​
 *   **URL Base de la Tienda (`STORE_BASE_URL`):**
     `https://x8ki-letl-twmt.n7.xano.io/api:tsF7qylj/`
​
 ## Usuarios de Prueba
​
 Para probar la aplicación, puedes usar las siguientes credenciales:
​
 *   **Usuario Administrador:**
     *   **Email:** `admin@tienda.com`
     *   **Contraseña:** `Abc_123` 
​
 *   **Usuario Cliente:**
     *   **Email:** `test@test.com`
     *   **Contraseña:** `Abc_123`
​
 ## Almacenamiento de Imágenes
​
 Las imágenes de los productos (arreglos florales) se suben al backend de xano
