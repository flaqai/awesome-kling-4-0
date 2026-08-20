<div align="center">

![Biblioteca de prompts Kling 4.0](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts — Guía en español

Prompts prácticos de vídeo con IA para cine, anuncios de producto, UGC, diálogo, VFX, animación, comida, viajes, educación y redes sociales.

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · **Español**

[24 prompts](prompts/README.md) · [Guía de prompting](docs/PROMPT-GUIDE.md) · [Audio multilingüe](docs/MULTILINGUAL-AUDIO.md)

</div>

> **Estado del modelo (20-08-2026):** Kling 4.0 no ha sido anunciado oficialmente. La versión principal verificable más reciente es Kling AI 3.0, publicada el 5 de febrero de 2026. Este repositorio es una vista previa comunitaria e independiente «4.0-ready», basada en funciones confirmadas de 3.0. No presenta como oficiales datos no verificados sobre vídeo 4K, precios, API o duración.

## Qué incluye

- 24 prompts completos y originales para 12 escenarios de producción.
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
