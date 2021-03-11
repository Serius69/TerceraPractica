
# Historias de Usuario
## Ingeniería del Software (SIS - 213)
<p align="center"><img src="img/PetAngel.jpg" width="500" ></p>

## PET-ANGEL
---
# Historias de Usuario
## Ingeniería del Software (SIS - 213)


### TITULO DEL PROYECTO PET-ANGEL



## Introducción
En el presente documento se puede observar las historias de usuario para la plataforma de mascotas “PET-ANGELS”. Una historia de usuario es una representación de los requisitos que se precisan para la elaboración de un sistema, es un lenguaje que permite a cualquier individuo entender con facilidad sin tener conocimiento previo en informática o programación.

## Objetivo
Identificar los requisitos del sistema y plasmarlo en el documento para desarrollar de forma precisa la plataforma mencionada y explicar los procesos que se llevarán a cabo.

## A quién está dirigido

Esta plataforma es principalmente informativa sobre el buen cuidado y crianza de las mascotas, agilizando cada uno de los procesos que actualmente se lleva acabó en las clínicas veterinarias, logrando brindar un mejor servicio a los clientes. Contando con voluntarios que estarán al cuidado de las mascotas con el servicio de guardería, los cuales tendrán un acceso al descuento Angels. Pet-Angeles busca destacar, ofreciendo contacto con las diferentes clínicas certificadas que se encuentren afiliados a la plataforma.

## Niveles de prioridad
Los niveles de prioridad serán en función al efecto que tenga en el núcleo del sistema, que en esta plataforma sería la . Para este sistema se definen los siguientes niveles de prioridad:

1. Alta: Este módulo afecta al núcleo del sistema directamente, por lo tanto es indispensable.
2. Medio: El módulo afecta al núcleo del sistema parcialmente.
3. Bajo: Afecta al núcleo del sistema de forma externa, sin embargo es prescindible.

## **Historias de Usuario**
### **01. Ingreso al sistema como usuario/cliente**

**Número**: 001      **Usuario**: Clientes

**Nombre de la historia**: Ingreso al sistema como usuario/cliente

**Prioridad en el Negocio**:Medio             **Riesgo de desarrollo**: Bajo

**Programador responsable:** *Troche Mayta Sergio*

**Validación:**  El usuario debe tener una cuenta registrada para poder acceder a la plataforma, los campos a introducir deben contar con el formato correcto :correo sin caracteres inválidos y contraseña mínima de 8 caracteres.

#### **Descripción:**
El usuario al ingresar a la pagina de Pet-Angel se le pedirá realizar un inicio de sesión para acceder a la plataforma de consultas de la pagina (Fig-1) se debe ingresar el correo y la contraseña, si el usuario no cuenta con una cuenta registrada debe de registrarse.


<p align="center"><img src="img/001login.png" width="600"></p>
<p align="center">Fig-001</p>

## Proceso

<p align="center"><img src="img/sis.png" width="600"></p>
<p align="center">P-001</p>

### **02.  Registro al sistema como cliente**

**Número:** 002   **Usuario:** Clientes 

**Nombre de la historia:** Registro al sistema como cliente

**Prioridad en el Negocio:** Medio            **Riesgo de desarrollo:** Bajo

**Programador responsable:** *Troche Mayta Sergio*

**Validación:** Para que un usuario nuevo se registre en la plataforma debe ingresar un nombre de usuario, correo y crear una contraseña. Estos campos deben tener caracteres válidos y todos son obligatorios.

#### **Descripción:**
Si es que un usuario es nuevo, este debe crear una nueva cuenta, ingresando al formulario de registro el cual se encuentra en la parte inferior central de la página de inicio de sesión (Fig-002) como un link. El usuario podrá crear su cuenta ingresando los siguientes datos:
- Nombre de Usuario.
- Correo.
- Contraseña.


<p align="center"><img src="img/002Registro.png" width="600"></p>
<p align="center">Fig-002</p>

## Proceso
<p align="center"><img src="img/reg.png" width="600"></p>
<p align="center">P-002</p>


### **03. Registro de usuario como "voluntario"**

**Numero:** 003 **Usuario:** Voluntarios

**Nombre de la historia:** *Registro en el sistema como voluntario*

**Prioridad en el Negocio:** *Medio*

**Riesgo de desarrollo:** *Medio*

**Programador responsable:** *Porcel Peña Jhoan*

**Validación:** *Se debe validar el nombre de usuario, correo electrónico, numero de celular, contraseña*

#### **Descripción:**
El presente registro lo harán los usuarios que desean, con los siguientes datos (Fig-003):
- Nombre de usuario.
- E-mail.
- Contraseña.
- numero de celular.


