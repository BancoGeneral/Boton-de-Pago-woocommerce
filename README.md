#  Botón de Pago Yappy – WooCommerce

##  Descripción
Botón de Pago Yappy es el *checkout oficial* de Banco General para WooCommerce. Ofrezca Yappy como método de pago a más de 600 mil clientes y reciba pagos con Yappy directamente en su tienda.

Rápido, seguro y fácil de implementar en su sitio web.

## Documentación

Encuéntrala en [www.bgeneral.com](Https://www.bgeneral.com/desarrolladores)

## Requerimientos mínimos

PHP 5.6+

WordPress 5.2+

WooCommerce 4.0+

Una cuenta jurídica con Yappy

Un [certificado de SSL](https://docs.woocommerce.com/document/ssl-and-https/)

## Instalación

1. Descargue el archivo .zip desde este repo.
2. Acceda a su panel de administración.
3. En el menú, seleccione ***Plugins* > Añadir nuevo.**
4. Haga clic en el botón **Subir plugin** en la parte superior de la pantalla.
5. Seleccione el archivo yappy-bg-para-woocommerce.zip de su sistema de archivos local.
6. Haga clic en el botón de **Instalar ahora**.
7. Cuando la instalación se complete, se mostrará ***“Plugin* instalado correctamente”**.
11. Haga clic en el botón **Activar Plugin** en la parte inferior de la página para completar la instalación.

Para obtener más información sobre la instalación de plugins desde un archivo zip, [consulte este enlace](https://wordpress.org/support/article/managing-plugins/#installing-plugins).

## Actualización
Dentro del panel de control de Wordpress; bajo la sección de ***Plugins***, encontrara una notificación indicandole que hay una actualización. Haga clic en **"Actualizar ahora"**.

## Configuración
Luego de completar la instalación del *plugin*, siga estos pasos para comenzar a utilizar el Botón de Pago Yappy:

1. Haga clic en Configuraciones desde el *plugin* de Botón de Pago o acceda desde el mensaje de configuración en la zona superior con el logo de Banco General.

![Visual del Botón de Pago Yappy](https://www.bgeneral.com/wp-content/uploads/2020/10/Boton%20de%20pago%20woocommerce/Configuracion%20WooCommerce%201.png)

2. Una vez en las Configuraciones del Botón de Pago, complete los campos de ID del comercio y Clave secreta con la información proporcionada en su Banca en Línea Comercial (Administración > Botón de Pago Yappy > Generar clave secreta). Su ID del comercio es un valor alfanúmerico de 32 caracteres.

![Visual del Botón de Pago Yappy](https://www.bgeneral.com/wp-content/uploads/2020/10/Boton%20de%20pago%20woocommerce/Configuracion%20WooCommerce%202.png)

3. Luego de completar los campos, marque la opción de Activar Botón de Pago. Guarde los cambios y la instalación estará completa. Finalmente, verifique la opción de Yappy como método de pago en su tienda.
![Visual del Botón de Pago Yappy](https://www.bgeneral.com/wp-content/uploads/2020/10/config%203.png)

## Modo de pruebas
El modo de pruebas permite simular transacciones utilizando números de teléfono de prueba para visualizar el flujo de compra sin realizar un pedido real. Debe tener en cuenta que:
- El modo de pruebas **sólo funciona con los números de teléfono de pruebas** (se detallan a continuación).
- El modo de pruebas no descuenta inventario.
- Recuerde deshabilitar el modo de pruebas para aceptar transacciones reales.

| 6000-0000                | 6000-0002                |
|:------------------------:|:------------------------:|
| Transacciones realizadas | Transacciones canceladas |

![Visual del Botón de Pago Yappy](https://www.bgeneral.com/wp-content/uploads/2020/10/Modo%20pruebas%20boton%20de%20pago.png)

## Funcionalidades extra
### Personalización del Botón de Pago Yappy
Opcionalmente, puede seleccionar el color del botón que se ajuste mejor al estilo de su tienda. Recomendamos la opción predeterminada.

![Brand (predeterminada)](https://www.bgeneral.com/wp-content/uploads/2020/10/Boton%20de%20pago%20woocommerce/brand.png)"Brand (predeterminada)"

![Dark](https://www.bgeneral.com/wp-content/uploads/2020/10/Boton%20de%20pago%20woocommerce/dark.png)"Dark"

![Light](https://www.bgeneral.com/wp-content/uploads/2020/10/Boton%20de%20pago%20woocommerce/light.png)"Light"

![White](https://www.bgeneral.com/wp-content/uploads/2020/10/Boton%20de%20pago%20woocommerce/white.png)"White"

### Método de pago por defecto
También puede habilitar Yappy como la opción de pago por defecto en su tienda (sin importar el orden de los métodos de pago instalados).

## Preguntas frecuentes

**1. ¿El Botón de Pago Yappy funciona con el *plugin* X que modifica WooCommerce?**

En general, el Botón de Pago Yappy funciona con cualquier *plugin* que funcione con WooCommerce 4.0+. Sin embargo, no podemos certificar que funcione con todos los *plugin* del mercado.

**2. Como comercio, ¿recibiré alguna notificación de las compras realizadas por Yappy?**

Sí. Cada vez que se realice una compra por Yappy, recibirá un correo de confirmación con el número de pedido de Magento, el monto y la hora de la transacción.

**3. ¿Funciona el Botón de Pago Yappy con WooCommerce Subscriptions?**

No, en estos momentos no funciona con suscripciones o cobros recurrentes.

**4. ¿Dónde puedo conseguir mis credenciales para el Botón de Pago Yappy?**

Sus credenciales las puede conseguir en Banca en Línea Comercial. Siga este enlace para verificar los pasos de generación de credenciales.

**5. ¿Para qué países está disponible Yappy?**

El Botón de Pago solo está disponible para Panamá.

**6.¿Cómo se manejan los pedidos con el Botón de Pago Yappy?**

El *plugin* maneja 3 estados de pedidos:

1. **Pendiente de pago:** El cliente hizo clic en el botón de “Paga con Yappy” y se está a la espera de que confirme la compra en el *app* de Banco General.
2. **Cancelado:** El cliente inició el proceso, pero canceló el pedido en el *app* de Banco General.
3. **Procesado:** El cliente confirmó la compra en el *app* de Banco General y el pago se ejecutó. Si se maneja inventario, el mismo se descontará.

**7. Veo un mensaje que dice “Algo salió mal, contacta al administrador.” ¿Qué debo hacer?**
- Asegúrese de que su sitio web cumple con los requerimientos mínimos.
- Revise que cuenta con la versión más reciente del módulo.
- Confirme que sus credenciales son correctas y que fueron colocadas en los campos correspondientes.
- Confirmar que el URL de su tienda está registrado correctamente en el perfil de su Botón de Pago Yappy en Banca en Línea Comercial.

**8. ¿Dónde puedo ver reportes de ventas de mi Botón de Pago Yappy?**

Las ventas del Botón de Pago se verán reflejadas en su Banca en Línea Comercial. Acceda a las mismas desde Reportes > Reportes Yappy.

## Resolución de problemas

¿Tiene algún problema? Siga estos pasos para asegurar la correcta configuración de la extensión:
- Asegúrese que su sitio cumple con los requerimientos mínimos.
- Revise que cuenta con la versión más reciente del módulo.
- Revise las preguntas frecuentes por si su pregunta se ve reflejada en las mismas.
- Confirme que sus credenciales son correctas y que fueron colocadas en los campos correspondientes.
- Confirme que no está habilitado el modo de pruebas (sandbox).
- Revise que el dominio de su tienda (URL) sea igual al que definió en su perfil de Botón de Pago en Banca en Línea Comercial, ya que se utilizará para validar la solicitud.

## ¿Tiene alguna pregunta?
Consulte nuestra sección de Preguntas Frecuentes o de Resolución de problemas para resolver los inconvenientes más comunes. Si requiere mayor soporte, comuníquese con nosotros por correo electrónico a botondepagoyappy@bgeneral.com.
