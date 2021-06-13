# Gbody JS by Giiber Developer

Esta pequeña libreria en desarrollo, es para las personas que estam comenzando en la programacion.

## ¿Cómo comenzar?

Puedes comenzar añadiendo este link a tu HTML mediante el **script** recuerda.
siempre colocalo de primero antes de los otros script que tengas agregado!

## ¿Cómo Usarlo?

Es muy facil, solo tienes que llamar una funcion añadir datos, por ejemplo!

image_({
	src: "https://github.com/Tufowin/gameX/raw/main/img/bg/bg2.png",
	container: "body",
	clase: "imagen_GbodyJS", ## <-- (.imagen_GbodyJS)

	// Información de carga
	loaded: ()=> { alert('¡La imagen se ha cargado!'); },
	error: ()=> { alert('Error, ¡algo anda mal!') }
})

audio_({
	src: "./mp3/musica.mp3",
	clase: "audio_GbodyJS" <-- (.audio_GbodyJS),
	container: "#contenedor",
	preload: true,
	autoplay: true,
	controls: true,

	// Información de carga
	loaded: function() { contenido }; |o| ()=> { contenido },
	error: function() { contenido }; |o| ()=> { contenido }
})

video_({
	src: "./videos/video.mp4",
	clase: "video_GbodyJS" <-- (.video_GbodyJS),
	container: ".contenedor",
	preload: true,
	autoplay: true,
	controls: true,

	// Información de carga
	loaded: function() { contenido }; |o| ()=> { contenido },
	error: function() { contenido }; |o| ()=> { contenido }
})