<p align="center"><img src="img/003Registro voluntarios.png" width="600"></p>
<p align="center">Fig-003</p>

## Proceso
<p align="center"><img src="img/reg.png" width="600"></p>
<p align="center">P-003</p>


### **04. Visualización del perfil del cliente**

**Número:** 004      **Usuario:**

**Nombre de la historia:** Visualización del perfil del cliente
**Prioridad en el Negocio:**  Medio           **Riesgo de desarrollo:** Bajo

**Programador responsable:** *Troche Mayta Sergio*

**Validación:** El usuario puede observar sus datos que se registró en la plataforma, además en la parte inferior se observa el historial de consultas que tiene, por otra parte, se observa algunas opciones que puede editar y/o agregar los datos para hacer mas completo su perfil:
- Nombre de Usuario.
- Nombre de la mascota.
- Raza de la mascota.
- Edad de la mascota.
- Correo.
- País / Ciudad.

También tendrá las opciones de edición con los botones de:
- Editar perfil.
- Cambiar contraseña.

En la parte de mascotas tiene una descripción detallada de las mascotas que tiene registradas en su perfil:
- Nombre de la mascota.
- Raza de la mascota.
- Edad de la mascota.
- Generar cita


#### **Descripción:**
El usuario podrá ver su perfil, revisar sus datos registrados en la plataforma y observar las mascotas que registro en la plataforma mediante una lista en la parte inferior de la interfaz. Finalmente, los campos más importantes son los datos del usuario y las consultas generadas que tiene(Fig-004).

<p align="center"><img src="img/004Perfil.png" width="600"></p>
<p align="center">Fig-004</p>

## Proceso
<p align="center"><img src="img/usu.png" width="600"></p>
<p align="center">P-004</p>

### **05. Edición de Perfil del Cliente**

**Número:** 005     **Usuario:** Clientes

**Nombre de la historia:** Edición del perfil del cliente

**Prioridad en el Negocio:** Alta            **Riesgo de desarrollo:** Alta

**Programador responsable:** *Troche Mayta Sergio*

**Validación:** En la figura se puede observar los campos que puede editar el usuario, como ser las
opciones de la edición de datos, que son:
- Nombre del usuario.
- Correo.
- Ciudad.
- País.
Por otra parte en la actualización de la contraseña solo se observa los campos de ingreso de la
nueva contraseña más la verificación de la nueva y la validad de la antigua contraseña.

Finalmente la parte de actualización de las mascotas registradas el usuario podrá cambiar los siguientes campos:
- Nombre de la mascota.
- Raza de la mascota.
- Edad de la mascota.

#### **Descripción:**
El cliente tiene registrado sus datos personales en la plataforma, por lo cual, puede editar sus datos como ser el nombre del usuario, el correo electrónico del usuario, además la ubicación actual del usuario como ser el país y ciudad. Por lo tanto, el usuario puede editar la contraseña actual con una contraseña nueva (Fig-005).

<p align="center"><img src="" width="600"></p>
<p align="center">Fig-005</p>

## Proceso
<p align="center"><img src="img/edit.png" width="600"></p>
<p align="center">P-005</p>

### **06. Visualización del perfil de clínica**

**Numero:** *006*
**Usuario:** clientes nivel clínica

**Nombre de la historia:** *Visualización del perfil de clínica*

**Prioridad en el Negocio:** *Medio*

**Riesgo de desarrollo :** *bajo*

**Programador responsable :** *Porcel Peña Jhoan*

**Validación:** *Se deberá visualizar los datos generales de las clínicas como:* 
- Nombre
- Teléfono
- Nombre de operadora
- ubicación de la clínica
- Tipos de atención
- Horario de atención
- Veterinarios a cargo según el horario.
- Sección de video llamadas o llamadas de emergencia
- Sección de mascotas atendidas
- Una calificación justificada de la clínica

#### **Descripción:**
Todos los usuarios registrados en general,podrán visualizar la información proporcionada por la clínica veterinaria, la cual estará en su perfil de la misma(Fig-006).

<p align="center"><img src="img/006Vista Clinica.png" width="600"></p>
<p align="center">Fig-006</p>

## Proceso
<p align="center"><img src="img/clin.png" width="600"></p>
<p align="center">P-006</p>

### **07. Visualización clínicas**

**Numero:** *007*

**Usuario:** clientes en general

**Nombre de la historia:** *Visualización de la pantalla principal*

**Prioridad en el Negocio:** *Medio*

**Riesgo de desarrollo :** *bajo*

**Programador responsable :** *Porcel Peña Jhoan*

**Validación:** *Se vera las clinicas veterinarias que se encuentran registradas en el sistema"* 

