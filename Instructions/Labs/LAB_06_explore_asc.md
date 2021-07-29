---
lab:
    title: 'Explorar Azure Security Center'
    module: 'Módulo 3, lección 2: Describir las funcionalidades de las soluciones de seguridad de Microsoft. Describir las funcionalidades de administración de la seguridad de Azure'
---


# Laboratorio: Explorar Azure Security Center 

## Escenario del laboratorio
En este laboratorio, explorará Azure Security Center y aprenderá cómo puede utilizar Puntuación de seguridad de Azure para mejorar la posición de cumplimiento de su organización.

  

**Tiempo estimado**: 10-15 minutos.

#### Tarea 1: En esta tarea, realizará un paseo introductorio por Azure Security Center
1.	Abra Microsoft Edge. En la barra de direcciones, escriba **portal.azure.com**.

1. Inicie sesión con sus credenciales de administrador.
    1. En la ventana de inicio de sesión, escriba **admin@WWLxZZZZZZ.onmicrosoft.com** (la ZZZZZZ es su id. de inquilino único proporcionado por su proveedor de servicios de hospedaje de laboratorios) y luego seleccione **Siguiente**.
    
    1. Escriba la contraseña de administrador que debería haberle proporcionado su proveedor de servicios de hospedaje de laboratorios. Seleccione **Iniciar sesión**.
    1. Cuando aparezca un mensaje para preguntarle si quiere mantener la sesión iniciada, seleccione **Sí**.

1. En la esquina superior izquierda de la pantalla, junto a las palabras Microsoft Azure, seleccione el icono Mostrar el menú del portal (las tres líneas horizontales, también denominadas icono de hamburguesa) y luego seleccione **Todos los servicios**.  
1. En el cuadro Filtrar servicios, escriba **Security Center**, y luego seleccione **Security Center** en la lista de resultados.
1. Fíjese en la información disponible en la página de información general de Security Center.  
1. Es posible que vea un cuadro de información azul en la parte superior de la página que indica que puede estar viendo información limitada.  Seleccione **Haga clic aquí**.
    1. Para asegurarse de que tiene una visibilidad completa del inquilino, asígnese el rol necesario.  Seleccione **Administrador de seguridad** y luego **Obtener acceso** en la parte inferior de la página.
   
     1. Es probable que vea el mensaje "El grupo de administración raíz no existe".  Tal y como se indica en la descripción, el sistema creará el grupo por usted.  Es posible que tarde unos 15 minutos en hacerlo (aunque el tiempo suele ser inferior), pasados los cuales podrá repetir el proceso para obtener acceso.  Una vez que se le haya concedido acceso, seleccione **Security Center** en la esquina superior izquierda de la página, encima de la opción Obtener permisos, y luego actualice la página de información general de Security Center.
1. La información en la parte superior de la página incluye el número de suscripciones de Azure, el número de recursos evaluados, el número de recomendaciones activas y cualquier alerta de seguridad.  En el cuerpo principal de la página hay tarjetas que representan la Puntuación de seguridad, cumplimiento normativo, información, Azure Defender, etc.  
1. En la parte superior de la página, seleccione **Recursos evaluados**.  Esto le llevará a la página Inventario, que muestra su suscripción a Pase para Azure.  Seleccione **Pase para Azure – Patrocinio**.
1. La página de estado de los recursos ofrece una lista de recomendaciones.  En la lista disponible, seleccione **Debe haber más de un propietario asignado a su suscripción**. 
1. Seleccione la flecha desplegable situada junto a Pasos de corrección. Observe cómo se aportan pasos detallados de corrección junto a la opción de tomar medidas.  
1. Seleccione **Security Center** en la esquina superior izquierda de la pantalla para volver a la página de información general de Security Center.
1. En la parte superior de la página, seleccione **Recomendaciones activas**.  
1. La página Recomendaciones muestra acciones específicas que se pueden realizar y el aumento de la Puntuación de seguridad que conlleva cada una.  Para salir de la página Recomendaciones, seleccione la **X** en la esquina superior derecha de la ventana.
1. En la página principal, seleccione **Cumplimiento normativo**.
1. La página de cumplimiento normativo ofrece una lista de controles de cumplimiento.  Bajo cada control hay un conjunto de evaluaciones que se basan en Azure Security Benchmark y ofrecen recomendaciones sobre cómo puede asegurar sus soluciones en la nube en Azure.
1. Seleccione **IM. Administración de identidades** y luego **IM.4 Usar controles con autenticación sólida para todo el acceso basado en Azure Active Directory**.  La lista muestra las acciones de responsabilidad del cliente que pueden tomarse para mejorar la posición de cumplimiento.
1. Seleccione la **X** de la esquina superior derecha de la pantalla para cerrar la página y volver a la página Información general de Security Center. 
1. Deje la página Información general de Security Center abierta. La utilizará en la siguiente tarea.


