=== WooCommerce Chilexpress Shipping ===
Contributors: whooo, jhoynerk, tcattd
Tags: woocommerce, shipping, chile, chilexpress
Stable tag: 1.1.3
Requires at least: 4.4
Tested up to: 4.8
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.txt

Añade a Chilexpress como método de envío para WooCommerce.

== Description ==
Añade a Chilexpress como método de envío para WooCommerce.

Utiliza la API de Chilexpress para obtener los costos de envío de forma automática según la región/ciudad/localidad que el usuario seleccione para envío en WooCommerce.

Demostración en video:
[youtube https://www.youtube.com/watch?v=JaLp1wmtKlk]

El soporte al plugin se realiza directamente en [GitHub](https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/).

== Installation ==
1. Ingresa a tu Administrador (WP-Admin), luego Plugins -> Añadir Nuevo. Busca "WooCommerce Chilexpress Shipping". Presiona "Instalar ahora" y luego Actívalo.
También puedes instalarlo de forma manual: sube el plugin a tu WordPress y actívalo.
2. Luego ve a WooCommerce -> Ajustes -> Envío -> Chilexpress.
3. Configura las opciones. Importante asignar la ciudad de origen (desde donde despacharás los envíos).
Dejar el usuario y password (de la API de Chilexpress) en blanco para utilizar los datos de conexión por defecto (públicos) que Chilexpress provee.
4. Listo.

Ahora tus clientes podrán seleccionar Chilexpress para el envío de sus productos (dentro de Chile) y recibir el cálculo de costo de envío automáticamente.

== Frequently Asked Questions ==
= Extensión SOAP requerida.
La conexión a la API de Chilexpress se realiza a través de SOAP. Por lo tanto, tu servidor debe tener [activada](http://php.net/manual/en/book.soap.php) aquella extensión para poder utilizar este plugin.

= ¿Errores? ¿Sugerencias?
Reportar errores y enviar sugerencias directamente en [GitHub](https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues), por favor.

Ayuda y aportes (pull requests) son bienvenidos.

¡Gracias!

== Screenshots ==
1. Cálculo precio de envío en Carro de Compras.
2. Cálculo precio de envío en Finalizar Compra.
3. Configuración del plugin.

== Changelog ==
= 1.1.3 =
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/14
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/13
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/11#issuecomment-315484722

= 1.1.0 =
* Mejora: implementado el cálculo de precios en la calculadora rápida del carro de compras. Ver: https://www.youtube.com/watch?v=JaLp1wmtKlk
* Mejora: caché de Regiones y Ciudades configurable. Ver opciones del plugin. Default 24 horas.
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/11

= 1.0.9 =
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/10
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/10#issuecomment-314546595

= 1.0.7 =
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/9

= 1.0.6 =
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/6
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/8

= 1.0.5 =
* Fix: https://github.com/whooohq/whq-woocommerce-chilexpress-shipping/issues/4

= 1.0.4 =
* Fix: Transient cache id
* Fix: Cache busting

= 1.0.2 =
* Implementado Select2 para los campos de región y ciudad/localidad.
* Otras mejoras y bugfixes.

= 1.0.1 =
* Primera versión pública.

== Upgrade Notice ==
Activar y configurar.
