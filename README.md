# E-commerce

* **Track:** _Especialización Front-end_
* **Curso:** _CONSTRUYE UNA SINGLE PAGE APP (SPA) MULTI-USUARIO CONSUMIENDO DATA REMOTA_
* **Unidad:** _Producto final_

***
## Descripción
Crear una app e-commerce con los principios de SPA (Single page aplication). Para ello, se utilizará:

1. API de productos (Descripción, precios, etc), como la de Mercado Libre.

2. API que permita la compra por parte del usuario, que puede ser Paypal, Stripe o cualquier otra que sirva para lo mismo.

3. Desplegar el repositorio a GH Pages.


## Concepto de la app web y flujo

1. El nombre del e-commerce es **Buy Smart**, brinda la opción de ver y comprar smartphones y algunos pocos artículos smart relacionados mediante la presentación de una información enfocada en el nombre del modelo, su costo, disponibilidad y la posibilidad de su costo en cuotas y números de cuotas. 

2. El flujo de la aplicación será de la siguiente forma:

* Página principal que da la bienvenida y le solicita al usuario a iniciar sesión. Al dar clic en el botón de iniciar sesión, se redigirá a la siguiente vista.

![Responsive-Desktop](public/assets/docs/index.JPG)

* En la vista de iniciar sesión, se solicita ingresar el correo electrónico y en una siguiente vista, se solicita ingresar la contraseña.

![Responsive-Desktop](public/assets/docs/login.JPG)

![Responsive-Desktop](public/assets/docs/login-password.JPG)

* Luego de iniciar sesión, se redirige a la vista principal donde se presentan los productos con su información respectiva. Además, se presenta un botón que le indica al usuario que puede dirigirse a hacer la compra. Esto lo llevará a poder hacer el pago con paypal.

![Responsive-Desktop](public/assets/docs/home-flow.gif)

## Herramientas

Para este proyecto, se usó las herramientas tecnológicas de HTML5, Materialize, CSS3, page.js, handlebars, API de mercado libre y API de paypal.