# 🎧 **Spotify Hit Predictor: Kaggle Weekend Challenge 🚀**  

![image](L.png)


## 🎯 **Contexto**
Este dataset contiene características extraídas de canciones utilizando la **Spotify Web API**. Las canciones están etiquetadas como **'Hit' (1)** o **'Flop' (0)** en función de ciertos criterios establecidos por el autor.  
La finalidad de este desafío es construir un **modelo de clasificación** capaz de predecir si una canción será un **'Hit'** o no. 🎵

---

## 🏆 **El Reto: Competición Navideña Kaggle** 🎄  

### 📌 **¿Qué vamos a hacer?**
Esta competición está organizada para los estudiantes del **Máster en Inteligencia Artificial (MIA)** de la escuela **EDEM**. Los profesores, **José Luis** y **Javier**, han preparado este reto especial para que os llevéis a casa durante **Navidades**. 🎁  

**¡Será el regalo perfecto para afilar vuestras habilidades en Machine Learning!** 🎓  

---

## ❄️ **¿Cómo se desarrolla la competición?**
1. **Train (80%)**: Datos de entrenamiento con etiquetas (`target`).
2. **Test (20%)**: Datos de prueba sin la columna objetivo. Aquí haréis las predicciones.
3. **Solution**: Conjunto de soluciones que utilizaremos para evaluar vuestras predicciones.

---

## 🔥 **Desafíos y Reglas**
1. **Limite de Submissions**: Las submissions estarán limitadas para hacer el reto más desafiante. ¡Pensad bien vuestras estrategias! 🧠
2. **Periodo de Competición**: Desde el inicio de las **Navidades** hasta el final de las fiestas. Tened tiempo para disfrutar el turrón, los villancicos... y el **machine learning**. 🎅
3. **Entrega**: Vuestro objetivo será realizar un análisis detallado y **presentarlo en clase** tras las vacaciones. La presentación será clave para defender vuestra solución.

---

## 🎄 **Un Toque Navideño** 🎄  
Esta competición tiene un toque muy especial:  
- **Fórmula de Navidad** 🎁: ¿Quién no quiere aprovechar la magia de las fiestas para crear el mejor modelo de predicción?  
- **Competición y Diversión**: Trabajad duro, pero también disfrutad. Aprovechad el espíritu navideño y que los **renos del Machine Learning** os lleven a la cima. 🦌  

---

## 📊 **Sobre el Dataset**
Este dataset se compone de varias características detalladas para cada canción.  

### 📌 **Atributos Principales**
- **track**: Nombre de la canción.  
- **artist**: Artista de la canción.  
- **uri**: Identificador de recurso de la canción.  
- **danceability**: Qué tan bailable es la canción (0.0 a 1.0).  
- **energy**: Medida de intensidad y actividad de la canción.  
- **key**: Tono de la canción.  
- **loudness**: Nivel de volumen promedio.  
- **mode**: Modalidad de la canción (0 = menor, 1 = mayor).  
- **speechiness**: Medida de palabras habladas en la pista.  
- **acousticness**: Confianza de que la canción sea acústica.  
- **instrumentalness**: Si la canción tiene voz o no.  
- **liveness**: Presencia de audiencia en la grabación.  
- **valence**: Positividad transmitida por la canción.  
- **tempo**: Velocidad de la canción en BPM.  
- **duration_ms**: Duración de la pista en milisegundos.  
- **chorus_hit**: Mejor estimación del inicio del estribillo.  
- **sections**: Número de secciones en la canción.  
- **target**:  
    - `1`: La canción fue un **Hit** (apareció en Billboard Hot-100).  
    - `0`: La canción no cumplió los criterios y se considera **Flop** (sin ánimo despectivo).  

Para más detalles, puedes consultar la documentación de la API de Spotify:  
👉 [Audio Features Spotify API](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/)

---

## 🎯 **Objetivo del Desafío**
Construid un **modelo de clasificación** que, dadas las características de las canciones, prediga si una canción será un **Hit** o un **Flop**.

---

## 🚀 **Entrega Final**
- **submission.csv**: Archivo con las predicciones sobre el conjunto de test.  
- **presentación**: Explicación del modelo, vuestra estrategia, dificultades enfrentadas y conclusiones.  

---

## 🎓 **Créditos**
Agradecemos a las siguientes herramientas y fuentes que hicieron posible este reto:
- [spotipy](https://pypi.org/project/spotipy/): Python module para la API de Spotify.
- [billboard](https://pypi.org/project/billboard.py/): Módulo de Python para extraer datos de Billboard.
- **Spotify**: Por ofrecer un API tan útil y detallada.

---

## 🎅 **¡A Disfrutar y a Competir!** 🎄  
Que esta Navidad no solo os traiga regalos, sino también el **modelo ganador**. ¡Sacad vuestro espíritu competitivo, disfrutad del proceso y que gane el mejor equipo! 🏆  

🎉 **¡Felices Fiestas y Feliz Machine Learning!** 🎉  

