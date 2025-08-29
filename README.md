# IAs 2025

## Autor: Mauricio Gastón Lúquez - Dev Fullstack e Instructor

Para más información, visita [mi perfil de LinkedIn](https://www.linkedin.com/in/mauricio-gast%C3%B3n-l%C3%BAquez-aaa78571/) o [mi GitHub](https://github.com/HX-MLuquez)

### **Modelos y Herramientas de IA 2025**

**Leyenda Rápida:**

- **G:** Generativa (crea contenido nuevo)
- **P:** Predictiva / Analítica (analiza, extrae o clasifica información)
- **Razonamiento:** Capacidades explícitas o versiones orientadas al razonamiento complejo (ej. CoT).

---

### **Texto (LLMs, Chat y Herramientas de Escritura)**

#### **Asistentes de Chat y Generación General (Modelos Fundacionales)**

| Nombre (Versión)            | Creador            | Freemium / Pago        | Límites / Notas                                                                                                                              | G/P | Razonamiento | Arquitectura      | Enlace Oficial     | Uso Recomendado                                                                                          |
| :-------------------------- | :----------------- | :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------- | :-: | :----------- | :---------------- | :----------------- | :------------------------------------------------------------------------------------------------------- |
| **GPT-4o / GPT-4 Turbo**    | OpenAI             | Freemium / Plus / API  | **GPT-4o** es el modelo insignia: nativo multimodal, rápido y conversacional. **GPT-4 Turbo** sigue en uso en planes legacy y empresariales. |  G  | ✅           | Transformer       | OpenAI             | Asistentes de voz, análisis multimodal, creación de contenido creativo.                                  |
| **Claude 3.5 Sonnet**       | Anthropic          | Freemium / Pago        | Supera a Opus en velocidad y benchmarks. Introduce "Artifacts", un espacio de trabajo interactivo para código y documentos.                  |  G  | ✅✅         | Transformer       | Anthropic          | Codificación avanzada, análisis visual de datos, redacción colaborativa en tiempo real.                  |
| **Claude 3 (Opus / Haiku)** | Anthropic          | Freemium / Pago        | **Opus:** Máxima potencia para rigor analítico. **Haiku:** El más rápido y económico para interacciones instantáneas.                        |  G  | ✅           | Transformer       | Anthropic          | **Opus:** Investigación profunda, análisis legal/financiero. **Haiku:** Chatbots de servicio al cliente. |
| **Gemini 2.5 Pro**          | Google / DeepMind  | Pago (Gemini Advanced) | Versión insignia de la familia 2.5, enfocada en razonamiento complejo, código avanzado y tareas multi-paso.                                  |  G  | ✅           | Transformer / MoE | Google Gemini      | Análisis de datos complejos, desarrollo de software, planificación estratégica.                          |
| **Gemini 2.5 Flash**        | Google / DeepMind  | Freemium / API         | Optimizado para alta velocidad, bajo costo y baja latencia. Ideal para aplicaciones que requieren respuestas en tiempo real.                 |  G  | Parcial      | Transformer       | Google AI for Devs | Asistentes de chat en vivo, resumen rápido, aplicaciones web interactivas.                               |
| **LLaMA 3.1 (Familia)**     | Meta               | Open-source            | Modelos abiertos de alto rendimiento (405B, 70B, 8B). Su licencia permisiva permite el uso comercial y fomenta un ecosistema de fine-tuning. |  G  | Parcial      | Transformer       | Meta Llama         | Desarrollo local, asistentes especializados con control total sobre los datos, investigación.            |
| **DeepSeek**                | DeepSeek AI        | Libre / API            | Un LLM de alto rendimiento, open-source, con un enfoque especial en capacidades de codificación.                                             |  G  | Parcial      | Transformer       | DeepSeek           | Desarrollo de software, fine-tuning para tareas de programación específicas.                             |
| **Grok (Familia)**          | xAI                | Pago (X Premium+)      | Diseñado con acceso en tiempo real a la plataforma X (Twitter) y un tono de respuesta "espicier", menos filtrado.                            |  G  | ✅           | Transformer / MoE | xAI Grok           | Búsqueda de información en tiempo real, análisis de tendencias sociales, periodismo.                     |
| **Copilot**                 | Microsoft / GitHub | Freemium / Pago        | El estándar de la industria para asistencia en programación. Integrado directamente en el editor de código (IDE).                            |  G  | ✅           | Transformer       | GitHub Copilot     | Autocompletado de código, depuración, explicación y refactorización para desarrolladores.                |

#### **Búsqueda y Respuestas Conversacionales**

| Nombre (Versión)  | Creador    | Freemium / Pago        | Límites / Notas                                                                                                        | G/P | Razonamiento | Arquitectura  | Enlace Oficial | Uso Recomendado                                                                                    |
| :---------------- | :--------- | :--------------------- | :--------------------------------------------------------------------------------------------------------------------- | :-: | :----------- | :------------ | :------------- | :------------------------------------------------------------------------------------------------- |
| **Perplexity AI** | Perplexity | Freemium / Pro         | "Motor de respuestas" que combina un LLM con búsqueda web en tiempo real para dar respuestas precisas y citadas.       | G/P | ✅           | Propia / LLMs | Perplexity AI  | Investigación, verificación de hechos, tareas que requieran respuestas actualizadas y con fuentes. |
| **Poe by Quora**  | Quora      | Freemium / Suscripción | Agregador que permite acceder y comparar respuestas de múltiples modelos (GPT, Claude, etc.) desde una única interfaz. |  G  | ✅           | Plataforma    | Poe            | Comparar el rendimiento de diferentes LLMs, creación de bots personalizados.                       |

#### **Herramientas de Escritura, SEO y Productividad**

| Nombre (Versión)   | Creador        | Freemium / Pago    | Límites / Notas                                                                                                        | G/P | Razonamiento | Arquitectura    | Enlace Oficial | Uso Recomendado                                                               |
| :----------------- | :------------- | :----------------- | :--------------------------------------------------------------------------------------------------------------------- | :-: | :----------- | :-------------- | :------------- | :---------------------------------------------------------------------------- |
| **Jasper**         | Jasper         | Pago               | Asistente de escritura maduro, enfocado en contenido de marca y campañas de marketing a escala.                        |  G  | ❌           | LLMs (varios)   | Jasper.ai      | Creación de contenido para empresas, manteniendo un tono de voz consistente.  |
| **Copy.ai**        | Copy.ai        | Freemium / Pro     | Plataforma de copywriting enfocada en marketing y ventas. Genera textos para anuncios, emails, blogs y redes sociales. |  G  | ❌           | LLM (propio)    | Copy.ai        | Equipos de marketing para acelerar la creación de contenido publicitario.     |
| **Grammarly**      | Grammarly      | Freemium / Premium | Asistente de escritura con sugerencias de tono, claridad y estilo, ahora con funciones generativas.                    | P/G | ❌           | NLP / LLM       | Grammarly      | Mejorar la calidad de cualquier texto escrito, desde emails hasta documentos. |
| **DeepL**          | DeepL GmbH     | Freemium / Pro     | Considerado el traductor automático con mayor matiz y precisión del mercado.                                           |  P  | ❌           | Transformer     | DeepL          | Traducción de documentos profesionales donde la precisión es crítica.         |
| **Genei.io**       | Genei          | Freemium / Pago    | Herramienta de investigación que procesa documentos (PDFs, webs) para extraer información clave y generar resúmenes.   | P/G | ❌           | NLP / LLM       | Genei.io       | Estudiantes e investigadores para acelerar la revisión de bibliografía.       |
| **Originality.ai** | Originality.ai | Pago               | Detector de plagio y de texto generado por IA para editores, SEOs y académicos.                                        |  P  | ❌           | Clasificador IA | Originality.ai | Asegurar la originalidad del contenido y la integridad académica.             |
| **Neuraltext**     | Neuraltext     | Pago               | Plataforma de contenido SEO que automatiza la creación de borradores optimizados para buscadores.                      |  G  | ❌           | LLM             | Neuraltext     | Equipos de SEO para crear artículos de blog que posicionen en Google.         |

---

### **Imagen (Generación, Edición y Análisis)**

#### **Generación de Propósito General y Artístico**

| Nombre (Versión)         | Creador           | Freemium / Pago               | Límites / Notas                                                                                       | G/P | Arquitectura                     | Enlace Oficial  | Uso Recomendado                                                                              |
| :----------------------- | :---------------- | :---------------------------- | :---------------------------------------------------------------------------------------------------- | :-: | :------------------------------- | :-------------- | :------------------------------------------------------------------------------------------- |
| **Midjourney V6.1**      | Midjourney Inc.   | Pago (vía Discord)            | El rey del estilo artístico y cinematográfico. La v6 mejora drásticamente la coherencia y el texto.   |  G  | Diffusion (propia)               | Midjourney      | Arte digital, fotografía conceptual, imágenes con estética profesional.                      |
| **DALL·E 3**             | OpenAI            | Freemium / Pago               | Integrado en ChatGPT y Copilot. Su fuerte es la comprensión de prompts largos y conversacionales.     |  G  | Diffusion + Transformer          | OpenAI DALL-E 3 | Ilustraciones, marketing de contenidos, conceptualización de ideas.                          |
| **Stable Diffusion 3.5** | Stability AI      | Open-source / Pago            | La opción más flexible y abierta. Puede ejecutarse localmente. La v3.5 mejora la calidad fotográfica. |  G  | Multimodal Diffusion Transformer | Stability AI    | Proyectos comerciales con control total, experimentación, flujos de trabajo personalizados.  |
| **Imagen 3**             | Google / DeepMind | Integrado en productos Google | Modelo de Google enfocado en fotorrealismo, comprensión del lenguaje y generación de texto legible.   |  G  | Diffusion                        | Google DeepMind | Creación de imágenes realistas, prototipado rápido, integración con el ecosistema de Google. |
| **Ideogram 1.0**         | Ideogram          | Freemium / Plus               | Destaca por su increíble capacidad para generar texto legible y coherente dentro de las imágenes.     |  G  | Diffusion                        | Ideogram        | Creación de logos, pósters, diseños tipográficos y memes.                                    |
| **StyleGAN3**            | NVIDIA            | Open-source                   | Arquitectura GAN especializada en la generación de rostros y texturas hiperrealistas.                 |  G  | GAN                              | NVIDIA Research | Producción de imágenes de alta fidelidad tipo "faces", arte procedural.                      |

#### **Plataformas Creativas y de Diseño**

| Nombre (Versión)               | Creador       | Freemium / Pago | Límites / Notas                                                                                             | G/P | Arquitectura               | Enlace Oficial             | Uso Recomendado                                                                          |
| :----------------------------- | :------------ | :-------------- | :---------------------------------------------------------------------------------------------------------- | :-: | :------------------------- | :------------------------- | :--------------------------------------------------------------------------------------- |
| **Leonardo AI**                | Leonardo AI   | Freemium / Pago | Suite creativa completa con múltiples modelos, fine-tuning y herramientas de edición en tiempo real.        |  G  | Diffusion / Varios         | Leonardo AI                | Diseño de personajes para videojuegos, assets gráficos, imágenes con estilo consistente. |
| **Microsoft Designer**         | Microsoft     | Freemium        | Herramienta de diseño fácil de usar, integrada con DALL-E 3, para redes sociales y diseños rápidos.         |  G  | Diffusion                  | Microsoft Designer         | Marketing, redes sociales, usuarios que necesitan diseños visuales rápidos.              |
| **Krea**                       | Krea AI       | Freemium / Pro  | Plataforma enfocada en el control creativo en tiempo real, permitiendo "dirigir" la generación con bocetos. |  G  | Diffusion (en tiempo real) | Krea                       | Artistas y diseñadores que buscan un control interactivo sobre la generación.            |
| **Playground**                 | Playground AI | Freemium / Pro  | Combinación de generador de imágenes y editor social. Permite remezclar creaciones de otros.                |  G  | Diffusion                  | Playground                 | Creación social, experimentación con estilos, edición de imágenes generadas.             |
| **Recraft**                    | Recraft       | Freemium / Pro  | Especializado en la generación de gráficos vectoriales (SVG), íconos y ilustraciones con estilo de marca.   |  G  | Propia / Vector Diffusion  | Recraft                    | Diseñadores de UI/UX, creación de brand kits y material de marketing vectorial.          |
| **This Person Does Not Exist** | Philip Wang   | Libre           | Ejemplo clásico de un modelo GAN que genera rostros humanos hiperrealistas pero ficticios.                  |  G  | GAN (StyleGAN)             | This Person Does Not Exist | Material de ejemplo, avatares, demostración del poder de las arquitecturas GAN.          |

#### **Mejora y Herramientas Específicas de Imagen**

| Nombre (Versión) | Creador   | Freemium / Pago | Límites / Notas                                                                                            | G/P | Arquitectura           | Enlace Oficial | Uso Recomendado                                                            |
| :--------------- | :-------- | :-------------- | :--------------------------------------------------------------------------------------------------------- | :-: | :--------------------- | :------------- | :------------------------------------------------------------------------- |
| **Remini**       | Remini    | Freemium / Pago | Especializado en mejorar la calidad de fotos antiguas, borrosas o de baja resolución.                      | P/G | IA (propia)            | Remini         | Restauración de fotos familiares, mejora de la calidad de imágenes.        |
| **Google Lens**  | Google    | Libre           | Herramienta de análisis y reconocimiento visual. Identifica objetos, texto y lugares.                      |  P  | Visión por Computadora | Google Lens    | Búsqueda visual, traducción en tiempo real, identificación de objetos.     |
| **Hotpot.ai**    | Hotpot.ai | Freemium / Pago | Colección de herramientas para tareas específicas: restauración de fotos, eliminación de fondos, etc.      | P/G | Varios modelos de IA   | Hotpot.ai      | Tareas de edición de imágenes rápidas y automatizadas para no-diseñadores. |
| **VanceAI**      | VanceAI   | Pago            | Suite de herramientas de mejora de imagen enfocada en la calidad profesional (resolución, ruido, nitidez). |  P  | IA (propia)            | VanceAI        | Fotógrafos que necesitan mejorar la calidad técnica de sus imágenes.       |

---

### **Video y Audio (Generación y Síntesis)**

| Nombre (Versión)       | Creador    | Freemium / Pago         | Límites / Notas                                                                                                    | G/P | Arquitectura            | Enlace Oficial              | Uso Recomendado                                                                    |
| :--------------------- | :--------- | :---------------------- | :----------------------------------------------------------------------------------------------------------------- | :-: | :---------------------- | :-------------------------- | :--------------------------------------------------------------------------------- |
| **Sora**               | OpenAI     | Acceso limitado / Pago  | El referente en calidad cinematográfica de texto-a-video. Genera videos de hasta 60 segundos.                      |  G  | Diffusion + Transformer | OpenAI Sora                 | Prototipos de anuncios, storyboards animados, contenido visual de alta fidelidad.  |
| **Veo**                | Google     | Acceso limitado / Pago  | Competidor directo de Sora, enfocado en alta definición (1080p) y comprensión de términos cinematográficos.        |  G  | Diffusion Transformer   | Google DeepMind             | Producción de video para redes sociales, clips conceptuales para marketing.        |
| **Runway Gen-3**       | Runway     | Freemium / Pago         | Más que un generador, es una suite de edición de video con IA para un control granular del movimiento y estilo.    |  G  | Video Models            | RunwayML                    | Artistas visuales, cineastas, edición de video asistida por IA.                    |
| **Kling**              | Kuaishou   | Acceso limitado (China) | Principal competidor de Sora de los creadores de TikTok (versión china). Genera video de hasta 2 minutos en 1080p. |  G  | Diffusion + Transformer | (No hay web oficial global) | Creación de videos cortos para redes sociales, narrativa visual de mayor duración. |
| **ElevenLabs**         | ElevenLabs | Freemium / Pago         | Líder en síntesis y clonación de voz. Produce voces ultrarrealistas que capturan emociones.                        |  G  | Deep Learning (Voz)     | ElevenLabs                  | Doblaje, audiolibros, asistentes de voz personalizados.                            |
| **Suno (v4.5)**        | Suno       | Freemium / Pago         | Genera canciones completas (letra, voz, instrumentación) a partir de texto. La v4.5 mejora la calidad.             |  G  | Transformer (Audio)     | Suno AI                     | Creación de jingles, bandas sonoras para videos, prototipado musical.              |
| **Udio**               | Udio       | Freemium / Pago         | Competidor directo de Suno, elogiado por la naturalidad de las voces y la complejidad musical.                     |  G  | Transformer (Audio)     | Udio                        | Producción de pistas musicales, creación de música para proyectos creativos.       |
| **Whisper (large-v3)** | OpenAI     | Open-source             | El estándar de oro para la **transcripción** de audio a texto (ASR). Precisión casi humana.                        |  P  | Transformer / ASR       | OpenAI Whisper              | Transcripción de entrevistas, subtitulado de videos, análisis de audio.            |
| **Jukebox**            | OpenAI     | Research / Open-source  | Modelo histórico de investigación para generar audio raw con canto. Computacionalmente intensivo.                  |  G  | VQ-VAE + Transformer    | OpenAI Research             | Investigación en generación musical, experimentación.                              |

---

### **IA Predictiva y Plataformas de Machine Learning**

| Nombre (Plataforma/Modelo) | Creador      | Tipo / Licencia          | Notas Clave                                                                                                     | G/P | Arquitectura            | Enlace Oficial | Uso Recomendado                                                                                              |
| :------------------------- | :----------- | :----------------------- | :-------------------------------------------------------------------------------------------------------------- | :-: | :---------------------- | :------------- | :----------------------------------------------------------------------------------------------------------- |
| **XGBoost**                | DMLC         | Biblioteca (Open-source) | El algoritmo más eficiente y preciso para datos tabulares (hojas de cálculo, bases de datos).                   |  P  | Gradient Boosting       | XGBoost        | Detección de fraude, modelado de riesgo crediticio, predicción de la fuga de clientes.                       |
| **TensorFlow**             | Google       | Framework (Open-source)  | Framework fundamental para construir y entrenar modelos de Machine Learning y Deep Learning a cualquier escala. |  P  | Deep Learning Framework | TensorFlow     | Visión por computadora, NLP, investigación y desarrollo de nuevos modelos de IA.                             |
| **Vertex AI**              | Google Cloud | Plataforma MLOps (Pago)  | Plataforma unificada para gestionar todo el ciclo de vida del Machine Learning: de los datos al despliegue.     |  P  | AutoML Platform         | Vertex AI      | Empresas que necesitan operacionalizar la IA, forecasting de demanda, personalización a escala.              |
| **H2O Driverless AI**      | H2O.ai       | Plataforma AutoML (Pago) | Plataforma de "AutoML" que automatiza gran parte del trabajo del científico de datos.                           |  P  | AutoML Platform         | H2O.ai         | Acelerar el desarrollo de modelos predictivos, análisis de seguros, optimización de la cadena de suministro. |

---

## 🎨 **Características de Diseño:**

- **Diseño glassmorphism** con efectos de blur y transparencias
- **Gradientes vibrantes** y animaciones fluidas
- **Orbs flotantes** animados en el fondo
- **Responsive design** que se adapta a móviles
- **Animaciones CSS** sofisticadas con delays escalonados

## 🚀 **Funcionalidades Interactivas:**

- **Búsqueda en tiempo real** por nombre, creador, descripción o uso
- **Filtros dinámicos** por categoría, pricing y características
- **Estadísticas animadas** que se actualizan según los filtros
- **Cards interactivos** con efectos hover y gradientes coloridos
- **Badges informativos** para identificar rápidamente las características

## 📊 **Organización del Contenido:**

- **Categorías visuales:** Texto, Imagen, Video/Audio, ML
- **78 herramientas organizadas** según tu documento
- **Enlaces directos** a cada herramienta
- **Información completa** de cada IA con uso recomendado

## ✨ **Efectos Especiales:**

- **Animaciones de entrada** escalonadas para las cards
- **Efectos de luz** en los enlaces
- **Contadores animados** en las estadísticas
- **Transiciones suaves** en todos los elementos

La aplicación es completamente autónoma (HTML puro con CSS y JavaScript vanilla), fácil de usar y con un diseño atractivo.
