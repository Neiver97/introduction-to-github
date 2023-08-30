<!--step0 

<h1 align="center"><strong> Bienvenid@ a Prácticas de Pruebas Continuas - Curiosity</strong></h1><br> 

  

# Objetivo: 

En el Onboarding encontrarás toda la información que te servirá como guía en tu proceso de incorporación. 

## Cómo empezar: 

  

1. Haz click derecho en **Use this template** esto creara una copia de este repositorio donde encontraras información de pruebas continuas y realizaras las actividades del Onboarding. 

  

   ![Use this template](https://user-images.githubusercontent.com/1221423/169618716-fb17528d-f332-4fc5-a11a-eaa23562665e.png) 

  

2. Para el propietario elije tu cuenta banco de github para alojar el repositorio. 

  

   ![Crear un nuevo repositorio](https://user-images.githubusercontent.com/1221423/169618722-406dc508-add4-4074-83f0-c7a7ad87f6f3.png) 

  

3. En el nuevo repositorio comienza a leer la información del primer módulo y completa la primera actividad  

Cuando termines de leer estas instrucciones en el nuevo repositorio que creaste a partir del template espera 1 minuto para que se genere la rama, refresca la página e ingresa a la rama **step-1-informacion-general**. 

  

4. Completa el step y la actividad en el archivo **actividad.md** cuando hagas commit se generará la rama y la actividad del siguiente modulo. 

  

5. Cada que hagas commit de una actividad refresca la página e ingresa a la siguiente rama. 

  

6. Recuerda realizar los cuestionarios. 

  

7. Entregas el módulo final está compuesto por ejercicios que revisaremos y entregaras en los issues del repositorio template. 


endstep0--> 


<details id=1> 

<summary><h2>Step 1: Informacion General y Autogestion</h2></summary> 

## Permisos que debes solicitar<br><br> 

--- 

### Teams  

Solicita a los compañeros el ingreso a los grupos y equipos de Teams:<br> 

 - EMMA - Soporte Ambientes no Productivos<br> 

--- 



### **[Discuss](https://discuss.apps.bancolombia.com/login)**<br> 

 

Es una plataforma que funciona como un espacio en el que se formulan y solucionan preguntas técnicas es similar a Stack Overflow, aquí se intercambian conocimientos y se brinda colaboración y para ingresar debes registrarte con tu usuario de red.<br> 

  

Responder dudas en Discuss es una tarea del día a día que tiene el equipo de Curiosity, así que puedes formular o buscar preguntas relacionadas con Pruebas Continuas como primer recurso ya que probablemente tu situación ya le haya ocurrido a alguien y, por lo tanto, tendrá una solución en Discuss. 

  

--- 

<h2 align="center"><strong> 🗝 Accesos que debes Solicitar en USM</strong></h2><br> 

  

**USM** Es una herramienta utilizada para formalizar algunos servicios entre colaboradores, Allí puedes solicitar permisos de accesos, servicios básicos de TI, gestionar usuarios y roles. 


**🔗[USM sin VPN](https://mesadeservicio.bancolombia.com/usm/wpf)**<br>  

**🔗[USM con VPN](https://usm/usm/wpf?Node=iclaunchpad.pad)**<br> 

  

--- 

  

### ✔ Acceso a la red Bancolombia (Generación de token y acceso a la VPN):<br> 

  

Solicitas acceso en **[USM](https://mesadeservicio.bancolombia.com/usm/wpf)** en la ruta:<br> 

  

*Administración de Identidades y Accesos Plataformas / Gestión de Usuarios en Plataformas*  <br> 

  

- Valida que la información precargada en el menú de Datos Básicos esté correcta. <br> 

  

![1](https://user-images.githubusercontent.com/116098240/201989751-d270c740-d176-466b-983a-3231a5540b2d.PNG)<br> 

  

  

- Diligencia la siguiente información:<br> 

  

  - 📋 Indica el grupo del directorio activo **S_USUARIO_VPN_ING_SOFTWARE**<br> 

   

  - 📋 Ingresa lo siguiente en la casilla **Comentarios** : *Acceso por RDP de ambientes PREPRODUCTIVOS*<br> 

   

  ![2](https://user-images.githubusercontent.com/116098240/201990519-ba53d76b-0b45-4b85-956f-edda3852cbff.PNG)<br> 

  

  - 📩 Recibirás un correo con los pasos a seguir donde ingresaras a la url **(https://vpn.bancolombia.com/)** con el usuario, contraseña y un passcode. 
  

- Si tienes dudas sigue estas **[Instrucciones](https://github.com/bancolombia/oss-onboarding/blob/main/TokenSteps.md)**<br> 


--- 

  

### ✔ Acceso a Consola de AWS:<br> 

  

Curiosity crea, personaliza y administra las EC2 usadas para correr pruebas automatizadas, por lo tanto, este permiso lo solicitaran solo miembros de Curiosity.<br> 
  

   >> **Nota:** *Se debe adjuntar correo con el VoBo de Camilo Piedrahita o Youlin Alejandro Varela reciente no mayor a tres días hábiles* 

  

  - #### 📋 Diligencia el formulario así: 

       

    - Ambientes: Producción  

    - Plataforma: Directorio Activo 

    - Servicio: Grupo de Seguridad de Windows 

    - Nombre del Grupo: **S_PRUEBAS_CONTINUAS_AWS** <br>


   Ingresa lo siguiente en la casilla **Comentarios** :  *Acceso a ambientes PREPRODUCTIVOS AWS*<br> 

---

### ✔ Acceso a GitHub:<br> 

  

> Solicitas acceso con los grupos de seguridad: 

  

**S_OSS_GitHub** : Organización repositorios propios de Bancolombia 

**S_OSS_BCSCode** : Organización para compartir códigos a terceros 

  

En USM dirigirse a la ruta:  Inicio / Administración de Identidades y Accesos / Gestión de Usuarios en Plataformas 

  

📋 Diligencia el formulario así: 

  

- Tipo de Servicio: Modificación y/o Asignación de permisos,  

- Ambiente: producción  

- Plataforma: Directorio Activo 

- Servicio: Grupo de Seguridad Windows 

- Nombre del grupo: según necesidad. 

  

--- 

  

### ✔ Azure Devops: Vicepresidencia Servicios de Tecnología:<br> 

  

> Acá se manejan los proyectos, tableros agiles, repos, pipelines y demás herramientas DevOps y solicitas acceso si eres parte de Curiosity en **[USM](https://mesadeservicio.bancolombia.com/usm/wpf)** así :<br> 

  

Servicios Básicos de TI / Cuentas de usuario y Autorizaciones de Acceso / Autorizaciones de Acceso / Asignación accesos Azure DevOps: 

  

- Indicando en lugar de una célula el grupo<br> 

  

![acceso-azure](https://user-images.githubusercontent.com/116098240/201992189-f4a09bc1-f472-41e5-a400-4d72bbdc03d7.PNG) 

  

  

### ✔ Azure Devops: Soporte Ingeniería TI:<br> 

  

> Proyecto de soporte de pruebas continuas aqui es donde se reciben las solicitudes de Soporte en el Backlog y solicitas acceso si eres miembro de curiosity en **[USM](https://mesadeservicio.bancolombia.com/usm/wpf)** en la ruta:<br> 

- **Servicios Basicos de TI | Cuentas de usuario y Autorizaciones de Acceso | Autorizaciones de Acceso|Asignación accesos Azure DevOps|**<br><br> 

  

  

❗ **Si eres proveedor no debes realizar la solicitud para ser agregado a los proyectos de** **[Azure DevOps:](https://dev.azure.com/GrupoBancolombia).**<br> 

  

--- 

  

🗝 Accesos que debes Solicitar al equipo de DevOps y Métricas 

  

- Acceso a **[Hygieia](https://devops.apps.bancolombia.com/#/)** 

- Acceso a **[Sonar](https://sonar.apps.bancolombia.com/)** 

- Acceso a **[Artifactory](https://artifactory.apps.bancolombia.com/ui/)**<br> 

  

--- 

  

### ✔ Asignación de Movilizadores:<br> 

  

Solo las personas que se encuentren en la lista de movilizadores podrán crear las solicitudes en el Backlog de soporte, los movilizadores son los encargados de validar e intentar dar solución a los errores antes de crear los casos en el backlog de soporte y dar a conocer a los equipos los cambios realizados (configuraciones o nuevas definiciones) que se comunican por medio de las alineaciones u otros medios. Cada célula debe tener un máximo de dos movilizadores. 

  

**[Conversatorio Rol Movilizadores](https://bancolombia.sharepoint.com/:v:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/General/Conversatorio%20Rol%20movilizador%20de%20pruebas%20continuas%20de%20Software.mp4?csf=1&web=1&e=TsjPjf)**<br><br> 

  

![mov](https://user-images.githubusercontent.com/116098240/202485441-dc927e85-868f-494e-81bc-964eaa043cdd.png)<br> 

  

  

Para asignar los movilizadores se usa el siguiente pipeline operativo **[AW1192003_DevOps_Operations_Assign_Mobilizer](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_build?definitionId=16449)**, donde debes ingresar la información que se solicita para correr el pipeline y el líder de la célula deberá aprobar la asignación del movilizador, después de ejecutarlo le debes compartir el link de la ejecución al líder para que apruebe la tarea, para más información ingresa a este **[Link](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/16678/Pipelines-Operativos-DevOps-(Creaci%C3%B3n-de-Repos-asignaci%C3%B3n-de-permisos-borrado-de-ramas-asignaci%C3%B3n-de-build-a-PR)?anchor=7.-asignar-movilizadores)**.<br><br> 

  

![movilizadores](https://user-images.githubusercontent.com/116098240/202485306-3bd4a9b7-b73f-489c-afab-e4d2d2ecfd36.PNG)<br> 



  

--- 

  

<h2 align="center"><strong>📍 Sitios de Interés </strong></h2><br> 

  

<h2>ℹ Autogestión</h2><br> 

  

🔗 **[¿Y Cómo lo hago?](https://bancolombia.sharepoint.com/sites/co-clh)** Donde puedes consultar información importante sobre autogestión y temas de interés en diferentes categorías <br> 

  

🔗 **[CHAT MATEO](https://home-e31.niceincontact.com/incontact/chatclient/index.html)** Aquí te ayudaran con los inconvenientes que tengas con tu usuario de red, dudas sobre accesos a plataformas o en general procedimientos que desconozcas y de los que requieras mayor claridad.<br> 

  

🔗 **[MATEO A UN CLICK](https://livechat.boldchat.com/aid/417108825276829833/chat/visitor.jsp?&cwdid=2365820882664860794?resize=true&cbdid=7880232268121371696)** donde atenderán tu necesidad, puedes ver este **[Instructivo](https://bancolombia.sharepoint.com/sites/portalempleado/noticias/Documents/Forms/AllItems.aspx?id=%2Fsites%2Fportalempleado%2Fnoticias%2FDocuments%2FVSC%2FInstructivo%20uso%20MATEO%20a%20un%20clic%20V1%2Epdf&parent=%2Fsites%2Fportalempleado%2Fnoticias%2FDocuments%2FVSC&p=true&ga=1)** para saber cómo hacerlo   <br> 

  

🔗 **[USM](https://mesadeservicio.bancolombia.com/usm/wpf)** : Es una herramienta utilizada para formalizar algunos servicios entre colaboradores, Allí puedes solicitar permisos de accesos, servicios básicos de TI, gestionar usuarios y roles..<br> 

  

🔗 **[USD](https://mesadeservicio.bancolombia.com/CAisd/pdmweb1.exe)** : Es una herramienta utilizada como mesa de servicios. Allí se pueden gestionar solicitudes como: Ordenes de Cambios (OC), incidentes, eventos, casos problemas...<br> 

  

🔗 **[Sofy]** Bot que ayudara a resolver dudas y consultas relacionadas a temas laborales (certificados, vacaciones, permisos, nómina, etc.)<br> 

  

🔗 **[Desbloqueo de Usuario - Cambio de Contraseña - MFA](https://bancolombia.sharepoint.com.mcas.ms/sites/co-clh/SitePages/tecnologia/Desbloqueo-de-usuarios-y-o-cambio-de-contrase%C3%B1a-de-red.aspx)** Encuentra aquí el paso a paso para que autogestiones de una forma ágil y simple el desbloqueo y/o cambio de tu contraseña de red <br> 

  

--- 

  

<h2>ℹ Información y Ayuda Técnica</h2></summary><br> 

  

🔗 **[Portal de conocimientos TI](https://bancolombia.sharepoint.com/:f:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/General?csf=1&web=1&e=lqf8rK)** Aquí puedes encontrar información general de pruebas de software y Dojos.<br> 

  

🔗 **[Wiki](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis)** Aquí puedes encontrar información de todo lo relacionado con la Vicepresidencia Servicios de Tecnología <br> 

  

> >  🔗 **[Wiki Pruebas Continuas](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/9568/Pruebas-Continuas-de-Software)** Sección de Pruebas Continuas en la wiki<br> 

  

🔗 **[Discuss](https://discuss.apps.bancolombia.com/)** Es un foro donde puedes buscar, publicar y responder dudas.<br> 

  

📺 **[Discuss (hasta el minuto 11:20)](https://bancolombia-my.sharepoint.com.mcas.ms/personal/jaasilv_bancolombia_com_co/_layouts/15/stream.aspx?id=%2Fpersonal%2Fjaasilv%5Fbancolombia%5Fcom%5Fco%2FDocuments%2FGrabaciones%2FAlienaci%C3%B3n%20T%C3%A9cnica%20Movilizadores%20Pruebas%20Continuas%2D20220817%5F080935%2DGrabaci%C3%B3n%20de%20la%20reuni%C3%B3n%2Emp4)**  

  

🔗 **[Medium Bancolombia](https://medium.com/bancolombia-tech)** Es un Blog técnico público en donde podrás encontrar la forma en que hacemos tecnología en el banco. Te recomiendo que revises los artículos publicados que sean de tu interés, y que más adelante te animes a escribir y compartir tus experiencias en el<br> 

  

🔗 **[Fortalece tu conocimiento](https://bancolombia.sharepoint.com/sites/co-vsti/SitePages/skill-hacking_rutas-de-conocimiento_material-de-autoestudio.aspx)** Podrás encontrar algunas fuentes de conocimientos sugeridas para fortalecer tus habilidades en las tecnologías, lenguajes, frameworks y demás elementos que necesites para desarrollarte profesionalmente y aportar el valor que se requiere en los proyectos y actividades donde participes.<br>  

  

--- 

  

<h2 align="center">🤝Acuerdos del Equipo</h2><br> 

  

- Si tienes algún impedimento o no te sientes satisfecho con los temas que estás trabajando, hazlo saber inmediatamente. 

- Respetamos la diversidad del equipo y trabajamos día a día por la equidad de género. 

- Para que las conversaciones sean fluidas, responde los chats y correos lo más pronto posible. Evita que superen un día (a excepción de los    fines de semana). 

- Está bien no estar de acuerdo, tus ideas son valiosas. Di lo que piensas sin enfocarte tanto en las jerarquías o en procesos rigurosos. 

- Si necesitas cancelar una reunión, hazlo con tiempo. Evita hacerlo el mismo día. 

- Somos proactivos, proponemos nuestro propio plan de trabajo. 

- Somos curiosos y nos gusta compartir conocimiento. Constantemente buscamos nuevas tendencias tecnológicas y mejores prácticas.<br><br><br> 

  

<h2 align="center">Ceremonias</h2><br> 

  

- **Review y Planning** 

  

- **Alineaciones Técnicas Movilizadores Pruebas Continuas:** Es un espacio periódico el tercer miércoles de cada mes de 8 a 10 am, donde se brinda información relacionada con soporte, nuevas prácticas, métricas, indicadores y en general todo lo relacionado con pruebas continuas con el objetivo de mantener a los equipos actualizados.  

  

- **Alineaciones técnicas Prácticas de Pruebas Automatizadas:** Este espacio es orientado a los integrantes del equipo aquí se dictan temas técnicos y se realizan ejercicios prácticos. 

  

- - **Alineación Curiosity + Líderes técnicos aliados** Es un espacio con el objetivo de dar a conocer avances de nuevas prácticas, socialización de indicadores de calidad, se comparte información relacionada con el backlog de soporte y otros temas propuestos por nuestros aliados. 

  

  

<h2 align="center">Estructura Organizacional</h2> 

  

La dirección de Ingeniería está conformada por 6 equipos que se dedican a habilitar, de manera transversal, nuevas prácticas en el ciclo de desarrollo de software de los proyectos de Bancolombia. 

  

- DevOps y Métricas 

- Prácticas de Desarrollo de Software 

- **Prácticas de Automatización Pruebas** ✔️ 

- Prácticas de Performance 

- Seguridad de TI 

- Oficina Open Source 

  

<h3 align="center">Realiza el Cuestionario dando click <a href="https://forms.office.com/r/4KSTNjKzYd">Aquí</h3> 

  

--- 

  

<h2>Tipos de Pruebas</h2><br> 

  

<img src="https://user-images.githubusercontent.com/116098240/199100259-4b4d36df-0fde-4458-b919-85005bcf9fe0.PNG" alt="tpiramide" height="600" width="900"> 

  

### 🟢 Pruebas Unitarias: 

Las pruebas unitarias son una forma de comprobar el código a nivel de módulos individuales para asegurarnos que funcionan correctamente por separado. Esto proporciona un plus de estabilidad al asegurar que cada trozo de código no tiene fallos.  

  

### 🔄 Pruebas de Integración: 

El objetivo de estas pruebas es verificar el funcionamiento entre los distintos componentes, buscan comprobar que interactúan correctamente a través de sus interfaces, tanto internas como externas, cubren la funcionalidad establecida y se ajustan a los requisitos no funcionales especificados en las verificaciones correspondientes. 

  

### 🆗 Pruebas de Aceptación: 

Las pruebas de aceptación se enfocan en verificar si el sistema es **“apto para el uso”**. Se diseñan principalmente a partir de las especificaciones de requerimientos, casos de uso y de los procesos de negocio definidos. 

  

### 👁️‍🗨️ Pruebas UI,UX,CX: 

Se les atribuye las siglas de la siguiente manera:  

  

- **UI** User Interface 

  

- **UX** User Experience 

  

- **CX** Customer Experience 

  

Este tipo de pruebas, en general miden la interacción del usuario o cliente con el sistema. Aspectos como la usabilidad, los colores, los tipos de letras, se evalúan para obtener una aplicación acorde y agradable visualmente. 

  

### ↔️ Pruebas E2E: 

En estas se comprueba que el flujo de principio a fin, funcione como el negocio lo espera, es decir, se conectan otros sistemas para validar que se tengan los resultados esperados **(Back-end y Front-end)** en las entradas y salidas de cada uno. 

  

### 🔎 Pruebas Exploratorias: 

Estas pruebas se hacen manualmente, son simultáneamente: Aprender, Diseñar y Ejecutar casos de prueba, hacerlo todo al mismo tiempo. 

  

#### ¿Por qué hacer pruebas exploratorias? 

  

- No todo lo podemos cubrir o es susceptible de automatización, se deben hacer pruebas manuales.  

  

- Podemos encontrar errores que en los niveles anteriores no se identificaron.  

  

- Aprendemos de la aplicación que estamos probando.  

  

- Agilidad en el proceso. 

  

### 📉 Pruebas de Performance: 

Permiten conocer y mitigar los riesgos relacionados con el mal desempeño de las aplicaciones en los entornos de producción y realizar las correcciones necesarias antes de ser desplegadas en ambientes productivos.  

  

Se cuantifica la capacidad de la infraestructura, se validan los requerimientos de performance, la escalabilidad de las plataformas y del sistema a probar. De esta manera, se puede conocer qué cantidad de clientes simultáneos soportan los productos, con tiempos y datos razonables sobre la infraestructura y las plataformas propuestas.  

  

Así mismo, se puede saber si es suficiente el hardware para soportar el nivel propuesto de transacciones y qué expectativa de crecimiento soporta.  

  

### 🔒 Pruebas de Seguridad: 

  

Este tipo de pruebas evidencia las vulnerabilidades existentes en las soluciones a nivel de la aplicación, código fuente y/o infraestructura, con el propósito de evitar que posibles Hackers realicen operaciones no autorizadas sobre ellas, violando la privacidad de la organización y comprometiendo información sensible de la empresa. 

  

--- 

  

## :keyboard: Actividad : 


1. En el archivo actividad1.md da click en el ✏️ para editar y escribe una lista con las Alineaciones que realiza Curiosity.

2. Haz commit, espera 30 segundo y refresca la página y ve a la siguiente rama Step 2: Soporte Ingeniería de SW DevExp



  

--- 

</details> 

  

<details id=2> 

<summary><h2>Step 2: Soporte Ingeniería de Software DevExp</h2></summary> 


Es un equipo de soporte transversal, que apoya los equipos de las diferentes EVCs, en las etapas de Desarrollo y Certificación de las soluciones del grupo Bancolombia.<br> 

  

## **[🔗Servicio Soporte - Standby Ingeniería](https://github.com/pcgutier/pc-onboarding-curiosity/blob/1f03f8bf631ecf14da28ead7d8b8046e9b2d0157/files/Servicio%20Soporte%20-%20Standby%20Ingenieria%20(1).pdf)**<br> 

  

- Las solicitudes se radican en el **[Backlog de Soporte de Ingeniería de SW DevExp](https://grupobancolombia.visualstudio.com/Soporte%20Ingenier%C3%ADa%20de%20TI/_backlogs/backlog/Soporte%20Ingenieria%20de%20SW%20-%20DevExp/Stories)** Así:<br> 

  

  

![1](https://user-images.githubusercontent.com/116098240/202241544-3f9a8fab-2344-4062-b03a-2701173d86c0.PNG)<br> 

![2](https://user-images.githubusercontent.com/116098240/202241579-0b46124e-b64d-4638-b6cb-80a161c00d6d.PNG) 

![3](https://user-images.githubusercontent.com/116098240/202241593-b5f9c097-3c1f-458d-a88f-69dc978d94b2.PNG)<br> 

  

  

Recuerda que si necesitas que tu solicitud sea prioritaria debes seleccionar el switch de Afectación en PDN y poner un TAG "Salida a PDN"<br> 

  

![tag](https://user-images.githubusercontent.com/116098240/202548730-1f713c3f-140a-4be7-8d78-b8bc93244f40.PNG) 

  

  

## Selecciona un template según tu solicitud:<br> 

  

### **Template Solicitud de excepción**<br> 

  

Las excepciones de pruebas se dan en Hygeia.<br> 

  

![7](https://user-images.githubusercontent.com/116098240/202247023-f8f8822a-839c-44a9-88e5-e0b00a20de36.PNG)<br> 

  

  

![141](https://user-images.githubusercontent.com/116098240/202286166-e47f5fa0-8930-4fdb-ad3f-492b4d243d31.png)<br> 

  

Es importante tener en cuenta que para que las solicitudes puedan ser atendidas debidamente deben contener la información solicitada y deben estar diligenciadas completamente de lo contrario serán rechazadas.<br> 

  

**Template Solicitud General**<br> 

![q](https://user-images.githubusercontent.com/116098240/202287400-af0f0fc5-181c-486d-be1e-ce955780abf3.PNG) 

  

![88](https://user-images.githubusercontent.com/116098240/202287825-b917e58e-67ba-4191-9ef5-f24b3fbebf00.PNG)<br> 

  

En estos artículos de la wiki puedes ver cómo realizar una solicitud detalladamente, los requisitos que deben cumplir y los motivos de rechazo. 

**[Soporte Ingeniería de Software DevExp](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/38256/Soporte-Ingenier%C3%ADa-de-Software-DevExp)** y 

**[Soporte Azure DevOps Pruebas Continuas Curiosity](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/12353/Soporte-Azure-DevOps-Pruebas-Continuas-Curiosity)**<br> 

  

--- 


![SLA](https://user-images.githubusercontent.com/116098240/202292684-afadebbe-49aa-45d8-921b-dfb02e047317.PNG)<br><br> 

  
--- 

  

### StandBy 

Se brinda atención a incidentes de salidas a producción que puedan presentarse luego de la jornada laboral (8:00-17:00). 

  

**En ningún caso se atienden excepciones en el StandBy.** 

  

Solo se atienden los siguientes incidentes:  

  

- Problemas con las EC2 y los agentes del pool DevOps-Automatizadas y DevOps-Automatizadas-Cloud, que no sean instalaciones particulares. 

  

- Problemas con agentes de los pools: DevOps-Automatizadas, PerformanceTest, DevopsPruebasEspecializadas-Cloud, DevOpsPE-Seguridad y DevSecOps-Engine. 

  

- Errores en los pipelines de RM que venían siendo ejecutados y estaban funcionales, pero no corren en la salida a Producción (Automatizadas, Performance y Seguridad). 

  

- Problemas con las herramientas soportadas por Curiosity.<br> 

  

![9](https://user-images.githubusercontent.com/116098240/202285215-69dedf7f-168f-4f20-8924-967eadfdb6d4.PNG) 

![10](https://user-images.githubusercontent.com/116098240/202284022-23962678-c90c-426b-a101-fa6f01f14916.PNG)<br> 

  

- Extensión del Uso de Automatización. 

- Las demás novedades deberán ser ingresadas al backlog de las diferentes áreas y acogerse al SLA que se tenga definido. 

**Para contactar las personas en StandBy debe comunicarse al número de celular 3167419112.<br> 

Horario del StandBy es de **17:01 a 7:59** y que cada semana cambia la personas que está disponibles.**<br><br> 
  

<h3 align="center">Realiza el Cuestionario dando click <a href="https://forms.office.com/r/kqgNay6rkE">Aquí</h3> 


--- 

## :keyboard: Actividad : 

1. En el archivo actividad2.md da click en el ✏️ para editar y escribe el nombre de los pools de Azure Devops para agentes donde se ejecutan las pruebas automatizadas.
Ej. - Nombre-del-Pool

2. haz commit, espera 30 segundo, refresca la página y dirígete a la siguiente rama Step 3: Pipelines Operativos

  

--- 


</details> 

  

  

  

<details id=3> 

<summary><h2>Step 3: Pipelines Operativos</h2></summary> 


### 1. Pipeline para configurar **Quality gate** y **Quality Profile** para proyectos de certificación en SonarQube Bancolombia.<br> 

  - El proyecto se debe crear en Sonar con el pipeline  **[AW1192003_DevOps_Operations_Sonarqube](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_build?definitionId=13613)**.<br>   

  - El nombre del proyecto debe ingresarse tal cual está en SonarQube 

  - Se debe ingresar correctamente el nombre de algún agente que tenga el equipo en el pool **DevopsAutomatizadas-Cloud**  y la EC2 donde este instalado el agente debe estar encendida para evitar encolamiento.<br> 

  

**[NU0007001_Curiosity_Operations_quality_gate_and_profile](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_build?definitionId=18617)**.<br> 

  

![99](https://user-images.githubusercontent.com/116098240/202299693-152892ea-6493-494d-9c1c-cab63d477494.PNG)<br><br> 

  

### 2. Pipeline para registrar repositorio en el Assessment Automático.<br> 

  

- Se debe ingresar el nombre del repositorio de Automatización  **_Test** o **_MR_Test** tal cual como esta en azure devops. 

- Ingresa el nombre del líder del FullStack del proyecto de automatización 

- El movilizador que ejecuta el pipeline quedara registrado como dueño del repositorio en cuestión.<br> 

  

**[NU0007001_Curiosity_Operations_Assessment_repo_register](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_build?definitionId=18185)**.<br>   

  

![333](https://user-images.githubusercontent.com/116098240/202299203-37604b25-c9cf-485c-9b6b-4ed51cdeba89.PNG)<br><br> 

  

  

### 3. Pipeline para actualizar indicador el Assessment automático de un repositorio<br> 

  

**[NU0007001_Curiosity_Operations_Assessment_refresh_report](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_build?definitionId=18467)**.<br> 

  

![qqqq](https://user-images.githubusercontent.com/116098240/202299942-4e31fe9e-6154-4a52-a30b-f924f4c732c8.PNG)<br> 

  

  

### Otros Pipelines 

  

- **Pipeline Encendido/Apagado instancia EC2:** Este pipeline lo usan los usuarios de las EC2 para encender y apagar las instancias **[Start_Stop_Instances_EC2](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_build?definitionId=10204&view=runs)**. <br> 

  

📺  **[Encendido/Apagado EC2](https://bancolombia.sharepoint.com/:v:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/General/EncendidoYApagadoInstanciasEC2.mp4?csf=1&web=1&e=HvEnhx)**  

  
### Como integrante de curiosity ten en cuenta solicitar informacion sobre los pipelines operativos de Curiosity que facilitan la realizacion de diferentes tareas.


--- 

## :keyboard: Actividad : 

  
1. En el archivo actividad3.md da click en el ✏️ para editar y escribe una lista
Ej. - NU0007001_Nombre_Pipeline con los nombres de los pipelines operativos de Curiosity.

2. Haz commit, espera 30 segundos, refresca la página y dirígete a la siguiente rama Step 4: Métricas de Calidad
  

--- 

  

</details> 

  

  

<details id=4> 

<summary><h2>Step 4: Métricas de Calidad</h2></summary> 

  

<h2 align="center">HYGIEIA</h2> 

Es una herramienta que nos permite validar el cumplimiento de métricas a través de los criterios definidos y los márgenes aceptables establecidos, se presenta en forma de tablero donde podemos observar información sobre las Métricas de calidad que aplica pruebas continuas, además permite visualizar el comportamiento de las aplicaciones a través de un histograma recolectando la información a través de los pipelines de forma automatizada.<br> 

  

📺 **[Alineación técnica Movilizadores: Discuss, Soporte y Hygeia desde 1:15:00](https://bancolombia-my.sharepoint.com.mcas.ms/personal/jaasilv_bancolombia_com_co/_layouts/15/stream.aspx?id=%2Fpersonal%2Fjaasilv%5Fbancolombia%5Fcom%5Fco%2FDocuments%2FGrabaciones%2FAlienaci%C3%B3n%20T%C3%A9cnica%20Movilizadores%20Pruebas%20Continuas%2D20220817%5F080935%2DGrabaci%C3%B3n%20de%20la%20reuni%C3%B3n%2Emp4)**  

  

- El **Test Atomation Coverage:** se debe configurar en la carpeta de la automatización en el archivo serenity.properties las variables: 

  - **coverage.goal** que tendrá el valor de automatizaciones que se tiene como objetivo realizar 

  - **coverage.compliance** que tendrá la cantidad de automatizaciones actual. 

  - opcionalmente o en algunos casos obligatorio tendrá un campo de comentario que es **coverage.comment** el cual se usara para dejar un corto comentario sobre el estado actual de la cobertura.<br><br> 

  

  <img src="https://user-images.githubusercontent.com/116098240/199733287-611efa8b-9103-48d2-a975-e76f52c97c9d.png" alt="hygeia-coverage" height="250" width="600"> 

  

- Además se debe crear un tablero por repositorio en hygieia y configurarlo, mira como **[Manual para configurar los widget de test automation-performance coverage](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10981/Manual-para-configurar-los-widget-de-test-automation-performance-coverage)**<br><br> 

  

**[Mas Info: Cobertura de pruebas automatizadas](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/15351/Cobertura-de-pruebas-automaticas)**<br><br> 

  

--- 

  

<h2 align="center"><img src="https://user-images.githubusercontent.com/116098240/199788751-912d071b-ce6a-452c-a09e-bc23986441ef.jpeg" alt="graf" width="300 "  height="150"</h2><br> 

  
### Uso de la Automatizacion:<br> 

Se configura de la misma forma que la metrica de cobertura de la automatizacion en el archivo serenity.properties. **[🔗Cobertura de pruebas automaticas](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/15351/Cobertura-de-pruebas-automaticas)**<br><br> 

  

![image](https://user-images.githubusercontent.com/116098240/199827340-6c7a975a-9c8a-4918-8663-91013042707b.png) 

  

📺 **[Aca puedes encontrar mas informacion de las Metricas de calidad de Grafana](https://bancolombia.sharepoint.com/sites/co-vsti/SitePages/skill-hacking-rutas-de-conocimiento-pruebas-continuas-de-software-responsabilidad-de-lideres.aspx#tablero-grafana)**<br><br> 

--- 

  

### Assessment Repositorios y Pipelines de Automatización<br> 

Verifica  que los repositorios  **_Test** y **_MR_Test**, los **pipelines de build (CI/CD)** y **Release Mangement Test_DEV** en Azure DevOps cumplan con los pilares y los formatos establecidos, ya que deben tener una correcta configuración además  la correcta implementación de **ScreenPlay**  y el uso de **Sonar**.<br><br> 

  

### Pilares de la Revisión<br> 

  

#### Repositorios VSTS<br> 

  

- **Existe Repo** para esto debe estar nombrado siguiendo el estándar de nombramiento. 

  

- **Estándar de Nombramiento** 🠮<code>codigoUnico_NombreComponente_Test</code> 

   **Mono-repositorios** 🠮 <code>codigoUnico_NombreAplicacion_MR_Test*.</code><br> 

  

- **Estructura de Almacenamiento** 

  

![image](https://user-images.githubusercontent.com/116098240/199814227-4ae46660-8def-40ca-894c-5ff8e30c9e91.png) 

  

  

- **Nombramiento de las Ramas:**<br> 

  

    - Rama principal 🠮 **Trunk** 

    - Ramas Feature:<code>feature/CódigoHistoria-NombreHistoria</code> 🠮 <code>Ej:feature/102030-CambioFormatoNumeros</code> 

    - Si no hay rama homóloga en el repositorio de aplicación sera asi 🠮 <code>feature/CódigoHistoria-NombreHistoria</code> 

  

  - Versionamiento Continuo 

  - Pull Request Continuo<br><br> 

  

**ScreenPlay** Valida que se aplique el **[Arquetipo de referencia](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/9602/Patr%C3%B3n-ScreenPlay?anchor=**arquetipo-de-referencia)**<br><br> 

  

**Pipelines** Se valida que cumpla con este estándar establecido por Curiosity **[Creación pipeline automatización CD](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10058/Creaci%C3%B3n-pipeline-automatizaci%C3%B3n-CD)**<br> 

  

  - Debe cumplir el **[Estándar de Nombramiento](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/12809/Pipeline-de-Integraci%C3%B3n-Continua?anchor=**est%C3%A1ndar-de-nombramiento**)**:<code>AW/NUXXXXXXX_nombreRepositorio</code> 🠮 <code>Ej.AW1021002_MS_AccountQuery</code> 

  

  - Se valida que las tareas del Pipeline de Build están completas y habilitadas.<br> 

  

  <img src="https://user-images.githubusercontent.com/116098240/199815255-0cce9dc4-e737-4a6b-a890-26ed7616aba8.png" alt="taskbuild" height="400" width="300"> 

  

  - Estándar de Compilación para Gradle CD se valida la compilacion del artefacto pero que no se ejecuten las pruebas usando el comando **build -x test** en la tarea Gradle.<br> 

  - Uso del pool de agentes **Build**<br> 

  - Debe estar correctamente almacenado en la  ruta 🠮 <code>Seccion de Practicas de Automatizacion\AWxxxx_NombreAplicativo</code><br><br> 

   

![image](https://user-images.githubusercontent.com/116098240/199815483-c736e40f-dd73-4bd1-b8b5-180553938a7b.png)<br> 

  

**Pipeline RM** Debe cumplir con el estándar definido **[Pipeline RM de Pruebas E2E (RM _DEV)](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10057/Pipeline-RM-de-Pruebas-E2E-(RM-_DEV))**<br> 

  

- Debe cumplir con el **[Estándar de nombramiento](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10057/Pipeline-RM-de-Pruebas-E2E-(RM-_DEV)?anchor=**est%C3%A1ndar-de-nombramiento**)**: código de la aplicación, el nombre de la aplicación y el sufijo _DEV. <code>AWxxxx_NomAplicacion_Test_DEV 🠮 Ej.AW1113001_Gema_Test_DEV</code><br> 

- Usa Pool Agentes Correcto para el Pipeline de Release Management en cada uno de los stage <code>DevOps-Automatizadas-Cloud</code>. 

- El Pipeline de **RM** tiene todas las tareas.<br><br> 

- Estándar de Compilación para el Pipeline de Release Management. 

- La tarea Gasper Bancolombia está habilitada.<br> 

  

![image](https://user-images.githubusercontent.com/116098240/199817517-caf63635-9e0c-4575-b7d9-7c94a7af1661.png) 

  

--- 

  

<h2 align="center">Sonar</h2><br> 

  

La configuración se hace en el Pipeline CI/CD como se indica en la configuración del Pipeline CD, sección **[Prepare analysis on SonarQube](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10057/Pipeline-RM-de-Pruebas-E2E-(RM-_DEV))**<br> 

     

  - Project Key Correcto es el identificador en sonar de un repositorio debe tener el nombre del repositorio que se está analizando. 

     - Tiene el Quality Gate para repositorios de certificacion: <code>Quality Gate - Nuevos_CER</code> 

     - Tiene el Quality Profile para los análisis a los repositorios de certificación: <code>CertificacionBancolombia-Java</code> y  deben tener un solo Quality Profile. 

  

--- 

- Curiosity realiza auditorias por medio de las metricas generadas para hacer seguimiento mas de cerca a los repositorios que presentan un porcentaje por debajo de lo definido como aceptable y para identificar cuales equipos necesitan asesorias en cuanto a las automatizaciones y los estandares definidos para pipelines y repositorios. 

  

- Aqui puedes encontrar toda la informacion de los lineamientos evaluados en el **[Assessment Repositorios y Pipelines de Automatización](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/20628/Assesment-Repositorios-y-Pipelines-de-Automatizaci%C3%B3n)**<br>  

  

- Los repositorios recien creados deben ejecutar un pipeline operativo para la creacion del indicador **[🔗Mas Info: Creación de repositorio de automatización en Assessment automatico](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/32295/Pipelines-operativos-Curiosity?anchor=2.-creaci%C3%B3n-de-repositorio-de-automatizaci%C3%B3n-en-assessment-automatico)**<br> 

  

- Los **Monorepositorios** que son aquellos que tienen varios proyectos y se usan para aquellos proyectos que están creando automatizaciones para servicios y microservicios tienen un estándar diferente que puedes encontrar aqui  **[🔗Monorepositorios para proyectos de pruebas E2E ](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/14796/Monorepositorios-para-proyectos-de-pruebas-E2E-(Solo-Microservicios))**<br><br> 

  

--- 

  

<h3 align="center">Realiza el Cuestionario dando click <a href="https://forms.office.com/r/qMtrNwycfQ">Aquí</h3> 

  

--- 

## :keyboard: Actividad : 

  
1. En el archivo actividad4.md da click en el ✏️ para editar y escribe una lista con el nombre de las 3 variables que se configuran en el serenity.properties para configurar el Test Atomation Coverage:

Ej metrica.nombre

2. Haz commit, espera 30 segundos, refresca la pagina e ingresa a la siguiente rama Step 5: Proceso de Pruebas

  

--- 

</details>   

  

<details id=5> 

<summary><h2>Step 5: Proceso de Pruebas</h2></summary> 


![proceso-test](https://user-images.githubusercontent.com/116098240/199835776-a86a2efa-718e-4096-bf93-a90b06ae5dc5.PNG) 

  

--- 

  
<h2>📑 Plan de Pruebas</h2><br> 


<img src="https://user-images.githubusercontent.com/116098240/199059170-d4aff827-a419-4b01-8a5d-31ff2bd81326.PNG" alt="TESTPLAN" height="550" width="1100"> 

  

### Estándar de nombramiento ⮕ *TEST PLAN EVC12345_(ID de la HU) SPRINT *<br> 

  

<img src="https://user-images.githubusercontent.com/116098240/199047490-86541fc7-5910-4fb9-904a-3737f3e58398.PNG" alt="testplan-nombramiento" height="70" width="1000"> 

  

--- 

### ¿Qué ítems debe contener? <br> 

  

- **Alcance:** Donde se especifican las funcionalidades que harán parte de la prueba, las acciones que se van a realizar, el resultado esperado y los aspectos que no haran parte de la prueba. 

  

- **Estrategia:** Aqui se describe cómo se va a llevar a cabo la prueba, en cuanto a orden de realización de los tipos de pruebas, funcionalidades a verificarse y los criterios para comenzar los diferentes tipos de pruebas. 

  

- **Supuestos y limitaciones:** Se especifican las características funcionales o no funcionales que son necesarias para llevar a cabo el proceso de pruebas.<br> 

  

>>***Ejemplo**: Accesos a aplicativos, Bases de Datos, Parametrizaciones, Recursos, tiempo, entre otros.*<br><br> 

  

- **Datos e infraestructura:** Se definen los datos que son requeridos para poder ejecutar la prueba conforme el alcance y la estrategia. Además  las necesidades que se tienen en el ambiente en el cual se van a realizar las pruebas y se describen los aplicativos, usuarios, rutas y demás componentes técnicos requeridos para la prueba.<br> 

  

- **Líneas impactadas y equipos de trabajo:** Son las líneas o frentes que se están impactando con la iniciativa o incidente, y se debe incluir el equipo de trabajo que participa o interviene tanto en la línea principal como en las líneas impactadas.<br><br> 

  

**[🔗Wiki: Guia para la planeación de las pruebas](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/9237/Guia-para-la-planeaci%C3%B3n-de-las-pruebas)** 

  

--- 

  

📺 **[Tipos y Proceso de Pruebas](https://bancolombia.sharepoint.com/:v:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/General/Repaso%20breve%20sobre%20los%20tipos%20de%20pruebas.mp4?csf=1&web=1&e=LAGDW5)**  

  

### Tag Documentado: 

  

  - Para despliegues automáticos, debe ir el repositorio de pruebas diligenciado en el **TAG** del plan de pruebas ⮕<code>Ej.ISCTR0001_CTR_Test</code><br> 

  

  - Para  pruebas  manuales  debe  estar  asociado  el  pipeline  de  salida  a  producción **GITLFS + release** ⮕<code>Ej.AW0929001_Axiom_Reporteria_Legal_LFS Release 277</code><br> 

  

>>**Nota:** Cuando en el paso a producción solo se realizan pruebas exploratorias, No es necesario colocar en el **Tag** el nombre del repositorio.<br><br> 

  

### Tipo de Test Plan: 

  

<img src="https://user-images.githubusercontent.com/116098240/199107162-d66e4bd2-8000-41ae-86d3-070162d0f032.png" alt="tipo-testplan" height="500" width="900"> 

  

  

  - **Ambos:** Implica realizar Test Plan y Check List, aplica a la mayoría de las salidas a producción con pruebas, menos en los cambios de data en producción. 

  

  - **Sólo Check List:** Cuando por motivos tecnicos no se usa **Test Plan** y se deben solicitar pruebas de Performance o Seguridad. 

  

  - **Sólo Test Plan:** Cuando tu proyecto está dentro de los casos especiales que no requieren diligenciamiento de Check List o la salida a producción es un cambio de data en producción. 

  

--- 

### Checklist de PNF (performance, seguridad) completamente diligenciado y evaluado.  

  

![CHECKLIST](https://user-images.githubusercontent.com/116098240/199059694-5ba43ca2-0ec0-4553-9321-a27712ffc36c.PNG) 

  

**[🔗Mas Info: Checklist de PNF](https://grupobancolombia.visualstudio.com.mcas.ms/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/12681/Check-List-de-Pruebas-No-Funcionales)** 

### 3.Entregables📎:  

  

- Matriz de riesgos(Excepto para incidentes) ⮕ **Herramienta Matriz de riesgos.xlsx** 

  

**[🔗Mas Info: Matriz de Riesgos](https://grupobancolombia.visualstudio.com.mcas.ms/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/12778/Matriz-de-Riesgos)** 

  

- Evidencias de pruebas ⮕ **Evidencias_EVCXXXX.pdf** 

  

![entregables](https://user-images.githubusercontent.com/116098240/199052857-39f41d2e-6501-4aea-8966-34b8d49c2cb1.PNG) 



  

--- 

  

<h2>✅ DOD-Concepto de Calidad</h2> 

  

![DOD](https://user-images.githubusercontent.com/116098240/199057036-1304b94c-be41-4596-a49c-5fcf55f36208.PNG) 

### 1.Indicar herramienta de despliegue:<br> 

  

![herramienta](https://user-images.githubusercontent.com/116098240/199061582-bcc43412-33eb-40aa-938b-7e0041b981a1.PNG) 

  

  - **Devops Automático:** Para despliegues automaticos con DevOps 

  - **GITLFS:** Para despliegues manuales con GITLFS 

  - **Solman ChaRM:** Para aplicaciones SAP<br> 

  

### 2.Campo *Parámetros Técnicas/Parches S.O:*<br> 

  

![parametros](https://user-images.githubusercontent.com/116098240/199062930-bba9662a-cf5b-4ea4-b1aa-97dcfbbd0246.PNG) 

  

  - Cuando la salida a producción corresponde a una **Configuración y/o  Parametrización  Técnica  Sin  Pruebas o Parches en S.O Sin pruebas** no se requiere Test Plan y se deja el campo **Evidencia Pruebas/Checklist P.E** en blanco. 

  

  - Si es una **Configuración  y/o  Parametrización  Técnica  Con  Pruebas**,  debe  llevar Test Plan y se realiza todo el proceso de pruebas. 

  

### 3.Campo *Evidencia Pruebas/Checklist P.E:*<br> 


  - Si hay contextualización o participación del equipo de PNF se   relaciona el **Id del Test Plan** y el **ID de PNF** con el concepto de Pruebas de seguridad y/o  performance<br> 
 

![evidencias](https://user-images.githubusercontent.com/116098240/199101919-89576c63-0a1b-4cca-8294-bfd3a9c769bd.PNG) 


   - Si el **Checklist** indica que no se requiere participación de **PNF** o se recomienda realizar la prueba modular al interior del equipo se debe relacionar solo  el **Id del TestPlan**<br> <code>Ej: Evidencia VSTS:123455</code><br> 

  

**[🔗Mas Info: ¿Cómo creo un DOD correctamente?](https://grupobancolombia.visualstudio.com.mcas.ms/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/36701/%C2%BFC%C3%B3mo-creo-un-DOD-correctamente-)**<br><br> 

  

<h3 align="center">Realiza el Cuestionario dando click <a href="https://forms.office.com/r/h9SyxjQ6Jw">Aquí</h3> 

##### **[📺 Alineación Técnica Movilizadores Pruebas Continuas: Proceso de Pruebas, Soporte Pruebas Continuas, Cumplimiento Assessment](https://bancolombia-my.sharepoint.com.mcas.ms/personal/hamartin_bancolombia_com_co2/_layouts/15/stream.aspx?id=%2Fpersonal%2Fhamartin%5Fbancolombia%5Fcom%5Fco2%2FDocuments%2FGrabaciones%2FAlienaci%C3%B3n%20T%C3%A9cnica%20Movilizadores%20Pruebas%20Continuas%2D20221116%5F080936%2DGrabaci%C3%B3n%20de%20la%20reuni%C3%B3n%2Emp4)**<br> 

--- 

### ❕Items para tener en cuenta en los Pipelines 

  

- Verificar  que  se  ejecuten  las  pruebas  E2E  al  100%,  en  caso  de  que  tengan  pruebas automatizadas.<br> 

  

- Verificar que asocie el plan de pruebas en el Stage Manual Testy/o Exploratory Test en caso de que se hayan realizado pruebas manuales.<br> 

  

  - Si no hay participación de PNF ⮕ <code>Evidencia VSTS:123455</code><br> 

  

  - Si hay participación de PNF ⮕ <code>Evidencia  VSTS:123455 Concepto  PE  Seguridad  y/o Performance: 346547</code><br> 

  

- Si no existe Stage E2E, es porque la aplicación está en el **[listado de excepciones aprobadas por Curiosity](https://dev.azure.com/GrupoBancolombia/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/12026/Pruebas-E2E)**. Si no está en dicho listado, obligatoriamente debe existir la E2E.<br> 

  

--- 

## :keyboard: Actividad : 
1. Ingresa a la rama step5-proceso-de-pruebas

En el archivo actividad5.md da click en el ✏️ para editar y escribe una lista con el nombre de las 3 herramientas que se usan para los despliegues:

Ej. nombre herramienta

2. Haz commit, espera 30 segundos y refresca la pagina, ahora ingresa a la siguiente rama Step 6: Pruebas Unitarias

--- 


</details> 

  


<details id=6> 

<summary><h2>Step 6: Pruebas Unitarias</h2></summary> 

## ¿Que es una Prueba Unitaria? 

- Un test unitario es un pequeño programa que comprueba que una unidad de software tiene el comportamiento esperado. 

- Una prueba unitaria generalmente reemplaza a colaboradores externos con dobles de prueba (Stubs, Mocks, Fakes, Spy, Dummy) **[Ref:](https://martinfowler.com/bliki/TestDouble.html)** 

- Existen test unitarios isolados y sociables, pero lo importante es automatizar pruebas en todo momento según su contexto.<br> 

  

**[📺 Dojo Pruebas unitarias Basico](https://bancolombia.sharepoint.com/:v:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/Pruebas%20Unitarias/Java/Videos%20Dojos/Dojo%20Pruebas%20Unitarias%20en%20Java-Basico.mp4?csf=1&web=1&e=vIEi8B)**<br> 

  

  **[📺 Dojo Pruebas unitarias Avanzado](https://bancolombia.sharepoint.com/:v:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/Pruebas%20Unitarias/Java/Videos%20Dojos/Dojo%20Pruebas%20Unitarias%20en%20Java-Avanzado.mp4?csf=1&web=1&e=dPu1S8)**<br> 


--- 

## TDD - Test Driven Development<br> 

### Las tres leyes del TDD: 

1. No escribirás código de Producción sin antes escribir un test que falle.<br> 

2. No escribirás más de un test suficiente para fallar.<br> 

3. No escribirás más código del necesario para hacer pasar el Test ( Y el Refactoring???)<br> 

  

*By: Robert C. Martin* 

  

## TDD como herramienta de Diseño. 

TDD nos ayuda a tener mejor Código, y no más test innecesarios. Con los requisitos definidos realizamos una serie de pasos:  


1. Escogemos el requisito (ojalá sea de nuestro agrado). 

2. Escribimos un test que falle (Que no sea vacío en lo posible). 

3. Creamos la implementación mínima para que pase el test. 

4. Ejecutamos los test hasta que pasen. 

5. Refactorizamos para que quede mejor el código (Re-ejecutamos las pruebas)<br> 

  

*By:Kent Beck* 

  

--- 

## Principios FIRST:<br> 

  
**Fast:** La prueba debe ser corta, y no debe tardar mas de 3 seg en ejecución.<br>  

**Isolated:** debe funcionar por si sola, sin dependencias de otras pruebas o data<br> 

**Repeteable:** se debe ejecutar cuantas veces se requiera, en cualquier momento<br> 

**Self Validate:** requiere comprobarse automáticamente, sin intervención manual<br> 

**Timely:** deben ser oportunas, eficaces y con enfoque TDD.<br> 

  

--- 


**[📺 Portal de Conocimiento TI: Pruebas Unitarias](https://bancolombia.sharepoint.com/:f:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/Pruebas%20Unitarias?csf=1&web=1&e=KtTSJK)** 

  

## Cobertura exigida en Sonar: 


```  

70% New Code 

50% Legacy Code 

```  

- Es una herramienta útil para encontrar partes no probadas de un código.  

- La cobertura no es un buen indicador de que tan buenas son las pruebas.  

- La cobertura nunca debe ser un objetivo en si mismo, debería ser una buena practica del lado profesional del desarrollador 

  

--- 

## JAVA – En la práctica. 

- Para la ejecución de las pruebas unitarias generalmente se utilizan frameworks o librerías. 

- El framework que más se utiliza para Java es Junit. 

- Para determinar la cobertura de pruebas que tiene el proyecto una de las herramientas más usadas es Jacoco. 

- JUnit se puede agregar al Proyecto tanto como una librería propia del Proyecto o descargandola con ayuda de un gestor de tareas. 

  

--- 

## Assertions 

  

### testAssertEquals:  

``` 

@Test 

public void testAssertEquals() { 

   Assert.assertEquals(objetoEsperado,objetoObtenido); 

} 

``` 

### testAssertArrayEquals: 

``` 

@Test 

public void testAssertArrayEquals() { 

   byte[] expected = "trial".getBytes(); 

   byte[] actual = "trial".getBytes(); 

   assertArrayEquals("failure - byte array is not the same", expected, actua) 

} 

``` 

  

### testAssertNotNull: 

``` 

@Test 

public void testAssertNotNull() { 

   assertNotNull("should not be null", new object); 

} 

``` 

  

### testAssertNull: 

``` 

@Test 

public void testAssertNull() { 

   assertNull("should be null", null); 

} 

``` 

  

### testAssertTrue: 

``` 

@Test 

public void testAssertTrue() { 

   assertTrue(booleanEsperado); 

} 

``` 

### testAssertFalse: 

``` 

@Test 

public void testAssertTFalse() { 

   assertFalse(booleanEsperado); 

} 

``` 

  

### testAssertSame: 

``` 

@Test 

public void testAssertSame() { 

   Primas primas = new Primas(unEmpleado().crear()); 

   assertSame("Deben ser iguales", prima , prima) 

} 

``` 

### testAssertNotSame: 

``` 

@Test 

public void testAssertNotSame() { 

   Primas primas = new Primas(unEmpleado().crear()); 

   Salario salario = unSalario().crear(); 

   assertNotSame("No deben ser iguales", prima , salario) 

} 

``` 

  

### Annotations 

  

``` 

public class Annotations { 

   private List<String> lista; 

  

   @Before 

   public void init() { 

       lista = new ArrayList<>( 

           Arrays.asList("test1","test2") 

       ); 

   } 

  

   @Test 

   public void testItemsquals() { 

       Assert.assertEquals( 

         lista.get(0),lista.get(1) 

       ); 

   } 

  

   @After 

   public void finalize() { 

       lista.clear() 

   } 

} 

  

``` 

  

``` 

- @Before 

- @BeforeClass 

- @After 

- @AfterClass 

- @Test 

- @Ignore 

- @Test(timeout=500) 

- @Test(expected=IllegalArgumentException.class) 

- @Rule 

  

``` 

### Exceptions 

  

``` 

  

@Test(expected = NullPointerException.class) 

public void verificarSiNoEnvioTipoSalarioRetornaExcepcion() throws PrimasExcepcion, TipoSalExcepcion { 

    Primas prima = new Primas(unEmpleado().conTipoSalarioNull.crear()); 

    prima.calcularPrima(); 

} 

  

``` 

  

**Consideraciones:** 

- No se puede validar el mensaje de la excepción o el estado del objeto después de lanzada la excepción. 

- La prueba si en cualquier parte del método se lanza un NullPointerException, no necesariamente el que se quiere validar.  

  

---  

## Las tres partes del test **AAA:** **Arrange** (Preparar), **Act** (Actuar), **Assert** (Afirmar) 

  

### ANTES. 

  

``` 

  

@Test(expected = NullPointerException.class) 

public void validarDiasTrabajadosMenorQueCero() throws TipoSalExcepcion , PrimasExcepcion { 

    prima = new Primas(unEmpleado().conDiasTrabajadosMenorQueCero.crear()); 

    boolean rptaEsperada = false; 

    boolean rptaObtenida = prima.calcularPrima(); 

    String msjEsperado = DIASTRABANEGA; 

    String msjObtenido = prima.getError(); 

    Assert.assertEquals(msjEsperado,msjObtenido); 

    Assert.assertEquals(rptaEsperada,rptaObtenida); 

} 

  

``` 

  

### DESPUES. 

  

``` 

@Test  

public void validarDiasTrabajadosMenorQueCero() throws TipoSalExcepcion, PrimasExcepcion { 

  

//***********************************ARRANGE**********************************************// 

  

prima = new Primas(unEmpleado().conDiasTrabajadosMenosQueCero().crear()); 

  

boolean rptaEsperada = false; 

boolean rptaObtenidA; 

String msjEsperado = DIASTRABANEGA; 

String msjObtenido; 

  

//****************************************ACT*********************************************// 

  

rptaObtenida = prima.calcularPrima(); 

msjObtenido = prima.getError(); 

  

//***************************************ASSERT********************************************// 

  

Assert.assertEquals(msjEsperado,msjObtenido); 

Assert.assertEquals(rptaEsperada,rptaObtenida); 

  

} 

  

``` 

  

--- 

  

### Stack tecnológico 

  

![stack](https://user-images.githubusercontent.com/116098240/200019388-3fe56f3c-89c2-449a-b094-d0edc7fa981f.png) 

  

- La buena práctica es hacer uso de JUnit con ayuda del gestor de tareas. 

  

``` 

dependencies { 

  testImplementation group: 'junit', name: 'junit', version: '4.12' 

} 

  

``` 

  

- Las pruebas unitarias generalmente se ubican en una subcarpeta del proyecto. 

  

``` 

\--calculoSalario 

    | 

    \-- .gradle    

    \-- .idea 

    \-- gradle 

    \-- src 

        | 

        \-- main 

    *** \-- test *** 

        +-- build.gradle 

  

``` 

  

--- 

### :keyboard: Actividad : 

  

1. Dado el siguiente ejemplo en la rama **step6-pruebas-unitarias** en el archivo **actividad6.md** completa los Assertions, la respuesta debe quedar sin espacios.

  

```  

@Test 

   public void testAssertions() { 

      String str1 = new String ("abc"); 

      String str2 = new String ("abc"); 

      String str3 = null; 

      String str4 = "abc"; 

      String str5 = "abc"; 

		 

      int val1 = 5; 

      int val2 = 6; 

  

      String[] expectedArray = {"one", "two", "three"}; 

      String[] resultArray =  {"one", "two", "three"}; 

} 

  

``` 

  

**Ejemplo:** 

  

//Verifica que dos objetos son iguales 

assertEquals(); 

  

**Respuesta** 

  

assertEquals(str1,str2); **sin espacios**

  

--- 

2. Haz commit, espera 30 segundos, refresca la pagina e ingresa a la siguiente rama **Step 7: Pruebas de Aceptación** 

</details> 

  

  

<details id=7> 

<summary><h2>Step 7: Pruebas de Aceptación (BackEnd)</h2></summary> 

## Herramienta a usar<br> 

La herramienta promovida por el banco es  [KARATE FRAMEWORK](https://github.com/karatelabs/karate), la cual permite probar servicios Rest, SOAP y GraphQL. 

Karate basa sus pruebas en sintaxis Gherkin de BDD muy usada en Cucumber sin depender de ningún lenguaje de programación de propósito general. Utiliza DSL para describir las pruebas de API basadas en HTTP, se basa en la legibilidad, con diferentes reportes entendibles por cualquier actor que intervenga en las pruebas tanto de negocio, técnico y líder. 

  

<br> 

  

--- 

    

## Particularidades de Karate Framework: 

![imagen](https://user-images.githubusercontent.com/99279915/205955385-4035b475-76fb-4503-8a98-6379458e0b36.png) 


Karate Framework se ejecuta sobre la **JVM de Java**, no requiere implementar definiciones de pasos adicionales, ni código extra, también vale la pena señalar que JSON esta embebido en la sintaxis, de modo que puede expresar la carga útil y los datos esperados sin tener que usar comillas dobles y sin tener que encerrar los nombres de los campos JSON entre comillas. No hay necesidad de 'escape' de los caracteres como habría tenido que hacerlo en Java u otros lenguajes de programación. 

  

--- 

  

## Funcionalidades principales de Karate: 


- Setup inicial sencillo, rápido y directo. 

- BDD unificado desde un mismo fichero. No es necesario definir los steps en otras ubicaciones. 

- Pruebas simples, concisas, legibles y fáciles de mantener. 

- Posibilidad de utilizar clases Java para utilidades complejas o funciones de ayuda que facilita su depuración y mantenibilidad. 

- No se requieren conocimientos de programación avanzados. Acciones habituales sobre APIs implementadas mediante lenguaje natural. 

- Posibilidad de ejecutar pruebas en paralelo. 

- Reutilización de features pudiendo ser usadas como pre-condiciones o funciones de otros pruebas. 

- Implementación sencilla de aserciones complejos. 

- Soporte nativo para aserciones sobre JSON y XML. 

- Permite lectura de ficheros CSV (Data Driven Testing) 

- Motor de JavaScript integrado. 

- Importación de archivos csv o json con información. En cucumber, las variables están estáticas en una tabla. 

- Documentación y ejemplos completos. 

- Soporte websockets. 

- Informes HTML completos y muy visuales.<br> 

    

--- 

    

### Cuando se recomienda usar Karate: 

Karate es una buena opción cuando se desee disponer de una suite automatizada de pruebas sobre servicios REST y no se precisen acciones excesivamente complejas para realizar dichas comprobaciones. En caso contrario, karate pierte su claridad y sencillez, que es su mayor carácteristica, al poder ser comprendido tanto por la parte técnica como la de negocio. 

</br> 

  

--- 


<h2>Estructura de carpetas </h2> 

  

```java 

src/test/java 

    | 

    +-- karate-config.js 

    +-- logback-test.xml 

    +-- some-reusable.feature 

    +-- some-classpath-function.js 

    +-- some-classpath-payload.json 

    | 

    \-- animals 

        | 

        +-- AnimalsTest.java 

        | 

        +-- cats 

        |   | 

        |   +-- cats-post.feature 

        |   +-- cats-get.feature 

        |   +-- cat.json 

        |   \-- CatsRunner.java 

        | 

        \-- dogs 

            | 

            +-- dog-crud.feature 

            +-- dog.json 

            +-- some-helper-function.js 

            \-- DogsRunner.java 

``` 

--- 

    

<h2>Interoperabilidad con Java en pruebas con Karate:</h2> 


Realizar pruebas con Karate es más flexible de lo que parece. Al interior de las pruebas, podemos llamar a clases Java desarrolladas al exterior del feature, con la necesidad de realizar acciones como: Conexiones a BD, validación logs, transformaciones, entre lo finito que se puede hacer en java.   

A continuación, se muestra un ejemplo de conexión a BD y consulta por medio de Querys dentro del feature. Lo único externo es la clase DbUtils:    

![imagen](https://user-images.githubusercontent.com/99279915/206019772-e5bee020-5894-443c-b252-51c70c3f4ff2.png) 
   

--- 

    

### Websockets con Karate<br> 

Karate también tiene soporte integrado para websocket que se basa en la capacidad ASYNC. Las siguientes firmas de métodos están disponibles para obtener una referencia de websocket: 


- `karate.webSocket(url)` 

- `karate.webSocket(url, handler)` 

-  `karate.webSocket(url, handler, options)` - donde _options_ es un objeto JSON (o similar a un mapa) opcional que toma las siguientes claves opcionales: 

-- `subProtocol` - en caso de que el servidor lo espere 

-- `headers` - otro JSON de pares clave-valor 

-- `maxPayloadSiz` - este valor predeterminado es 4194304 (bytes, alrededor de 4 MB)<br> 

  

Estos iniciarán un cliente websocket para la `url` y opcional ``subProtocol``. Si se proporciona una función ``handler`` devuelve un booleano. Se necesita una función de controlador solo si tiene que ignorar otro tráfico entrante. Si necesita encabezados personalizados para el protocolo de enlace de websocket, use JSON como último argumento.<br><br> 

  

### Ejemplo 


```java 

* def handler = function (msg) {return msg.startsWith ( 'hola' )} 

* def socket = karate.webSocket (demoBaseUrl + '/ websocket' , handler) 

* socket.send ( 'Billie' ) 

* def result = socket .escucha (5000) 

* resultado de la coincidencia == '¡hola Billie!' 

``` 

<br> 

    
--- 


### Configuración archivo karate-config.js<br> 

Este archivo nos permite configurar diferentes parámetros a nivel general de nuestro proyecto sobre karate, tales como: ambientes, timeouts, entre otros: 

  

```js 

function fn() {    

  var env = karate.env; // get java system property 'karate.env' in  build.gradle 

  karate.log('karate.env system property was:', env); 

  if (!env) { 

    env = 'dev'; // a custom 'intelligent' default 

  } 

  var config = { // base config JSON 

    urlBase: 'https://example.dev', 

  }; 

  if (env == 'dev') { 

    // over-ride only those that need to be 

    config.urlBase = 'https://example.dev'; 

  } else if (env == 'cer') { 

    config.someUrlBase = 'https://example.cer'; 

  } 

  // don't waste time waiting for a connection or if servers don't respond within 5 seconds 

  karate.configure('connectTimeout', 5000); 

  karate.configure('readTimeout', 5000); 

  return config; 

} 

``` 

  

- Para poder ejecutar las pruebas según el ambiente parametrizado, en este caso 'dev' o 'cer' lo pueden hacer por medio del comando de gradle: 

  

```gradle 

gradlew clean test -i -Dkarate.env=dev 

``` 

  

   ó 

  

```gradle 

gradlew clean test -i -Dkarate.env=cer 

``` 

<br> 

  
  **Nota**: Para poder trabajar de esta manera, deben tener la configuración del build.gradle correcta con el parámetro _karate.env_ 

    

--- 

    

## RabbitMQ con Karate. 

En arquitecturas orientadas a eventos es muy común que necesitemos interactuar con broker de mensajería como RabbitMQ, para realizar test sobre estos servicios podemos aprovechar la capacidad que tiene Karate para interactuar con Java, siendo así posible utilizar el [Java Client de rabbitMQ](https://www.rabbitmq.com/api-guide.html) que nos permite realizar conexiones y operaciones sobre el broker. 
   

![Items](https://user-images.githubusercontent.com/116098240/207144617-895b5348-a208-4be1-8f3a-a55182dde6e7.jpg) 
 

A continuación se tienen dos escenarios los cuales interactúan con RabbitMQ. 


- El primer escenario requiere probar el método GET de un servicio, el cual se encarga de leer mensajes en una cola RabbitMQ y retornarlo como objeto Json. 

<br> 

    Para realizar esta prueba se inserta un mensaje directamente a la cola RabbitMQ para que el servicio pueda leerlo al ser ejecutado el método GET. 

  

```java 

Feature: Read messages from RabbitMQ queue from API Rest 

  

  Background: 

    * def config = { host: '#(host)' , port: '#(port)', username: '#(username)', password: '#(password)', queueName: '#(queueName)'} 

    * url 'http://localhost:9001/v1/api' 

  

  Scenario: Send request GET to rest api to read message from RabbitMQ queue 

    * def event = {"application":"demo","type":"success","severity":"low","message":"test send message from karate"} 

    * def utilsRabbit = Java.type('co.com.jsierra.karateapitest.utils.UtilsRabbit') 

    * def payload = karate.toBean(event, 'co.com.jsierra.karateapitest.models.Event') 

    Given utilsRabbit.send( config , payload) 

    And path '/queue' 

    When method get 

    Then status 200 

    And match response == event 

``` 

- En el segundo escenario se requiere probar el método POST de un servicio, el cual se encarga de escribir mensajes en una cola RabbitMQ. 

  

    Para realizar esta prueba se ejecuta el método POST y luego leemos el mensaje directamente desde la cola RabbitMQ. 

  

```java 

Feature: Send messages to RabbitMQ queue from API Rest 

  

  Background: 

    * def config = { host: '#(host)' , port: '#(port)', username: '#(username)', password: '#(password)', queueName: '#(queueName)'} 

    * url 'http://localhost:9001/v1/api' 

  

  Scenario: Send request POST to the API Rest to write message in the queue 

    * def event = {"application":"demo","type":"success","severity":"low","message":"test send message from karate"} 

    * def utilsRabbit = Java.type('co.com.jsierra.karateapitest.utils.UtilsRabbit') 

    Given request event 

    And path '/queue' 

    When method post 

    Then status 200 

    * def msg = utilsRabbit.receive(config) 

    And match event == karate.toJson(msg) 

``` 

  

Para ver el ejemplo completo debes ir al siguiente repositorio en el proyecto ***Karate_Api_Test***:<br> 

https://github.com/jsierra93/karate-test-rabbitmq 

  

--- 

  

- Para ver más información sobre Karate y su utilización, se recomienda leer [el árticulo respectivo en la wiki](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10100/Pruebas-Integraci%C3%B3n-(Acceptance-Test-Backend)-karate#), en el que tambien hay ejemplos sobre su utilización para diferentes tipos de métodos.

- Puedes ver los videos  [Pruebas Aceptacion Backend - Asíncronos](https://bancolombia.sharepoint.com/:f:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/Pruebas%20de%20aceptacion/Videos%20Dojos,%20Meetups,%20Webinar,%20Alineaciones%20tecnicas/Pruebas%20Aceptacion%20Backend%20-%20%20As%C3%ADncronos?csf=1&web=1&e=2mT8cW) y el [Demo de Karate](https://github.com/anfruiz/karate-demo).

	 


## :keyboard: Actividad : 

  

1. En el archivo  **actividad8.md** completa el **karate-config**. 

2. haz commit, espera un minuto refresca la pagina e ingresa a la siguiente rama **step9-pruebas-de-aceptacion-front**. 

  

</details> 

  

  

<details id=8> 

<summary><h2>Step 8: Pruebas de Aceptación (FrontEnd)</h2></summary> 

  

## 1. Introducción 

En esta sección nos centraremos en abarcar las pruebas que se requieren ejecutar para garantizar la calidad de los flujos de usuarios, los inputs de los usuarios y acciones del front de las aplicaciones web modernas que se despliegan en el banco. 

  

Es muy importante aclarar que estas pruebas se realizan en componentes reales, ya desplegados en ambientes Pre-Productivos y comunmente se conocen como _Acceptance Test_. Cuando nos referimos a este tipo de pruebas en el front de nuestra app, estas cumplen con los siguientes principios: 

- Son orientadas a todos los componentes menos el backend 

- Por cada criterio de aceptación debe existir al menos un test 

- Probar código de la app, de forma rápida y automática, son muy apropiadas para las regresiones diarias 

  

<br/> 

  

_____ 

  

## 2. Herramienta 

El **framework** que utilizaremos para realizar las pruebas de aceptación en el front es [PLAYWRIGHT](https://github.com/microsoft/playwright) desarrollada por Microsoft. 

  

<center> 

  

![image](https://user-images.githubusercontent.com/99279915/208530255-e624e495-6d0d-4d55-9adc-a31852818e9b.png) 

_Fig.1. Logo de Playwright_ 


</center> 

  

Playwright es una librería de Node.js desarrollada por Microsoft para automatizar los flujos de una aplicación web en Chromium, Firefox y WebKit de forma confiable y rápida. 


Playwright está diseñada para automatizar las Single Page Apps (SPA) y Progressive Web Apps que utilizan todas las capacidades que un navegador ofrece actualmente. 


Algunas características son: 

- Escenarios con múltiples páginas. 

- Auto-waiting de los elementos del DOM hasta que estén listos para interactuar con ellos como click, escribir. 

- Emular dispositivos móviles, geolocalización y permisos. 

- Compatible con los siguientes lenguajes: 

     

<center> 

  

![image](https://user-images.githubusercontent.com/99279915/208530386-16cb1aab-2314-44c3-a641-e6e41ed1fb9d.png) 

_Fig.2. Lenguajes compatibles con Playwright_ 

  

</center> 

  

  

## 2.1 Runner 

[Playwright Test Runner](https://github.com/microsoft/playwright-test) fue creado para satisfacer aquellas necesidades que se tienen al momento de ejecutar pruebas E2E o en nuestro caso, de **aceptación**. 

  

Con la implementación de este runner podemos: 

- Ejecutar los test en todos los browsers: 

    - Chromium (Chrome y Edge). 

    - Firefox. 

    - Webkit (Safari). 

- Ejecutar en paralelo. 

- Tener un contexto aislado desde el principio sin configuraciónes adicionales. 

- Capturar videos y screenshots al momento de fallas. 

- Integrar Page Object Model (POM) como fixtures. 

- Solo re-ejecutar los test fallidos sin necesidad de ejecutar todo la suite de pruebas. 

  

### 2.2 Instalación 

Para descargar las librerías de playwright solo basta con ejecutar el siguiente comando desde el proyecto de la aplicación, donde **playwright** comprende todo el core de la librería y los emuladores de los diferentes browsers y **@playwright/test** contiene las características del runner: 

``` npm 

npm i -D playwright @playwright/test 

``` 

Al finalizar la descarga de las dependencias, el archivo _package.json_ debe quedar con las siguientes líneas:  

  

``` json 

"devDependencies": { 

    "@playwright/test": "^1.20.2", 

    "playwright": "^1.20.2" 

} 


``` 

### 2.3 Estructura de las carpetas 

```node 
        package.json 

        playwright.config.ts 

        global-setup.ts 

        src 

        acceptancetest 

            | 

            \--src 

            |  | 

            |  \--pages 

            |  |  | 

            |  |  +-- HomePage.ts 

            |  |   

            |  \--resources 

            |     | 

            |     +--Login.json 

            | 

            \--test 

            | 

            +-- Home.spec.ts 

  ``` 


### 2.4 Configuración archivo playwright.config.ts 

Por medio de este archivo se pueden realizar configuraciones generales para los test como especificar timeouts, cuándo realizar videos o screenshots, entre otros. 

A continuación, te mostramos la configuración básica que debe tener el proyecto para ejecutar los test. 


```typescript 

import { PlaywrightTestConfig, devices } from "@playwright/test"; 

  

const config: PlaywrightTestConfig = { 

  testMatch: "*.spec.ts", 

  reporter: [ 

    ["list"], 

    ["junit", { outputFile: "reports/xmlReport/results.xml" }], 

    ["json", { outputFile: "reports/jsonReport/results.json" }], 

    ["html", { outputFolder: "reports/htmlReport", open: "never" }], 

  ], 

  timeout: 600000, 

  retries: 1, 

  fullyParallel: true, 

  use: { 

    screenshot: "only-on-failure", 

    video: "retry-with-video", 

  }, 

}; 

export default config; 


``` 


Para más detalle de todos los parámetros que se pueden configurar, ingresar a [documentación](https://playwright.dev/docs/test-configuration#testing-options) de playwright. 


## 3. Demo en implementaciones 

### 3.1 Creación de un test 

#### 3.1.1 Codegen 

Playwright trae consigo el comando codegen que permite crear un test por medio de Record and Play. Para utilizarlo solo basta con ejecutar el siguiente comando desde la terminal en la raíz del proyecto: 


```
npx playwright codegen <url> 

``` 

Después de ejecutar este comando aparecerá en pantalla un navegador con la url especificada y una ventana donde se va escribiendo el test: 


<center> 


![image](https://user-images.githubusercontent.com/99279915/208530534-1e513d85-8276-46c0-aa26-5a2d134d229b.png) 

_Fig.3. Playwright codegen_ 


</center> 

  

______ 

  
#### 3.1.2 Manual 

Por este modo simplemente es empezar a crear el test escribiendo código desde cero. Se debe tener en cuenta que playwright utiliza CSS selectors para encontrar los elementos e interactuar con los mismos. 

  
##### 3.1.2.1 CSS Selectors 


<center> 

|**Selector**|**Ejemplo**|**Descripción**| 
|--|--|--| 
| .class | .title | Selecciona los elementos que tengan la clase 'title' | 
| .class1.class2 | .btn.primary | Selecciona los elementos que tengan las clases 'btn' y 'primary' | 
| .class1 .class2 | .container .btn | Selecciona los elementos con la clase 'btn' que sean descendientes del elemento con clase 'container' | 
| #id | #simulate | Selecciona el elemento con el id 'simulate' | 
| element | span | Selecciona los elementos 'span' | 
| element.class | div.container | Selecciona el elemento 'div' que tenga la clase 'container' | 
| element > element | div > p | Selecciona los elementos 'p' que son hijos del elemento 'div' | 
| [attribute='value'] | [data-test='firstname'] | Selecciona los elementos que tengan el atributo 'data-test' con el valor 'firstname' | 


</center> 


  
### 3.2 Page Object Model (POM) 

En playwright se pueden implementar patrones de diseño, para nuestro caso vamos a usar el patrón POM con el fin de tener el proyecto más organizado y poderle dar mantenibilidad de forma más fácil. 

  

#### 3.2.1 Ejemplo Page 

```typescript 

import { Locator, Page } from "playwright"; 

  

export class LogInPage { 

  readonly page: Page; 

  readonly usernameInput: Locator; 

  readonly passwordInput: Locator; 

  readonly logInButton: Locator; 

  readonly logInErrorMessage: Locator; 

  

  constructor(page: Page) { 

    this.page = page; 

    this.usernameInput = page.locator('[data-test="username"]'); 

    this.passwordInput = page.locator('[data-test="password"]'); 

    this.logInButton = page.locator('[data-test="login-button"]'); 

    this.logInErrorMessage = page.locator('.error-message-container'); 

  } 

  

  async navigate(url) { 

    await this.page.goto(url); 

  } 

  

  async logIn(username, password) { 

    await this.usernameInput.fill(username); 

    await this.passwordInput.fill(password); 

    await this.logInButton.click(); 

  } 

  

  async getErrorMessageClassAttribute() { 

    return await this.logInErrorMessage.getAttribute("class"); 

  } 

} 

  
``` 

  

#### 3.2.2 Sin POM 

``` typescript 

test.beforeEach(async ({ page }) => { 

  await page.goto("https://www.saucedemo.com"); 

  await page.fill('[data-test="username"]', "standard_user"); 

  await page.fill('[data-test="password"]', "secret_sauce"); 

  await page.click('[data-test="login-button"]'); 

  await page.click('[data-test="add-to-cart-sauce-labs-backpack"]'); 

  await page.click('[data-test="add-to-cart-sauce-labs-bike-light"]'); 

  await page.click('[data-test="add-to-cart-sauce-labs-bolt-t-shirt"]'); 

  await page.click(".shopping_cart_link"); 

}); 

  

test(`Given I was logged in demosauce 

    When I add two products to cart 

    Then I will see two items in the cart`, async ({ page }) => { 

  const items = await page.$$(".cart_item"); 

  expect(items).toHaveLength(3); 

}); 

  

``` 

  

#### 3.2.3 Con POM 

```typescript 

const cartTest = base.extend<{ cartPage: CartPage }>({ 

  cartPage: async ({ page }, use) => { 

    const logInPage = new LogInPage(page); 

    const homePage = new HomePage(page); 

    const cartPage = new CartPage(page); 

    await logInPage.navigate("/"); 

    await logInPage.logIn("standard_user", "secret_sauce"); 

    await homePage.goToCart(); 

    await use(cartPage); 

  }, 

}); 

  

cartTest( 

  `Given I was logged in demosauce 

    When I add two products to cart 

    Then I will see two items in the cart`, 

  async ({ cartPage }) => { 

    cartTest.expect(await cartPage.getCartItems()).toHaveLength(3); 

  } 

); 

  

cartTest( 

  `Given I was logged in demosauce 

    And I add two products to cart 

    When I remove a product from the cart 

    Then I will see one item in the cart`, 

  async ({ cartPage }) => { 

    cartTest.expect(await cartPage.getCartItems()).toHaveLength(3); 

    await cartPage.removeItem("bolt-t-shirt"); 

    cartTest.expect(await cartPage.getCartItems()).toHaveLength(2); 

  } 

); 

  

cartTest( 

  `Given I had items in the cart 

    When I finish the purchase 

    Then I will see the message 'THANK YOU FOR YOUR ORDER'`, 

  async ({ cartPage }) => { 

    cartPage.completePurchase(); 

  

    cartTest 

      .expect(await cartPage.getMessage()) 

      .toBe("THANK YOU FOR YOUR ORDER"); 

  } 

); 

``` 
  
### 3.3 Uso del Storage 
 

Playwright al ser un fork de [puppeteer](https://pptr.dev), tiene la característica de poder interactuar con las cookies, el sessionStorage y localStorage del navegador; permitiendo que podamos cargar los test con estas memorias ya configuradas en un archivos JSON y ahorrarnos algunos pasos para llegar al punto que realmente queremos probar. 


Para crear el JSON, se debe ejecutar el siguiente comando, y hacer los pasos que hacen que se creen los items en las memorias: 

```npm 

npx playwright open --save-storage=acceptancetest/src/resources/Login.json <url> 

``` 

  

Para utilizar el archivo con codegen se ejecuta el siguiente comando: 

```npm 

npx playwright codegen --load-storage=acceptancetest/src/resources/Login.json <url> 

``` 

  

Y finalmente para utilizarlo en los test, se debe agregar las siguientes líneas de código: 

  

```typescript 

test.use({ 

   storageState: "src/resources/Login.json", 

}); 

``` 

  

### 3.4 Fixtures 

  

Los fixtures son usados para crear un ambiente donde le entrega lo que necesita a cada test para su ejecución. Es importante resaltar que cada fixture es aislado, lo que permite que se agrupen los test por su finalidad y no por su configuración. 

  

A continuación se puede observar la diferencia entre un test con la forma tradicional vs un test utilizando fixtures: 

  

#### 3.4.1 Sin Fixture 

  

```typescript 

import { test }  from '@playwright/test'; 

import { TodoPage } = from './todo-page'; 

  

  beforeEach(async ({ page }) => { 

    const todoPage = new TodoPage(page); 

    await todoPage.goto(); 

    await todoPage.addToDo('item1'); 

    await todoPage.addToDo('item2'); 

  }); 

  

  afterEach(async () => { 

    await todoPage.removeAll(); 

  }); 

  

  test('should add an item', async () => { 

    await todoPage.addToDo('my item'); 

    // ... 

  }); 

  

  test('should remove an item', async () => { 

    await todoPage.remove('item1'); 

    // ... 

  }); 

}); 

```

---
  
#### 3.4.2 Con Fixture 

  

```typescript 

import { test as base } from '@playwright/test'; 

import { TodoPage } from './todo-page'; 

  

const test = base.extend<{ todoPage: TodoPage }>({ 

  todoPage: async ({ page }, use) => { 

    const todoPage = new TodoPage(page); 

    await todoPage.goto(); 

    await todoPage.addToDo('item1'); 

    await todoPage.addToDo('item2'); 

    await use(todoPage); 

    await todoPage.removeAll(); 

  }, 

}); 

  

test('should add an item', async ({ todoPage }) => { 

  await todoPage.addToDo('my item'); 

  // ... 

}); 

  

test('should remove an item', async ({ todoPage }) => { 

  await todoPage.remove('item1'); 

  // ... 

}); 

```   
---

## 4. Playwright en proyectos Angular 

  

Los proyectos de pruebas de aceptación estarán alojados en el repositorio donde se encuentra el código fuente de la aplicación, por ende, estarán dentro de la estructura de los proyectos en angular, u otro framework como lo puede ser React, Vue, o proyectos web en .NET, python, entre otros.  


Resaltaremos el ejemplo en Angular, ya que la mayoria de aplicaciones web en el banco, estan en angular desde versiones 8 hasta las 11 (esto al 28/07/2021). 

### 4.1. Estructura de carpetas en proyecto Angular:   

``` 

acceptancetest 

    | 

    \--src 

    |  | 

    |  \--pages 

    |  |  | 

    |  |  +-- HomePage.ts 

    |  |   

    |  \--resources 

    |     | 

    |     +--Login.json 

    | 

    \--test 

      | 

      +-- Home.spec.ts 

coverage 

dist 

node_modules 

src 

.browserlistrc 

.editorconfig 

.gitignore 

angular.json 

jest.config.js 

package-lock.json 

package.json 

playwright.config.ts 

README.md 

setup-jest.ts 

tsconfig.app.json 

tsconfig.base.json 

tsconfig.json 

tsconfig.spec.json 

tslint.json 


``` 

  

Nota: En el archivo jest.config.js se debe agregar el valor `'<rootDir>/acceptancetest/',` a la propiedad: `testPathIgnorePatterns` esto con el fin de que las pruebas unitarias no choquen con las pruebas de aceptación en el front. 


Nota2: Se tienen dos maneras de trabajar con los proyectos en Angular 

1. Podemos tener el archivo de propiedades `playwright.config.ts` en la raíz del proyecto angular, y tener las dependencias `@playwright/test` y `playwright` en el package.json principal de angular. En la carpeta AcceptanceTest solo deberíamos tener las pruebas y sus archivos adicionales según necesidades. 

  

2. También podemos tener un proyecto aparte para las pruebas de aceptacion alojado en la carpeta `acceptancetest` con su respectivo **package.json** y **playwrigh.config.ts**. Es buena idea ya que el bundle de descarga será muy pequeño, pero más adelante, lo más probable es que se requiera en el proyecto angular, para el manejo de la `coverage` con el plugin de instabul, entonces se recomienda la #1.  

  

### 4.2. package.json con las dependencias y scripts de playwright: 

  

```json 

{ 

  "name": "app-recovered-advanced", 

  "version": "1.0.0", 

  "scripts": { 

    "ng": "ng", 

    "start": "ng serve", 

    "build": "ng build", 

    "test": "jest --coverage --reporters=default --reporters=jest-junit", 

    "test:coverage": "jest --coverage", 

    "test:watch": "jest --watch", 

    "acceptancetest": "npx playwright test", 

    "lint": "ng lint", 

    "e2e": "ng e2e", 

    "postinstall": "ngcc" 

  }, 

  "private": true, 

  "dependencies": { 

    "@angular/animations": "~10.0.3", 

    "@angular/cdk": "^10.1.3", 

    "@angular/common": "~10.0.3", 

    "@angular/compiler": "~10.0.3", 

    "@angular/core": "~10.0.3", 

    "@angular/forms": "~10.0.3", 

    "@angular/material": "^10.1.3", 

    "@angular/platform-browser": "~10.0.3", 

    "@angular/platform-browser-dynamic": "~10.0.3", 

    "@angular/router": "~10.0.3", 

    "ngx-toastr": "^13.0.0", 

    "rxjs": "~6.5.5", 

    "tslib": "^2.0.0", 

    "zone.js": "~0.10.3" 

  }, 

  "devDependencies": { 

    "@angular-devkit/build-angular": "~0.1000.2", 

    "@angular/cli": "~10.0.2", 

    "@angular/compiler-cli": "~10.0.3", 

    "@ngneat/spectator": "^6.1.2", 

    "@playwright/test": "^1.13.0", 

    "@testing-library/angular": "^10.6.0", 

    "@testing-library/jest-dom": "^5.12.0", 

    "@testing-library/user-event": "^13.1.9", 

    "@types/jest": "^26.0.16", 

    "@types/node": "^12.11.1", 

    "codelyzer": "^6.0.0", 

    "jest": "^26.6.3", 

    "jest-cli": "^26.6.3", 

    "jest-html-reporters": "^2.1.2", 

    "jest-junit": "^11.1.0", 

    "jest-preset-angular": "^8.3.2", 

    "jest-sonar": "^0.2.11", 

    "jest-watch-typeahead": "^0.6.1", 

    "playwright": "^1.13.0", 

    "ts-node": "~8.3.0", 

    "tslint": "~6.1.0", 

    "typescript": "~3.9.5" 

  } 

} 

``` 

  

- Para ver más información sobre Playwright, como ejemplos de configuración en los pipelines de Azure DevOps del Banco, se recomienda [leer el artículo de la wiki, que es una versión más completa de este módulo](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/25293/Pruebas-de-Aceptaci%C3%B3n-(Frontend)) 
- Aquí Puedes encontrar los [Alineaciones Tecnicas y Dojos de Pruebas Aceptación Front - Playwright](https://bancolombia.sharepoint.com/:f:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/Pruebas%20de%20aceptacion/Videos%20Dojos,%20Meetups,%20Webinar,%20Alineaciones%20tecnicas/Pruebas%20Aceptaci%C3%B3n%20Front%20-%20Playwright?csf=1&web=1&e=mz9gGY) y el [Demo](https://github.com/anfruiz/playwright-demo)


---
## :keyboard: Actividad : 
 
1. En el archivo actividad8.md completa las partes faltantes de la pieza de codigo.
---
  
</details> 

  

  

<details id=9 open> 

<summary><h2>Step 9: Pruebas de Aceptación (Flutter)</h2></summary> 

# 1. Introducción 

En este módulo, hablaremos de cómo realizar pruebas de aceptación a las aplicaciones móviles desarrolladas por medio de flutter; utilizando el paquete de **integration_test** el cual hace parte del SDK de flutter. 


## 1.1 Dart 

- Lenguaje open source creado por Google.  

- Es un lenguaje orientado a objetos. 

- Lenguaje base para trabajar con Flutter 

  

## 1.2 Flutter 

- Es un Framework de código abierto desarrollado por Google para crear aplicaciones nativas de forma fácil, rápida y sencilla. 

- Su principal ventaja radica en que genera código 100% nativo para cada plataforma, con lo que el rendimiento y la UX es totalmente idéntico a las aplicaciones nativas tradicionales. 

- Flutter es un crossplatform y trae consigo los beneficios que traen otras herramientas crossplatform, por ejemplo, con unas pocas líneas de código las implementaciones que se realicen pueden servir tanto para Android como para iOS 

- Flutter trae consigo un referente tecnológico como lo es Google  

  

# 2. Integration_Test 


Para hablarlo en términos simples, integration_test es un paquete de prueba para aplicaciones de flutter, adicional a esto se puede usar para probar varios elementos de la interfaz de usuario permitiendo escribir pruebas automatizadas las cuales son llamadas en Flutter pruebas de integración y desde hoy en adelante en nuestro contexto Bancolombia llamaremos pruebas de Aceptación. 

  

## 2.1 Instalación 


Como primer paso, se debe agregar la dependencia para descargarla en el pubspec.yaml, como se muestra a continuación: 

  

```yaml 

dev_dependencies: 

  integration_test: 

    sdk: flutter 

  flutter_test: 

    sdk: flutter 

  test: any 

``` 


Una vez agregadas las dependencias, se debe ejecutar el comando _**flutter pub get**_, con el fin de actualizar las nuevas dependencias agregadas.


## 2.2 Estructura de carpetas en proyecto Flutter 

Siguiendo un poco la estructura de capas de screenplay, se propone la siguiente estructura de carpetas:  


```

integration_test 

    | 

    \--interactions 

    |    | 

    |    +--Enter.dart 

    | 

    \--questions 

    |    | 

    |    +--ValidateText.dart 

    | 

    \--tasks 

    |    | 

    |    +--Login.dart 

    | 

    \--test 

    |    | 

    |    +--LogInTest.dart 

    |    +--TransferTest.dart 

    |    +--MainTest.dart 

    | 

    \--userinterface 

    |    | 

    |    +--LogInPage.dart 

ios 

lib 

node_modules 

pubspec.yaml 


``` 


## 2.3 Ejemplo interaction 

Representa una interaction directa del usuario con la interfaz como ingresar datos en campos o dar clics en botones. Flutter Driver trae por defecto muchas actions sobre la interfaz, por tanto, no siempre es necesario crear nuevas Actions.  

  

Un ejemplo de una interaction se representa a continuación: 

  
```dart 

import 'package:flutter_test/flutter_test.dart'; 

  

class Enter{ 

  const Enter(this.finder, this.tester); 

  final Finder finder; 

  final WidgetTester tester; 

  

  static Future<void> textWith(tester, Finder finder, String text) async { 

    await tester.ensureVisible(finder); 

    await tester.tap(finder); 

    await tester.enterText(finder, text); 

    await tester.pumpAndSettle(); 

  } 

} 

``` 

  

## 2.4 Ejemplo question 

Es la capa donde se especifica el assert de las pruebas. Donde se verifican los resultados de las operaciones realizadas en las capas anteriores. Un ejemplo se presenta en la siguiente imagen: 

  

```dart 

import 'package:flutter_test/flutter_test.dart'; 

  

class ValidateText{ 

  const ValidateText(this.finder, this.tester); 

  final Finder finder; 

  final WidgetTester tester; 

  

  static Future<void> widgetText(tester, Finder finder) async { 

    await tester.ensureVisible(finder); 

    expect(finder, findsOneWidget); 

    await tester.pumpAndSettle(); 

  } 

} 

``` 

  

## 2.5 Ejemplo tasks 

Son tareas a un nivel de granularidad más alto al de clicks y selects. Representan operaciones importantes para llegar a cumplir una meta (lo que se está probando). Ejm consultar saldo, hacer transferencia, completar un pago, matricular cuentas.  

  

Las tareas, al ser operaciones, son verbos y así mismo serán nombrados, además implementan de Task. Es necesario aquí, aplicar el principio de única responsabilidad, es decir, una tarea es representada por una clase, una clase no debe ser usada para representar 2 o más tareas. Un ejemplo de una tarea se presenta a continuación: 

  

```dart 

import 'package:flutter_test/flutter_test.dart'; 

  

import '../interactions/Enter.dart'; 

import '../userinterface/LoginPage.dart'; 

  

class Login{ 

  const Login(this.tester); 

  final WidgetTester tester; 

  

  static Future<void> withCredentials(tester, String correo, pass) async { 

    await Enter.textWith(tester, emailText, correo); 

    await Enter.textWith(tester, passwordText, pass); 

    await tester.tap(btnContinuar); 

    await tester.pumpAndSettle(const Duration(seconds: 5)); 

  } 

} 

``` 

  

## 2.6 Ejemplo userinterface 

Son las clases que mapean los componentes de una interfaz de usuario. Sólo deben realizar ese mapeo, no tienen comportamiento. 

  

``` dart 

import 'package:flutter/cupertino.dart'; 

import 'package:flutter_test/flutter_test.dart'; 

  

final emailText = find.byKey(Key('txtCorreo')); 

final passwordText = find.byKey(Key('txtPassword')); 

final btnContinuar = find.byKey(Key('btnContinuar')); 

final lbBienvenido = find.byKey(Key('lbBienvenido')); 

final txtWrongPass = find.text('Su contraseña debe ser al menos de 5 caracteres'); 

``` 

  

## 2.6 Ejemplo test 

  
### 2.6.1 LoginTest.dart 


```dart 

import 'package:flutter/cupertino.dart'; 

import 'package:flutter_test/flutter_test.dart'; 

import 'package:integration_test/integration_test.dart'; 

import 'package:linea_base_automatizacion_flutter/main.dart' as app; 

  

import '../interactions/Enter.dart'; 

import '../questions/ValidateText.dart'; 

import '../tasks/Login.dart'; 

import '../userinterface/LoginPage.dart'; 

  

void main() { 

  

  IntegrationTestWidgetsFlutterBinding.ensureInitialized().testTextInput.register(); 

  

  testWidgets('verify authenticacion correct credentials', (WidgetTester tester) async { 

    app.main(); 

    await tester.pumpAndSettle(const Duration(seconds: 2)); 

    await Login.withCredentials(tester, "pepitoperez@mail.com", "1739235"); 

    await ValidateText.widgetText(tester, lbBienvenido); 

  }); 

} 

``` 

  

### 2.6.2 MainTest.dart 

```dart 

import 'package:integration_test/integration_test.dart'; 

import 'LoginTestCorrect.dart' as LoginTestCorrect; 

import 'LoginTestWrongCredentials.dart' as LoginTestWrongCredentials; 

  
void main() { 

  LogInTest.main(); 

  TransferTest.main(); 

} 

``` 

La finalidad de tener el **MainTest.dart** es poder unificar todos los test en un solo archivo, esto con la finalidad de que a la hora de compilar el proyecto para las pruebas se puedan ejecutar todas al tiempo. 

  

# 3. Configuración proyecto 

Para poder ejecutar las pruebas desarrolladas con _**integration_test**_ en firebase test lab primero se debe realizar unas configuraciones en el proyecto de flutter. 

## 3.1 Configuración Android 

- Se debe crear un archivo de prueba de instrumentación en el directorio **android/app/src/androidTest/java/co/com/bancolombia/myapp/** (reemplazar myapp con el nombre de la aplicación). Este archivo se puede llamar `MainActivityTest.java` con el siguiente contenido:


```java 

package co.com.bancolombia.myapp; 

import androidx.test.rule.ActivityTestRule; 

import dev.flutter.plugins.integration_test.FlutterTestRunner; 

import org.junit.Rule; 

import org.junit.runner.RunWith; 

  

@RunWith(FlutterTestRunner.class) 

public class MainActivityTest { 

  @Rule 

  public ActivityTestRule<MainActivity> rule = new ActivityTestRule<>(MainActivity.class, true, false); 

} 

``` 


- Agregar al build.gradle ubicado en la ruta **android/app/build.gradle** las siguientes dependencias: 



```gradle 


android { 

  ... 

  defaultConfig { 

    ... 

    testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner" 

  } 

} 

  

dependencies { 

    testImplementation 'junit:junit:4.12' 

  

    // https://developer.android.com/jetpack/androidx/releases/test/#1.2.0 

    androidTestImplementation 'androidx.test:runner:1.2.0' 

    androidTestImplementation 'androidx.test.espresso:espresso-core:3.2.0' 

} 

``` 

Para más información visitar el siguiente link: [Configuración Android](https://github.com/flutter/flutter/tree/master/packages/integration_test#android-device-testing)  

  
## 3.2 Configuración IOS 

- Se debe abrir `ios/Runner.xcworkspace` en Xcode.  

- Una vez abierto, se crea un test target por medio de la ruta `File > New > Target...` y se selecciona `Unit Testing Bundle`. 

- Cambiar el `Product Name` por `RunnerTests`. Asegurarse de que la opción `Target to be Tested` esté configurada `Runner` y que el lenguaje esté en la opción `Objective-C`. La configuración quedaría como en la siguiente imagen: 

  

![image](https://user-images.githubusercontent.com/99279915/208587268-0a16b3c9-fa61-474e-8042-14ee5d2344f8.png) 

  

Asegurarse que **iOS Deployment Target** de `RunnerTests` dentro de la sección **Build Settings** esté igual que la de `Runner`. 

  

- Agregar las siguientes líneas en el archivo `ios/Podfile` dentro del `Runner` target existente. 

  

```ruby 

target 'Runner' do 

  # Do not change existing lines. 

  ... 


  target 'RunnerTests' do 

    inherit! :search_paths 

  end 

end 

``` 


- Finalmente en Xcode, adicionar dentro de RunnerTests un archivo llamado `RunnerTests.m` en caso de que no exista. O si ya existe reemplaza su contenido con las siguientes líneas: 

  

```objective-c 

@import XCTest; 

@import integration_test; 

  
INTEGRATION_TEST_IOS_RUNNER(RunnerTests) 

``` 

Para más información visitar el siguiente link: [Configuración iOS](https://github.com/flutter/flutter/tree/master/packages/integration_test#ios-device-testing)  

  

Para más información sobre Flutter y Dart, como ejemplos de configuración de los pipelines de Azure DevOps del banco, se recomienda leer [el artículo de la wiki en el cual este módulo está basado](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/34872/Pruebas-de-Aceptaci%C3%B3n-para-Flutter?anchor=3.2-configuraci%C3%B3n-ios) y el siguiente [Demo](https://dev.azure.com/GrupoBancolombia/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_git/NU0007001_arquitecturaAutomatizacion_Test?path=/linea_base_automatizacion_flutter).


--- 

## :keyboard: Actividad : 
 

1. Agrega el contenido que debe llevar el archivo **MainActivityTest.java.md**.

2. Haz commit, espera 20 segundos y refresca la página.

--- 

</details> 

  

  

<details id=10> 

<summary><h2>Step 10: Pruebas E2E</h2></summary> 

  

<h2> 🛠️Herramientas usadas en automatización de pruebas E2E</h2> 

  

Estas son las herramientas necesarias para realizar las pruebas. 

  

  - **Java 1.8** se usa Java como lenguaje de programación. 

  - **Gradle** 

  - **Cucumber** está inmerso en Serenity. 

  - **Serenity BDD** es una librería Java, por lo que necesitará tener instalado un  JDK 1.8 o superior. <br><br> 

  

**[📺 Dojos Pruebas E2E](https://bancolombia.sharepoint.com/:f:/r/teams/PortaldeconocimientosTI/Documentos%20compartidos/General/Devops/Practicas%20de%20Pruebas/Pruebas%20E2E/Videos%20Dojos?csf=1&web=1&e=tCp4A1)** 

  

## Serenity BDD Y Cucumber. 

  

<img width="300"  height="100" alt="cucumber" src="https://user-images.githubusercontent.com/116098240/199345870-ae854668-6d49-4ee7-8c1b-4480cfe72193.PNG">  

  

<img width="300"  height="120" alt="cucumber" src="https://user-images.githubusercontent.com/116098240/199302877-7aa73f5d-28cd-447e-b72c-35edf41dae74.png"> 

  

## Gherkin. 

  

<img width="600"  height="400" alt="gherkin" src="https://user-images.githubusercontent.com/116098240/199121008-5b2d9cbc-0623-49fd-9d73-77361ef31c07.png"><br><br> 

  

```gherkin  

Feature: Título del escenario 

Dado [Condiciones previas o contexto inicial] 

Cuando [Evento o desencadenante] 

Entonces [Resultado esperado] 

``` 

  

- **Feature:** es la descripción de la funcionalidad a desarrollar. La palabra clave principal de un documento Gherkin es Feature, seguido por: y un breve texto que describa el feature, una feature tiene uno o varios scenarios. 

  

``` 

Feature: Extracción de dinero 

  

Background:  

Dado La tarjeta de crédito está habilitada 

Y El saldo disponible en mi cuenta es positivo  

Y El cajero tiene suficiente dinero 

  

Scenario: … 

``` 

  

- **Scenario (Escenario):** Describe un ejemplo de comportamiento del sistema, son condiciones de aceptación de una historia de usuario y normalmente las proporcionan los dueños de producto.  

  

- **Given (|Dado|Dada|Dados|Dadas) :** describe el contexto inicial de la prueba para establecer el escenario, un Given puede ser meramente informativo, para proporcionar algún contexto. 

  

>>Se deben incluir sólo las condiciones previas que estén directamente relacionadas con el escenario. 

  

- **When (Cuando):** Describe la acción o evento principal que el usuario realiza. Esta acción generará algún resultado, que comprobarás en el **Then**. 

  

- **Then (Entonces):** se trata del resultado esperado de las acciones ejecutadas. Define las condiciones que determinan si la prueba tiene éxito o no. Si se cumplen las condiciones, el software funciona correctamente; en caso contrario, falla.  

  

- **And (Y):**  Puedes ampliar cualquier sentencia utilizando "Y". Esto se debe a que cada escenario representa una funcionalidad individual. Si incluyéramos varios  Given-When-Then no tendría sentido que fuera una única funcionalidad. 

  

- **But(Pero):** **But** funciona igual que **Then**, pero se utiliza cuando queremos verificar que no se observa ningún resultado concreto, por ejemplo: 

  

```gherkin 

Dado que cumplo una condición previa 

Cuando  ejecuto una acción 

Entonces  observo este resultado 

Pero  no debería poder ver este otro resultado 

``` 

  

--- 

### Recomendaciones:<br><br> 


- Especificar las HU en términos de que es lo va a hacer el sistema y no como debe hacerlo. 

  

- No utilices un **Background** para features que contengan sólo un escenario, ya que podemos incluir los detalles en el **Given** directamente. 

  

- Debemos evitar el uso de lenguaje o acciones técnicas en el **Background.** 

  

- Mantén los escenarios cortos evitando los detalles de la implementación, pero añade suficiente descripción para entender el contexto del escenario. 

  

-  Evita los pasos que no incluyen 'Y' al principio, Por ejemplo: 

  

```gherkin 

Escenario: Página de inicio 

Dado que estoy en la página de inicio y me desplazo hacia abajo 


``` 

  

- Utiliza pasos declarativos en lugar de imperativos: Los pasos imperativos suponen exponer innecesariamente muchos detalles internos del sistema. 

  

- Hacer que los escenarios sean atómicos, ya que al ejecutarse de forma independiente sin depender de otros escenarios nos ayudará a hacer debug más rápidamente cuando se necesite. 

  

- Para trabajar con los **features** en español se debe colocar al inicio del archivo la sentencia <code>#language:es</code> 

  

--- 

  

**Ejemplo** 

  

```gherkin 

Feature: Login swaglabs  

  

As an user  

I want to log in to the swaglabs application  

to view the products.  

  

Scenario: Login with wrong password  

Given User is on the login page  

When User attempts to login with username "standard_user" and password "wrong_password"  

Then he should be presented with the error message "Epic sadface: Username and password do not match any user in this service" 

``` 
  

---
  

<h2>⚙️ Arquitectura de automatización </h2> 


<h2 align="center"><strong>🧑🏽‍💻Patrón Screenplay</strong></h2><br><br> 


<img width="613" alt="g-w-t-v2" src="https://user-images.githubusercontent.com/116098240/199121608-194a03ce-ae02-45d7-93ca-91c10eac761d.png"><br><br> 


Como se ve en la figura anterior, el patrón  screenplay se centra en los actores que tienen habilidades para realizar Task, habilitar Acciones y hacer Preguntas sobre la aplicación y sus elementos. Por este motivo, las pruebas se leen mucho mejor si se presentan desde el punto de vista del usuario (en lugar de desde el punto de vista de las "páginas").<br> 

El patrón Screenplay es la implementación del patrón The Journey Pattern, lo que nos indica este patrón es que vamos a tener un **Actor** que va a ser el centro de nuestra automatización y va a realizar todas las ejecuciones, teniendo a su disposición unas tareas que están compuestas de unas interacciones, es un patrón centrado en el actor.<br> 
 

**🔗[Mas info del Patrón ScreenPlay](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/9602/Patr%C3%B3n-ScreenPlay)**<br><br> 


--- 

  

<h2 align="center"><strong>🌫️Capas de la Arquitectura</strong></h2><br> 

  

<img width="500" height="350" alt="capas" src="https://user-images.githubusercontent.com/116098240/199122724-b6fe20d2-c484-498f-a685-36d9df42e62a.png"><br><br> 

  

- **Features:** Son las narrativas o. feature que equivalen a los escenarios de cucumber diseñados aplicando BDD. Los archivos son nombrados en minúscula, separados por “_” y pueden contener uno o más escenarios dependiendo del caso de negocio de prueba, **Ej.**<code>filtering_client_bank_accounts.feature</code> 

  

Se espera que los escenarios sean especificados usando lenguaje Gherkin y que estén dados en términos de lo que el usuario espera que pase más no del cómo debe hacerlo. Es decir, escribir los escenarios como un proceso de negocio de alto nivel, no en términos de clicks y selects. Para aclararlo, se presenta la siguiente imagen:<br><br> 

  

<img width="700"  height="200" alt="practicas" src="https://user-images.githubusercontent.com/116098240/199121435-90a5c929-75ea-4219-9402-b915c6c42edb.PNG"><br><br> 

  

- Los **Step Definitions**, son archivos en el lenguaje de programación usado, donde Cucumber va a poder asociar qué acciones ejecutar asociadas a cada paso de los criterios de aceptación definidos en los features.<br> 

  

- **Tasks:** Clases que representan tareas que realiza el actor a nivel de proceso de negocio, se llaman desde los Step definitions y están compuestas de interacciones. 

  

- **Interactions:** Se encargan de las interacciones con la interfaz de usuario. Muchas interacciones ya fueron desarrolladas y se encuentran disponibles gracias a las librerías de screenplay y de serenity BDD. Ejemplo: Open, Click, Enter, Hit, SelectFromOptions,  hacen uso de los userinterface. 

  

- **UserInterface:** Page Objects y Page Elements. Mapean los objetos de la interfaz de usuario 

  

- **Questions:** Esta capa gestiona los Asserts o verificaciones de las pruebas las cuales son el fin último de las mismas, ya que con estas capturamos la información de la interfaz que puede ser usada. Text,Value, Visibility… 

  

- **Integration:** Es una capa opcional, que nos sirve para comunicarnos con un sistema externo, como una base de datos, API o algún servicio. 

  

### Capas transversales: 

  

- **Utils:** Son aquellas funcionalidades que pueden usarse en cualquier parte del proyecto como pueden ser conversiones, lectura de archivos planos, conexiones... 

  

- **Models:** Son las clases que tiene atributos y propiedades para hacer viajar la data y que usan el patrón object builder o están relacionadas con el modelo de dominio. 

  

- **Exceptions:** Que nos permiten dar manejo los errores. 

  

--- 

  

<h2 align="center"><strong>🗃️Arquetipo de referencia </strong></h2><br> 

  

``` 

src/main/java 

    | 

    \-- co.com.empresa.qa 

        | 

        |   \-- exceptions 

        |   \-- models 

        |   \-- questions 

        |   \-- task 

        |   \-- userinteraface 

        | 

    \-- resources 

    | 

src/main//test 

   | 

   \-- java 

       | 

        \-- co.com.empresa.qa 

           |   \-- runners 

           |   \-- stepdefitions 

    \-- resources 

        \-- features 

        

``` 

--- 

Para entender el funcionamiento a nivel de código fuente del patrón visita el siguiente repositorio **🔗[Screenplay Pattern with Serenity BDD ](https://github.com/serenity-bdd/screenplay-pattern-todomvc)** 

<br><br> 

  

<h2 align="center"><strong>Paralelización de Pruebas </strong></h2><br> 

  

La paralelización de pruebas tiene el objetivo de correr las pruebas en simultaneo y asi poder mejorar la eficacia de los pipelines, se puede implementar de dos maneras: 

  

1. Usar varios stage en el pipeline de RM ejecutándose en paralelo, donde cada uno debe usar un agente diferente. 

2. También se puede hacer una paralelización usando los hilos que tiene nuestra máquina, la cual funciona muy bien para aplicaciones web.**[Mas información](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10854/Paralelizando-la-ejecuci%C3%B3n-de-pruebas)** 

<br><br> 

  

- Para aplicaciones móviles y de escritorio se usa un plugin que nos permite tener una estrategia de paralelización para este tipo de aplicaciones, **[aquí podrás encontrar más información](https://medium.com/bancolombia-tech/ejecutando-pruebas-automatizadas-m%C3%B3viles-en-paralelo-usando-serenity-bdd-de-manera-sencilla-a26681c82411)** 

  

--- 

## Pipeline CD para automatizaciones. 

  

Los pipelines CI/CD se unifican en la metodología Trunk Base Development (TBD) para formar uno solo que agrupa las tareas necesarias para compilar un artefacto. Puede ser o no un Pipeline As Code, básicamente es un pipeline de build ya que compila una aplicación y genera un artefacto. 

  

**Tener en Cuenta:** 

  

- El pipeline de build tendrá el mismo nombre del repositorio. Mas info **[Estándar nombramiento de Repositorios](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/109/Est%C3%A1ndar-nombramiento-de-Repositorios?anchor=**repositorios-para-automatizaci%C3%B3n-de-pruebas)** 

  

-  Debe guardarse en la carpeta de Sección de Practicas de Automatización, dentro de una carpeta nombrada con el código y el nombre del aplicativo. Sección de Practicas de Automatizacion\AWxxxx_NombreAplicativo. 

  
- Los pipelines as Code deben estar creados bajo la siguiente **[plantilla](https://grupobancolombia.visualstudio.com/b267af7c-3233-4ad1-97b3-91083943100d/_apis/git/repositories/1b927269-b4fe-422e-bbb7-6c60f64a9938/Items?path=/.attachments/Template%20Pipeline%20CD_Build-30526b0d-0260-4888-a612-3a9b25c550a9.txt&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster)** 


-  Los nombres de los pipelines as Code deben llevar el siguiente formato: 

  

``` 

NombreRpositorio_Build.yaml 

NombreRpositorio_Build.yml 

``` 

  

- Deben llevar las siguientes Tareas. 

  
![pipel](https://user-images.githubusercontent.com/116098240/208769961-ae1b4d59-4786-4713-80b5-726a6c5a7f84.PNG) 

  

Aquí podrás encontrar las instrucciones para configurar las tareas del pipeline [documentación](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10058/Creaci%C3%B3n-pipeline-automatizaci%C3%B3n-CD?anchor=**tareas-del-pipeline**) 


--- 


## Pipeline RM de Pruebas E2E (Test_DEV) 


Este pipeline se usa para probar la estabilidad de las automatizaciones, por lo tanto, debe ejecutarse antes de los pasos a PDN o Certificaciones. 


- Estándar de Nombramiento **AWXXXX_NombreAplicacion_Test_DEV** 

- Debe estar ubicado dentro de una carpeta con el código y nombre de la aplicación, dentro de la carpeta llamada Sección de Practicas de automatización. 

- Se puede crear desde un [template existente](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10057/Pipeline-RM-de-Pruebas-E2E-(RM-_DEV)?anchor=**crear-el-pipeline-desde-un-template-de-rm-existente**) 

- El Agent-Pool que se usa es DevOps-Automatizadas-Cloud y el agente se configura en la sección Demands. 

- Las Tareas que debe llevar son: 


![pipel](https://user-images.githubusercontent.com/116098240/208781208-baad9889-cecf-4072-93c3-23da4ed04304.PNG) 
  

Aqui puedes encontrar más información sobre la [configuración de las tareas](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10057/Pipeline-RM-de-Pruebas-E2E-(RM-_DEV)?anchor=configuraci%C3%B3n-de-la-secci%C3%B3n-tasks-del-pipeline**). 

  

Además en este articulo encontraras las instrucciones para configurar [Gasper](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/9247/Configuraci%C3%B3n-de-Gasper-en-los-pipelines) que es una extensión para gestionar Bugs y la [Extensión AutomationUse](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/12628/Extensi%C3%B3n-AutomationUse) que mide el porcentaje de uso de un artefacto de automatización en los diferentes raleases donde se ejecutan pruebas E2E o pruebas de aceptación. 

  

- Despues de ejecutar las Automatizaciones en el pipeline de estabilización Test_DEV se integra al pipeline de la aplicación para una salida a producción, ya sea QA_PDN para aplicaciones Iseries o CER para aplicaciones No iseries, aquí podrás encontrar [más información](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_wiki/wikis/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa.wiki/10985/Pipeline-de-Aplicaci%C3%B3n-CER-o-QA_PDN-en-Ambientes-Stage-o-Calidad) 

  

--- 

## :keyboard: Actividad : 
 

1. Dado el siguiente feature, En el archivo **actividad7.md** da click en el :pencil2: para editar y completa las partes faltantes en el **StepDefinitions** 
 

```gherkin 

#language: es 

  

Característica: Validación de intentos de acceso y acceso exitoso. 

  

  Escenario: Ingresar correctamente los datos de la cuenta para persona natural 

    Dado que un cliente tiene cuenta de acceso 

    Cuando ingresa los datos correctamente 

      | tipoPersona     | cedula | clave    | 

      | Persona Natural | 111111 | 12342598 | 

    Entonces debe observar la página principal de sucursal virtual 

  

``` 

2. Haz commit, espera 30 segundos y refresca la página e ingresa a la siguiente rama **Step X: Actividad Final** y realiza la actividad final. 


</details> 

  

<details id=X> 

<summary><h2>Step x: Actividad Final</h2></summary> 

--- 

## :keyboard: Actividad : 


1. En este ejercicio, realizarás una prueba E2E siguiendo el [arquetipo de referencia](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_git/NU0007001_arquitecturaAutomatizacion_Test?version=GBmaster&path=/otros-ejemplos/base_project_for_web_automation_projects) a el sitio web [SWAGLABS](https://www.saucedemo.com/) o una prueba de aceptacion con karate a [Swapi](https://swapi.dev/)  Puedes guiarte con este [demo de prueba con karate](https://github.com/anfruiz/karate-demo)


  
- Crearás un repositorio, un pipeline de **CD** y uno **RM** puedes guiarte con los siguientes videos: [Video Creacion Pipeline CD](https://bancolombia-my.sharepoint.com.mcas.ms/personal/jaasilv_bancolombia_com_co/_layouts/15/stream.aspx?id=%2Fpersonal%2Fjaasilv%5Fbancolombia%5Fcom%5Fco%2FDocuments%2FPara%20tener%20en%20cuenta%2FCreacion%20Pipeline%20CD%2Emp4&ga=1) y [Video Creacion Pipeline RM](https://bancolombia-my.sharepoint.com.mcas.ms/personal/jaasilv_bancolombia_com_co/_layouts/15/stream.aspx?id=%2Fpersonal%2Fjaasilv%5Fbancolombia%5Fcom%5Fco%2FDocuments%2FPara%20tener%20en%20cuenta%2FCreacion%20Pipeline%20RM%2Emp4&ga=1)


  - Usa el siguiente nombre **Dojo_Curiosity_Onboarding_TuNombre** para el repositorio y pipelines
  
  - El pipeline de ir en el directorio **Dojo_Pruebas/Onboarding_PruebasContinuas**

  - Agrega dentro del repositorio la carpeta con el nombre de la prueba que vayas a realizar  **acceptance_test** o **E2E**.

  - El stage E2E debe llevar el nombre **Onboarding_TestE2E**  
  
  - El stage Acceptance Test debe llevar el nombre  **Onboarding_AcceptanceTest**  

  - Configura las tareas en los stages del pipeline de RM pero no lo ejecutes.

  - Pipeline para crear repositorio [AW1192003_DevOps_Operations_Repository](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_build?definitionId=12220&_a=summary).



3. En el repositorio Template del Onboarding deberás crear un Issue y adjuntar los links del repositorio y los pipelines. 

Algunos pipelines de ejemplo: 

- [Configuracion stage E2E ](https://grupobancolombia.visualstudio.com/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_releaseProgress?releaseId=29917&environmentId=86004&_a=release-task-editor)

- [Configuracion stage Acceptance Test](https://grupobancolombia.visualstudio.com.mcas.ms/Vicepresidencia%20Servicios%20de%20Tecnolog%C3%ADa/_releaseProgress?releaseId=1368672&environmentId=6421333&_a=release-task-editor)

  

--- 

  

### ¿Cómo crear Issues para realizar tus entregas ? 

- Para crear un Issue, debes ingresar en la pestaña Issues: 


![hu](https://user-images.githubusercontent.com/116098240/208758490-2c5fef79-1a5b-4ad2-a1a1-6659fb74a469.png) 

  

- Una vez que haga clic en esa pestaña, crea un nuevo issue haciendo clic en New issue 

  

![issu2](https://user-images.githubusercontent.com/116098240/208758666-34596a2a-3d63-4e5a-a687-3ab3eb470fb8.png) 

  

- Una vez que haya creado un nuevo issue, será recibido por la pantalla a continuación. Aquí proporcionarás 

- Un título para el issue que será tu nombre 

- Un cuerpo para tu Issue donde pondras el link del pipeline. 

  
Y daras click en el boton **Submit new issue** 

  
![issu](https://user-images.githubusercontent.com/116098240/208758705-190b4896-94b1-4574-b41e-9d2a3d7b75ee.png) 

  
**IMPORTANTE:** Los Issues deben dejarse en estado abierto **Open**, de esta manera cada vez que se crea un Issue una persona de nuestro equipo pasará a revisar si su entrega corresponde a los requerimientos solicitados en la asignación, y es quien cambia el estado de un Issue a **Close** o dejara un comentario en relación a una corrección o adición que usted deba realizar para que sea válida la entrega realizada y que su actividad Issue pase a **Close**. 

  
--- 


</details> 

  


  
