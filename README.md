# 🐥 Curso de Machine Learning con la Miss Yera

Curso completo de machine learning en 7 clases con un solo hilo narrativo, **PolliCreditos**, una fintech peruana de microcréditos para bodegas y emprendedores. Cada clase resuelve un pedido real del CEO, y cada error del modelo cuesta soles concretos. De tu primera predicción a un proyecto final de fuga de clientes con estándar senior.

Cada clase tiene su video en la playlist de YouTube, su notebook para practicar en Colab sin instalar nada, quizzes con alternativas, la trampa de la Miss para cazar errores, la capa de matemática detrás de cada concepto y autoverificación del reto.

**Regla de oro del curso, nadie ejecuta una celda sin predecir en voz alta qué va a pasar.**

## 🧭 El mapa del curso

```mermaid
flowchart TB
  subgraph f1[ ]
    direction LR
    C1[Clase 1<br>Introducción al ML] --> C2[Clase 2<br>Supervisado y no supervisado] --> C3[Clase 3<br>Preparación y features] --> C4[Clase 4<br>Regresión]
  end
  subgraph f2[ ]
    direction LR
    C5[Clase 5<br>Clasificación] --> C6[Clase 6<br>Evaluación y validación] --> C7[Clase 7<br>Proyecto final]
  end
  f1 --> f2
  style f1 fill:transparent,stroke:none
  style f2 fill:transparent,stroke:none
  classDef destacado fill:#FF1493,stroke:#FF1493,color:#FFFFFF
  class C7 destacado
```

## 📺 Las clases

| # | Clase | Video | Notebook |
|---|---|---|---|
| 1 | **Tu primera predicción, ¿a quién le presta PolliCreditos?** | _pendiente_ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soymissyera/ClasesMLPollito/blob/main/clases/clase_01/clase_01_introduccion_ml_estudiantes.ipynb) |
| 2 | **Supervisado o no supervisado, el mapa que evita el 80% de los errores** | _pendiente_ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soymissyera/ClasesMLPollito/blob/main/clases/clase_02/clase_02_supervisado_no_supervisado_estudiantes.ipynb) |
| 3 | **El 70% del trabajo real, limpiar las solicitudes de crédito** | _pendiente_ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soymissyera/ClasesMLPollito/blob/main/clases/clase_03/clase_03_preparacion_features_estudiantes.ipynb) |
| 4 | **Regresión, ¿qué línea de crédito darle a cada bodega?** | _pendiente_ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soymissyera/ClasesMLPollito/blob/main/clases/clase_04/clase_04_regresion_estudiantes.ipynb) |
| 5 | **Clasificación, ¿quién caerá en mora? Cada error cuesta soles** | _pendiente_ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soymissyera/ClasesMLPollito/blob/main/clases/clase_05/clase_05_clasificacion_estudiantes.ipynb) |
| 6 | **Overfitting en vivo, la auditoría del regulador** | _pendiente_ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soymissyera/ClasesMLPollito/blob/main/clases/clase_06/clase_06_evaluacion_validacion_estudiantes.ipynb) |
| 7 | **Proyecto final, la fuga de los buenos clientes de punta a punta** | _pendiente_ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soymissyera/ClasesMLPollito/blob/main/clases/clase_07/clase_07_proyecto_final_estudiantes.ipynb) |

Los links de video se completan a medida que salen los episodios de la playlist.

## 🎒 Cómo usar este repositorio

1. Abre el notebook de la clase con su botón de Colab, no necesitas instalar nada.
2. Sigue el video completando los espacios marcados con ✏️ TU TURNO.
3. Usa la celda de autoverificación para confirmar que tu reto está completo.
4. Comparte tu resultado en los comentarios del video con el hashtag #PollitosML.
5. La solución oficial de cada reto se publica en `soluciones/` una semana después del video. Intenta primero, ahí está el aprendizaje.

## 📁 Estructura

- `clases/` los notebooks de estudiantes, uno por clase, con espacios para completar y autoverificación.
- `soluciones/` la versión resuelta y ejecutada de cada clase (se publica con delay).
- `assets/` los diagramas del curso en Mermaid, PNG y las animaciones GIF.
- `requirements.txt` para correr en local (en Colab no hace falta).

## 🐥 ¿Quién enseña?

Yera Flores (Miss Yera), consultora de IA y datos, y profe de este gallinero. Más cursos y el Full Day de IA en [missyera.com](https://missyera.com), y análisis gratuito de tu CV con IA en [misscv.com](https://misscv.com).

**Chau, chau. Bye, bye. 💋**

<sub>© 2026 Yera Flores (Miss Yera) · @soymissyera</sub>
