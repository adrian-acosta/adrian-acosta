## Hi there 👋

# 🖥️ ¡¡Bienvenidos a mi repositorio personal en GitHub!!

Me presento, mi nombre es Jesús Acosta, un tipo con 20 años de experiencia en el mundo de TI,. Cuento con 3 años como desarrollador y lo demas como QA tanto manual como automatizado 🤖.
La calidad me encanta al igual que programar y al encontrarme con la automatización de pruebas hace ya algunos ayeres pude hacer las dos cosas que me gustan al mismo tiempo.


## 🏫Educación

- **Egresado de la Licenciatura en sistemas computacionales por la Universidad de Occidente. 
- **Egresado de Ingeniería industrial por la Universidad del Golfo de México.


---

## 🚀 Certificaciones 

- ISTQB certified tester 
- Scrum Fundations By Certiproft
- Remote Work and Virtual Colaborarion By Certiproft
- Postman Api By Postman Academy

---

## 🛠️ Herramientas y Tecnologias


<img width="314" height="161" alt="image" src="https://github.com/user-attachments/assets/c0c3ae8a-6a14-47c9-b46a-03a127ecf922" /><img width="318" height="159" alt="image" src="https://github.com/user-attachments/assets/4ca777b6-cfa1-451d-bea9-2e1218f1f029" />


<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/06fedc87-88c0-4964-901b-6a7ff64e5525" /><img width="366" height="138" alt="image" src="https://github.com/user-attachments/assets/8a7655d8-719d-460f-8306-aa28befb91c4" /><img width="331" height="152" alt="image" src="https://github.com/user-attachments/assets/ef45880b-44f1-4043-9ecc-a11f878192bf" />





1. Clona el repositorio:

   git clone https://github.com/adrian-acosta/ML2025.git

2. Abre el proyecto en tu IDE como Eclipse / IntelliJ.

3.-Asegúrate de tener el driver de Chrome actualizado y disponible.(No se necesita instalar ningún driver para los navedadores ya que estan administrador por el Web driver manager de boni garcia.

<img width="614" height="181" alt="image" src="https://github.com/user-attachments/assets/f421ff68-221f-4edf-8630-df43055038d4" />

En caso de necesitar ejecutarlo con otro browser hay que actualizar en el archivo config.properties(Solo esta preparado para Choreme y Firefox, para que soporte otros hay que agregar en el código en la clase **WebDriverManager**

<img width="491" height="210" alt="image" src="https://github.com/user-attachments/assets/829dc266-f02f-42f8-9f26-52fc4b8ddde5" />



🚀 **Ejecución de pruebas**

Ejecutar todos los escenarios:

Utilizar el comeando mvn test o bien desde el IDE (Eclipse por ejemplo) desde la clase TestRunner

<img width="659" height="460" alt="image" src="https://github.com/user-attachments/assets/18a9a386-4e6d-4fce-b567-72627a857dea" />

📊 **Reportes Generados**

El reporte de salida de la ejecución de pruebas es el reporte sencillo de Cucumber, pero cuenta con imagenes por cada Step que se ejecuta lo cual lo hace un reporte mucho más completo y sin tener que instalar algo adicicional como otros reporteadores más complejos.

Reporte HTML Cucumber:
Abrir Reporte

<img width="269" height="173" alt="image" src="https://github.com/user-attachments/assets/ee56dd7b-4fa9-4ea9-8627-c0702bb9c9a8" />


Reporte con Capturas de Pantalla:

Ejemplo de captura de pantalla:

<img width="1363" height="597" alt="image" src="https://github.com/user-attachments/assets/a6c21104-7638-4d54-954d-04168747d689" />

<img width="1308" height="578" alt="image" src="https://github.com/user-attachments/assets/6abac5f3-87cd-4ac4-a5ac-4dba46d56581" />


El reporte para mejor visibilidad abrirlo desde la ubicación del proyecto en un navegador como Chrome.

✅ **Buenas prácticas aplicadas**

- Steps reutilizables y descriptivos.

- Captura de screenshots automáticos en pasos importantes o fallidos.

- Uso de Hooks (@Before, @After) para inicialización y cierre del WebDriver.

- Organización de features por módulo/funcionalidad.

- Reportes generados en HTML y JSON para integración con herramientas externas.

- Reutilización de métodos desde la clase BaseTest para optimización de código

- Uso del patrón de diseño Page Object Model lo que permite una reutilización de WebElements y Web methods.

- Utilización de archivo de configuración para no tener en código duro parámetros que pueden cambiar como rutas o bien el mismo navegador.
- Agregar comentarios en los métodos para una mejor comprensión del mismo.
  
- Identación a nivel de código.
