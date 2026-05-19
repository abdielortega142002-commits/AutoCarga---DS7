# **AutoCarga Automática en PHP (Autoload)**

## 📁Guía de Instalación:
Para ejecutar este proyecto de forma local:
1. **Clonar el repositorio** en tu máquina local.
2. **Abrir la terminal** en la raíz del proyecto.
3. **Instalar Composer**: Asegúrate de tenerlo configurado. Si no lo tienes, aquí dejo los pasos necesarios para instalar composer:
   <details>
     <summary><b>💡 Haz clic aquí para ver una guía mas detallada de como Instalar Composer</b></summary>

     ### En Windows
     1. Descarga y ejecuta el [Composer-Setup.exe](https://getcomposer.org/Composer-Setup.exe).
     2. Sigue los pasos del asistente (detectará tu PHP automáticamente).
     3. Reinicia tu terminal.

     ### En macOS / Linux
     Ejecuta en tu terminal:
     ```bash
     php -r "copy('[https://getcomposer.org/installer](https://getcomposer.org/installer)', 'composer-setup.php');"
     sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
     php -r "unlink('composer-setup.php');"
4. **Ejecutar el proyecto**: Abre `index.php` a través de un servidor local (como WampServer o XAMPP).
5. **Verificar**: Ejecuta el siguiente comando para comprobar que ya responde:
   ```bash
   composer --version


## 📂Estructura de Archivos
* `app/Controllers/` -> Contiene las clases (Ej. `ClienteController.php`). Su Namespace es `App\Controllers`.
* `composer.json` -> Archivo de configuración que mapea el prefijo `App\` hacia la carpeta `app/`.
* `index.php` -> Punto de entrada del sistema.

## **Capturas de Pantalla sobre el Código + Ejecución**
<img width="1147" height="361" alt="image" src="https://github.com/user-attachments/assets/fb04d033-88a2-46e8-9e89-532396b29f71" />
<br>
<img width="1142" height="530" alt="image" src="https://github.com/user-attachments/assets/038eaef1-dd57-4303-b6dd-2d93905dd756" />
<br>
<img width="1152" height="542" alt="image" src="https://github.com/user-attachments/assets/5c021d56-250f-47ef-8857-6f0c28a74647" />
<br>
<img width="1146" height="529" alt="image" src="https://github.com/user-attachments/assets/c8b4e6f0-9fae-4d8c-ae1e-5456675d13a0" />
<br>
<img width="1147" height="821" alt="image" src="https://github.com/user-attachments/assets/61be93a7-51ca-48db-a553-17a9200fa022" />


## 📝Conclusión Técnica
Este Laboratorio de AutoCarga Automática en PHP me ha parecido muy interesante por el simple hecho que pone en práctica los conceptos de la POO (Programación Orientada a Objetos) adaptado al Lenguaje de Programación de PHP y tambien puedo mencionar las siguientes caracteristicas: 
1. **Mantenibilidad:** El sistema es mucho más limpio. Al crear nuevos controladores o modelos para clientes o servicios, ya no es necesario llenar el archivo principal con decenas de líneas `require` o `include`.
2. **Eficiencia de Memoria (Lazy Loading):** PHP solo carga en memoria el archivo `ClienteController.php` en el momento exacto en que se hace el `new ClienteController()`, optimizando el consumo del servidor.
3. **Estandarización:** Utilizar PSR-4 garantiza que la estructura de carpetas y Namespaces sea universal. Cualquier desarrollador que revise el código sabrá instantáneamente dónde buscar la lógica de negocio sin preguntar.

## 👨‍💻 Datos del Estudiante (Footer)

* **👤 Nombre:** Abdiel Ortega
* **🪪 Cédula:** 8-1025-287
* **👩‍🏫 Profesora:** Ing. Irina Fong
* **🏫 Universidad:** Universidad Tecnológica de Panamá (UTP)
* **🔬 Facultad:** Facultad de Ingeniería de Sistemas Computacionales
* **🎓 Carrera:** Licenciatura en Desarrollo y Gestión de Software
* **👥 Grupo:** 1GS133