#### Tarea 2: En esta tarea se desplazará a la Puntuación de seguridad de Azure y explorará las recomendaciones que pueden contribuir a mejorar su Puntuación de seguridad 

1. En la página Información general de Security Center, seleccione la tarjeta **Puntuación de seguridad**.

2. Seleccione **Pase para Azure – Patrocinio**.  Observe su Puntuación de seguridad.
3. En la página Recomendaciones, seleccione **Administrar acceso y permisos**. Observe que uno de los elementos de ese grupo está en rojo.
4. Seleccione el elemento **Debe haber más de un propietario asignado a la suscripción**, que muestra el estado del recurso en rojo. Si selecciona este elemento, no funcionará.
    1. En la esquina superior izquierda de la página, seleccione **Security Center**, encima de la opción Recomendaciones.
    
    1. En el panel de navegación izquierdo, seleccione **Recomendaciones**.
    1. En la página Recomendaciones, seleccione **Administrar acceso y permisos**. Observe que uno de los elementos de ese grupo está en rojo.
    1. Seleccione el elemento **Debe haber más de un propietario asignado a la suscripción**, que muestra el estado del recurso en rojo. 
5. Seleccione la **suscripción a Azure**.
6. En la parte superior de la página Control de acceso (IAM), seleccione **+ Agregar** y luego seleccione **Agregar asignación de roles** en el menú desplegable.
7. En el campo Rol, escriba **Propietario** y luego seleccione **Propietario** en la lista que aparece debajo.
8. En la lista de usuarios, seleccione **Alex Wilber** y luego seleccione **Guardar** en la parte inferior de la página.
9. El estado puede tardar hasta 24 horas en actualizarse, pasadas las cuales su Puntuación de seguridad también se actualizará, dado que todos los elementos del grupo Administrar acceso y permisos se han cumplido.
10. En la esquina superior izquierda de la página, donde aparecen las palabras Pase para Azure, seleccione **Security Center** y luego seleccione **Información general** para volver a la página Información general de Security Center.
11. Mantenga esta página del abierta para la siguiente tarea.


#### Tarea 3:  Recuerde que Security Center se ofrece en dos modos: Azure Defender DESACTIVADO (gratuito) y Azure Defender ACTIVADO. En esta tarea aprenderá a habilitar y deshabilitar Azure Defender

1.	En la página Información general de Security Center, seleccione **Habilitar Azure Defender** en la tarjeta Azure Defender.

2.	Seleccione la casilla **Azure Defender activado**.  Observe cómo todos los planes de Defender cambian su estado a Activado y fíjese en los precios de cada elemento. Después, seleccione **Guardar** en la esquina superior izquierda de la página.
3.	Vuelva a la página Security Center. Para ello, seleccione **Security Center** en la esquina superior izquierda de la página.   Es posible que deba esperar varios minutos para que la tarjeta Azure Defender refleje el cambio.  Actualice la página si es necesario.
4.	Para deshabilitar Azure Defender, seleccione **Precios y configuración** en el panel de navegación izquierdo de la página Security Center, y luego seleccione la **suscripción Pase para Azure: Patrocinio**.
5.	En la página Planes de Azure Defender, seleccione la casilla **Azure Defender desactivado** y luego seleccione **Guardar** en la esquina superior izquierda de la página.
6.	Aparecerá una ventana emergente en la que se le pedirá que confirme la degradación.  Deseleccione la casilla para que Microsoft se ponga en contacto con usted y seleccione **Confirmar**.
7.	Ya puede cerrar la pestaña del explorador para salir de Azure Portal.


#### Revisión
En este laboratorio, ha explorado Azure Security Center y ha aprendido cómo puede utilizar Puntuación de seguridad de Azure para mejorar la posición de cumplimiento de su organización.
