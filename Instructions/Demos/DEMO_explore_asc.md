---
Demo:
    title: 'Azure Security Center'
    module: 'Módulo 3, lección 2: Describir las funcionalidades de las soluciones de seguridad de Microsoft. Describir las funcionalidades de administración de la seguridad de Azure'
---

# Demo: Azure Security Center

### Escenario de la demo

En esta demostración, recorrerá Azure Security Center y mostrará cómo se puede utilizar la Puntuación de seguridad de Azure para mejorar la posición de seguridad de una organización.

1. Abra la pestaña del explorador **Inicio: Microsoft Azure**.  Si anteriormente había cerrado la pestaña, abra una página del explorador y, en la barra de direcciones, escriba portal.azure.com y vuelva a iniciar sesión.

1. En el cuadro de búsqueda, en la barra azul de la parte superior de la página junto a Microsoft Azure, escriba **security center** y seleccione **Security Center** en los resultados de la búsqueda.

1. Si es la primera vez que entra en Security Center con su suscripción, es posible que llegue a la página de introducción y se le pida que actualice.  Desplácese a la parte inferior de la página y seleccione **omitir**.

1. Fíjese en la información disponible en la página de información general de Security Center.  Nota: Es posible que vea un cuadro de información azul en la parte superior de la página que indica que puede estar viendo información limitada.  No lo seleccione (puede tardar hasta 15 minutos en procesarse y no supone ninguna diferencia para esta demostración).

1. La información en la parte superior de la página incluye el número de suscripciones de Azure, el número de recursos evaluados, el número de recomendaciones activas y cualquier alerta de seguridad.  En el cuerpo principal de la página hay tarjetas que representan la Puntuación de seguridad, cumplimiento normativo, información, Azure Defender, etc.  

1. En la parte superior de la página, seleccione **Recursos evaluados**.  (Tenga en cuenta que esto equivale a haber seleccionado Inventario en el panel de navegación izquierdo de la página principal de Security Center).
    1. De esta forma irá a la página de **Inventario**, que muestra su suscripción al pase para Azure.  Seleccione **Pase para Azure – Patrocinio**.
    1. La página de estado de los recursos ofrece una lista de recomendaciones.  En la lista disponible, seleccione **Debe haber más de un propietario asignado a su suscripción**.
    1. Seleccione la flecha desplegable situada junto a Pasos de corrección. Observe cómo se aportan pasos detallados de corrección junto a la opción de tomar medidas.  
    1. Seleccione **Security Center** en la esquina superior izquierda de la pantalla para volver a la página de información general de Security Center.

1. En la parte superior de la página, seleccione **Recomendaciones activas**.  (Tenga en cuenta que esto equivale a haber seleccionado Recomendaciones en el panel de navegación izquierdo de la página principal de Security Center).
    1. La página de recomendaciones muestra su panel de Puntuación de seguridad. 
    1. Debajo del panel de Puntuación de seguridad hay una lista de controles. Cada control de seguridad representa un riesgo de seguridad que debe mitigarse y también incluye información sobre la puntuación máxima asociada a ese control, la puntuación actual, el aumento potencial de la puntuación y el estado de los recursos.  
    1. Seleccione uno de los controles, como **Habilitar MFA**.  Seleccione uno de los subelementos, como **debe habilitarse MFA en las cuentas con permisos de propietario en su suscripción**.  En la página que se abre, verá una descripción, los pasos de corrección y los recursos afectados. Puede salir de esta página si selecciona la **X** en la esquina superior derecha de la pantalla.
    1. Puede salir de la página de recomendaciones si selecciona la **X** en la esquina superior derecha de la pantalla, para volver a la página de información general.

1. Ahora ha vuelto a la página de información general de Security Center.  En la página principal, seleccione Puntuación de seguridad (esto equivale a seleccionar Puntuación de seguridad en el panel de navegación izquierdo).
    1. De esta forma, irá al panel de la Puntuación de seguridad.  Además, enumera los grupos de administración y las suscripciones disponibles.  Seleccione su suscripción de Azure – Pase para Azure – Patrocinio.
    1. Así, irá a la página de Recomendaciones, que se mostró anteriormente.
    1. Puede salir de la página de recomendaciones si selecciona la **X** en la esquina superior derecha de la pantalla.
    1. Puede salir de la página de Puntuación de seguridad si selecciona la **X** en la esquina superior derecha de la pantalla, para volver a la página de información general.

1. Ahora ha vuelto a la página de información general de Security Center.  En la página principal, seleccione **Cumplimiento normativo**. (Tenga en cuenta que esto equivale a haber seleccionado Recomendaciones en el panel de navegación izquierdo de la página principal de Security Center).
    1. La página de cumplimiento normativo ofrece una lista de controles de cumplimiento.  Bajo cada control hay un conjunto de evaluaciones que se basan en Azure Security Benchmark y ofrecen recomendaciones sobre cómo puede asegurar sus soluciones en la nube en Azure.
    1. Seleccione **IM. Administración de identidades** y luego **IM.4 Usar controles con autenticación sólida para todo el acceso basado en Azure Active Directory**.  La lista muestra las acciones de responsabilidad del cliente que pueden tomarse para mejorar la posición de cumplimiento.
    1. Seleccione la **X** en la esquina superior derecha de la pantalla para cerrar la página y volver a la página de cumplimiento normativo.
    1. Seleccione la **X** en la esquina superior derecha de la pantalla para volver a la página de información general.

1. Vuelva a la página principal del portal Azure si selecciona **Inicio** en la esquina superior izquierda de la página.  Mantenga esta pestaña del explorador disponible, ya que volverá a ella en una demostración posterior.

## Revisión

En esta demostración, recorrió Azure Security Center y mostró cómo se puede utilizar la Puntuación de seguridad de Azure para mejorar la posición de seguridad de una organización.