#### **Descripción:**
Todos los usuarios registrados en general,podrán visualizar la información de las diferentes clinicas"(Fig-007).

<p align="center"><img src="img/0071Clinicas menu.png" width="600"></p>
<p align="center">Fig-007</p>

<p align="center"><img src="img/0072Destacados.png" width="600"></p>
<p align="center">Fig-007</p>

## Proceso
<p align="center"><img src="img/prin.png" width="600"></p>
<p align="center">P-007</p>

### **008. Visualización de plataformas de video llamada**

**Número:** 008      **Usuario:** Paciente

**Nombre de la historia:** Visualización de plataformas de video llamada

**Prioridad en el Negocio:**  Media          **Riesgo de desarrollo:** Bajo

**Programador responsable:**

**Validación:** 

El Usuario podrá elegir la plataforma de video llamada con la cual esten mas familiarizado.

#### **Descripción:**

El Usuario tendrá a su disposición varias plataformas donde pueda el realizar video llamadas (Zoom, Whatsapp, Meet, Telegram, Messeger) así el podrá escoger la tecnología con el que se sienta mas cómodo. (Fig-008)

<p align="center"><img src="img/008Videollamada.png" width="600"></p>
<p align="center">Fig-008</p>

## Proceso

<p align="center"><img src="img/vid.png" width="600"></p>
<p align="center">P-008</p>


### **009.  Creación de la cuenta del administrador**


**Número:** 009     **Usuario:**

**Nombre de la historia: Creación de la cuenta del administrador**

**Prioridad en el Negocio: Medio**             **Riesgo de desarrollo: Alta**

**Programador responsable:** *Troche Mayta Sergio*

**Validación:  Solo el administrador principal puede registrar a un nuevo administrador para lograr
apoyar el sistema, los características que el usuario debe llenar en el sistema son:

- Nombre de Usuario.
- Correo.
- Celular.
- País / Ciudad.
- Contraseña.
- Pregunta frecuente y respuesta**
<p align="center"><img src="img/011Creacion admin.png" width="600"></p>


<p align="center">Fig-009 “Creación de la cuenta del administrador”.

## Proceso
<p align="center"><img src="img/reg.png" width="600"></p>
<p align="center">P-009</p>

</p>


#### **Descripción: El administrador principal de la plataforma puede agregar a un nuevo administrador, por otra parte los datos más importantes son la contraseña de usuario y la pregunta de seguridad.**

### **010.  Recuperación de contraseña ** 

**Número:** 010      **Usuario:**

**Nombre de la historia: Recuperar contraseña**

**Prioridad en el Negocio: Medio**             **Riesgo de desarrollo: Medio**

**Programador responsable:** *Troche Mayta Sergio*
 
**Validación: Para recuperar la contraseña el usuario lo hará con una opción en la pantalla de inicio
de sesión o cuando se equivoque tres veces al momento de realizar este último..
Para esta función, el sistema le pedirá la respuesta a su pregunta seguridad y su nueva contraseña.
La contraseña tendrá que tener el mismo formato que al crear una cuenta.
Al darle a “Recuperar Cuenta” le dará un mensaje de confirmación o de error dependiendo el caso.**


#### **Descripción:  La recuperación de contraseña es una funcionalidad que permite que el usuario pueda recuperar su contraseña en caso de olvidarla. Para esto es necesario que conozca su pregunta de
seguridad.**

<p align="center"><img src="img/012Recuperacion de contrasenia.png" width="600"></p>
<p align="center">Fig-010 </p>

## Proceso
<p align="center"><img src="img/cont.png" width="600"></p>
<p align="center">P-010</p>

Para el proceso de recuperar contraseña se puede entrar de dos formas. Una directamente desde la
página de iniciar sesión o equivocándose 3 veces al iniciar sesión. Una vez dentro se pedirá la
respuesta a la pregunta de seguridad y una nueva contraseña. Si todo salió correcto el sistema le
devolverá un mensaje de confirmación de la recuperación de contraseña.


## **Conclusión**


Después de un análisis minucioso de los requerimientos necesarios para la plataforma de cuidado de mascotas "PET-ANGEL", se cumplió con el objetivo del documento, logrando identificar los requisitos indispensables para el funcionamiento idóneo de la plataforma.

Cada proceso fue detallado y descrito a lo largo del documento para que sea entendible para cualquier individuo. No obstante, es necesario aclarar que hay algunos procesos y funciones que serán externos en la primera versión del sistema.

Cabe recalcar que si bien se identificaron los requisitos principales, a medida que se lleva a cabo el desarrollo del sistema es inevitable que vayan apareciendo más requisitos, los cuales serán documentados paralelamente.


