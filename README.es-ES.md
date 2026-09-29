<div align="center">

![Biblioteca de prompts Kling 4.0](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts — Guía en español

Prompts prácticos de vídeo con IA para cine, anuncios de producto, UGC, diálogo, VFX, animación, comida, viajes, educación y redes sociales.

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · **Español** · [15 idiomas](docs/LANGUAGES.md)

[52 prompts](prompts/README.md) · [Guía de prompting](docs/PROMPT-GUIDE.md) · [Audio multilingüe](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **Estado del modelo (29-09-2026):** Kling 4.0 Flash abrió el acceso anticipado el 28 de septiembre para suscriptores Ultra anuales. Según el [anuncio oficial de Kling AI](https://sg.linkedin.com/company/kling-ai-api), la versión completa de Kling 4.0 y el acceso por API llegarán en octubre de 2026, sin fecha exacta publicada. Los **30 segundos por generación** corresponden a la versión completa anunciada; no son un límite verificado para Flash. Los prompts actuales duran entre 5 y 15 segundos.

## Novedades y disponibilidad de Kling 4.0

Según el [anuncio oficial de Kling AI en X](https://x.com/Kling_ai/status/2104596718067257458), Flash ya está en acceso anticipado para suscriptores Ultra anuales; el modelo 4.0 completo y la API están previstos para octubre de 2026. Para la versión completa se anuncian hasta 30 segundos por generación, 10 fotogramas clave, 15 referencias multimodales, salida de hasta 4K/10-bit HDR, audio estéreo y más idiomas y acentos. **No atribuyas estos límites a Flash sin comprobarlos.** Los 52 prompts existentes usan líneas de tiempo de 5 a 15 segundos. En FLAQ.AI, las páginas 4.0 de [texto a vídeo](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) e [imagen a vídeo](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) siguen marcadas como «Coming Soon»: no son una API 4.0 activa.

## Vídeos y prompts compartidos en X

**Revisado el 29-09-2026.** El [vídeo oficial de presentación](https://x.com/Kling_ai/status/2104596718067257458) es un montaje de la familia 4.0; su duración total no demuestra la duración de una generación Flash. Los casos siguientes son pruebas descritas por sus autores, no benchmarks oficiales ni reproducciones independientes de este proyecto. Consulta los vídeos y prompts originales en sus publicaciones; aquí no se copian.

| Publicación original | Qué probar en el prompt |
|---|---|
| [Umesh: persecución nocturna de un gato, 20 s](https://x.com/umesh_ai/status/2104595267794460949) · [prompt original](https://x.com/umesh_ai/status/2104595270671724936) | Mantén un solo protagonista, una ruta conectada y un evento físico por lugar; la cámara sigue sin cortes. |
| [OscarAI: concierto animado, 20 s, con prompt](https://x.com/Artedeingenio/status/2104829034299351079) | El autor prefiere, en sus primeras pruebas, instrucciones breves y directas, aunque advierte que la ejecución no fue exacta. Ensaya sujeto → cambio → cámara → final. |
| [とすくん: cambio de tiempo, 15 s](https://x.com/tokyo_Valentine/status/2104810060811833710) · [prompt original](https://x.com/tokyo_Valentine/status/2104810064750239987) | Usa la ficha del personaje solo para identidad y vestuario; indica por separado cuándo cambian clima, luz y actuación. |
| [Alexandra Dekimpe: pruebas de producción](https://x.com/HadesDesign/status/2104878440889417957) | Sustituye emociones abstractas por microacciones visibles; fija la causalidad con «solo después»; da el diálogo exacto o pide silencio. Son observaciones de la autora. |
| [Aswin Aji Raj: UGC en hindi, 20 s](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | El prompt completo no se publicó. Define hablante y frase exacta; revisa pronunciación, sincronización labial y afirmaciones comerciales. |
| [@plasm0: comparación 3.0/Flash con el mismo prompt](https://x.com/plasm0/status/2104597949485629557) | Conserva prompt y referencias para una prueba A/B y anota los ajustes. Un par de vídeos no constituye una evaluación formal. |

**Ejercicio vertical original de 15 s, aún sin probar** (fuera de los 52 prompts del catálogo; no reproduce textos de X):

~~~text
[SUJETO/REFERENCIA] Una sola luz recargable para bicicleta, sin marca, con carcasa grafito mate y un único interruptor ámbar. Si se aporta una imagen, solo fija la forma de la luz.
[ESCENA/CÁMARA] Taller de bicicletas tranquilo al atardecer. Un plano continuo y cercano sigue las manos de la mecánica, la luz y el manillar. Luz natural de ventana; sin cortes ni teletransportes.
[0–4 s] Coloca la luz apagada junto al manillar; se ven ambas manos y el soporte.
[4–8 s] Encaja la luz en el soporte. Solo después del clic de fijación pulsa con el pulgar el interruptor ámbar.
[8–12 s] La luz se enciende una sola vez e ilumina la rueda delantera y un pequeño sector del suelo. La cámara se desplaza lateralmente para mostrar el haz.
[12–15 s] Suelta el manillar; la luz permanece firme. Mantén un encuadre final estable.
[AUDIO/RESTRICCIONES] Ambiente del taller, un clic de montaje y un clic del interruptor. Sin voz ni música. Conserva forma, número de manos, posición y dirección del haz. Sin marcas, luces extra ni saltos de montaje injustificados.
~~~

Prueba tanto instrucciones breves como textos más largos pero estructurados. Anota modo, duración, referencias y resultado antes de llamarlos «probados». Se aceptan aportaciones originales mediante la [guía de contribución](CONTRIBUTING.md).

## Qué incluye

- 52 prompts completos y originales en 13 colecciones de producción.
- Flujos de texto a vídeo, imagen a vídeo, fotograma inicial/final y referencia de sujeto.
- Dirección por segundos: plano, cámara, actuación, física, sonido y restricciones.
- Patrones de diálogo en español, chino, inglés, japonés y coreano.
- Cine, producto, UGC, acción, animación, moda, música, comida, viajes, espacios, educación y contenido social.
- Imágenes creadas desde cero para este repositorio.

## Estructura básica

```text
[SALIDA] duración, relación de aspecto, toma única/multiplano y acabado visual
[CONTINUIDAD] rasgos fijos del personaje, vestuario, producto y accesorios
[ESPACIO] lugar, hora, luz y posiciones iniciales
[TIEMPO] una acción principal + una intención de cámara por segmento
[INTERPRETACIÓN] mirada, respiración, contacto, emoción, peso y velocidad
[AUDIO] hablante (idioma, tono, ritmo) + ambiente + foley sincronizado
[RESTRICCIONES] identidad, manos, dirección, luz, texto, logos y deformaciones
```

## Ejemplo de diálogo en español

```text
Lucía (español de México, tono sereno): «Pensé que no vendrías.»
Mateo (español de España, voz baja): «Yo también.»
Solo se mueve la boca de Lucía durante su frase y la de Mateo durante la suya.
Mantén cada frase en el idioma escrito. Sin traducción, subtítulos ni diálogo adicional.
La lluvia y el zumbido del tren continúan a bajo volumen debajo de ambas voces.
```

Indica la variante regional solo cuando aporte a la escena y evita caricaturizar acentos. Verifica siempre nombres, números, pronunciación y texto exacto. Para subtítulos accesibles, es preferible añadir texto revisado en posproducción.

## Recomendados

- [Reencuentro multilingüe en una estación](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [Anuncio de bebida botánica](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [Persecución de ciencia-fantasía](prompts/action-and-vfx.md#1-the-glass-manta-pursuit)
- [Bucle cómico del paraguas](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

Consulta el [catálogo completo](prompts/README.md).

## Originalidad y uso responsable

Todos los textos y prompts se han creado para este proyecto; no reutilizan entradas ni miniaturas de terceros. No uses rostros, voces, marcas, personajes o música sin permiso. Revisa afirmaciones publicitarias, datos educativos, seguridad, arquitectura, artesanía y contexto cultural antes de publicar.

Fuentes oficiales: [anuncio de Kling AI 3.0 por Kuaishou](https://ir.kuaishou.com/news-releases/news-release-details/kling-ai-launches-30-model-ushering-era-where-everyone-can-be) · [guía oficial de Kling Video 3.0](https://app.klingai.com/cn/quickstart/klingai-video-3-model-user-guide)

## Acerca de FLAQ.AI

> A 29-09-2026, las páginas FLAQ.AI de 4.0 [texto a vídeo](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) e [imagen a vídeo](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) indican «Coming Soon». El acceso anticipado a Flash en Kling no implica que la API 4.0 de FLAQ.AI esté disponible.

[FLAQ.AI](https://flaq.ai/) es una plataforma web y una capa de API unificada para flujos con modelos de imagen, vídeo y lenguaje. Actualmente ofrece páginas para [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) e [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). Este repositorio no afirma que Kling 4.0 esté disponible en FLAQ.AI. Comprueba en las páginas en vivo los nombres, controles, precios, duración, resolución y esquema de API antes de producir.
