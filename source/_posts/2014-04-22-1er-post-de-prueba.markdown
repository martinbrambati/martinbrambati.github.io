---
layout: post
title: "Conversion Improvement"
date: 2014-04-22 12:51:59 -0300
comments: true
categories: [Google Analytic, AB testing, Real Estate, Foreclosures, Conversiones]
---

Hace ya 3 meses empezamos con un proyecto interno con el objetivo de mejorar las conversiones de los sitios más grandes.

Como mi background es más técnico y menos analítico descubrí que es un buen punto de partida para entender mejor el negocio del RealEstate y conversion improvement.<!-- more -->


##Análisis del negocio

En USA, Foreclosures son casas en remate. Esto es porque sus dueños no pudieron seguir pagando la hipoteca. El negocio asociado a la compra/venta de foreclosures tuvo su momento de oro con la crisis de la burbuja financiera de Estados Unidos. En esa época, la gente no podía pagar entonces los bancos remataban las casas. 

En gral., el negocio del Foreclosure en USA tiene un pico de consumo en Febrero, luego continua bajando hasta Marzo/Abril y luego se plancha hasta Noviembre/Diciembre. Esto es importante para determinar en qué época del año hacer los AB testings en base al tráfico y nivel de conversiones del sitio.

En particular, el negocio de nuestros sitios es la registración paga del usuario. Los datos de la propiedad son visibles parcialmente mientras que el usuario no esté registrado. Los sitios más pequeños siguen otro modelo basado en publicidad paga, pero eso es otro tema.

##Conversion improvements

Al márgen del tipo de negocio que estemos manejando, siempre vamos a poder obtener métricas de conversiones. Una conversión es una acción a partir de la cual a nosotros nos signifca un beneficio. Ejemplos:

	Un usuario se registra en un newsletter
	Un usuario paga por registrarse

En gral. vamos a querer saber mucho más acerca de las condiciones en que se realiza esa conversión para poder potenciarla y que muchos más usuarios hagan lo mismo. Hay varias herramientas que permiten medir y mejorar las conversiones, personalmente prefiero <a href="http://www.google.com.ar/analytics/">Google Analytic</a>, pero también hay otras, como <a href="https://www.optimizely.com/">Optimizely</a> y <a href="https://www.kissmetrics.com/">Kiss Metrics</a>. La ventaja de Analytic es que es Gratis y permite configurarlo a gusto y piacere. Optimizely es una muy buena herramienta pero es carísima y salvo que tus sitios tengan un volúmen muy grande y que no sepas nada de programación, no lo uses. Kiss Metrics tiene un enfoque distinto, es pago (no tan caro) pero no muestra datos tan "duros" como Analytic, sino un poco más cocinados, está bueno si no querés ensuciarte mucho con los datos y tenés plata como para pagar la membresía.

##Analytic y AB testing

Después de mucho experimentar puedo concluir con toda seguridad que la mejor herramienta para mejorar conversiones son los AB testings, en donde se pueden testear 2 o más variantes de un "experimento" al mismo tiempo. 

El concepto de AB testing es importante, el hecho de testear en el mismo momento 2 versiones distintas, en las mismas condiciones.

	[IMG_EXPERIMENTO]

En nuestro caso, una conversión es cuando un usuario se registra. Es un formulario de 3 pasos + 1 paso al pagar en un servicio externo de pagos. Contamos también con un "Funnel" preconfigurado, el cual es muy útil.

	[IMG_FUNNEL_FORM]

Particularmente, en nuestros sitios, para mejorar las conversiones no solo fue necesario modificar el formulario de registro, sino ir más allá y más acá, es decir, analizar y modificar qué pasa antes y después y definimos así 3 sectores:

	Home page y listados
	Registro de usuario
	Formulario de pago

Cada una de las secciones tiene sus propios objetivos

	Home page y listados -> Bajar el rebote y mejorar el tiempo en página
	Registro de usuario -> Continuar hacia el formulario de pago
	Formulario de pago -> Usuario concreta el pago

Es decir, no alcanza con testear solo el formulario que hará que nuestro sitio convierta un poco más, sino que hay que verlo como un todo, como un sistema con partes que interactúan entre sí. 

### 300 million dollar "button"

Un ejemplo típico que siempre se repite es el del <a href="https://www.uie.com/articles/three_hund_million_button/">botón de 300 millones de dólares</a>. Muchos dicen: "cambiemos el color del botón" o "movamos de lugar este comentario", pero en realidad no están viendo que el cambio real vino de darle una mirada distinta a todo el proceso de pagos y la definición entera de lo que el sitio realmente hace y deja de hacer, y eso es lo importante!

###Cambiar lo que ves, mantener lo que no ves

Es importantísimo no cambiar nada más de lo que realmente queramos, de esa manera solo estaremos testeando lo que queremos testear. Siempre tenemos que saber qué cosa está compitiendo con qué. Eso no significa que no tengamos muchos AB tests al mismo tiempo.