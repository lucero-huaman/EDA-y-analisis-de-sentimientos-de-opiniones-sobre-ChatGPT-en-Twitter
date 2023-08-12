EDA y análisis de sentimientos de opiniones sobre CHATGPT en Twitter
====================================================================

Contexto
--------

 En este estudio, se llevó a cabo un análisis exhaustivo de la opinión pública en relación con la aparición de ChatGPT, una innovadora tecnología de procesamiento del lenguaje natural desarrollada por OpenAI.

Carga de datos
--------------

 Se usó un dataset de 478,346 datos proporcionado por kaggle, en donde se recopiló información sobre la opinión del público en general ante la aparición de CHATGPT extraido a través de web scrapping.

Conjunto de datos
-----------------

Limpieza de Tweets
------------------

### Pasos

 **1- Convertir el texto a minúsculas**  
 Al convertir todo el texto a minúsculas, se asegura la uniformidad y consistencia en los datos. Esto evita que las mismas palabras escritas en mayúsculas y minúsculas se traten como diferentes, mejorando la precisión en el análisis.

 **2- Eliminar signos de puntuación, números y caractéres especiales** 
 La eliminación de estos elementos no alfabéticos reduce el ruido en los datos y se enfoca en las palabras clave. Esto facilita el procesamiento de las palabras y ayuda a evitar que estos elementos afecten negativamente la evaluación de sentimientos.

 **3- Separar el texto en palabras individuales** 
 Dividir el texto en palabras individuales es esencial para el análisis de sentimientos, ya que permite examinar cada palabra por separado y evaluar su significado y sentimiento en contexto.

 **4- Eliminar stopwords** 
 Las stopwords son palabras muy comunes que no aportan mucho significado al análisis de sentimientos, como "el", "es", "y", etc. Al eliminar estas palabras, se reducen las dimensiones del análisis y se enfoca en las palabras más relevantes que realmente expresan sentimientos.

 **5- Lematizar las palabras** 
 La lematización consiste en reducir las palabras a su forma base (lemas). Esto ayuda a agrupar variantes de una misma palabra, como "corriendo" y "corre", en una única forma. Esto mejora la coherencia y consistencia en el análisis, y ayuda a evitar que se cuenten las mismas palabras de diferentes formas.

 **6- Unir las palabras limpias en una cadena de texto** 
 Después de aplicar los pasos anteriores, se reúnen las palabras limpias en una cadena de texto nuevamente. Esto es necesario para mantener el contexto y poder realizar análisis y visualizaciones sobre los datos procesados.

 **7- Crear un dataset con todos los tweets limpios.** 
 Al crear un conjunto de datos con los textos limpios, se establece una base sólida para el análisis de sentimientos. Este conjunto depurado permite realizar evaluaciones de polaridad y subjetividad de manera más precisa y efectiva, lo que a su vez contribuye a obtener resultados más confiables.

Análisis de sentimientos
------------------------

 Se uso TextBlob para identificar la subjetividad y polaridad de los tweets. Si el valor obtenido en la polaridad es menor a 0 entonces el sentimiento es negativo, si es igual a 0 entonces es neutro, de lo contrario es positivo.

 ![Screenshot 1](https://iili.io/HDAsh9n.jpg)
 
### Nube de palabras

 #### Comentarios positivos

 La opinión pública sobre CHATGPT lo considera un avance en el campo de la inteligencia artificial, útil para comprender y facilitar actividades laborales o cotidianas. Además se le considera como una herramienta que permitirá el desarrollo y mejora de la interacción hombre-tecnología.

 ![Screenshot 2](https://iili.io/HDAswwG.jpg)
 
 #### Comentarios negativos

 En general, al público le preocupa que CHATGPT o tecnologías similares que puedan desarrollarse a partir de esta, puedan ser utilizadas para el reemplazo de profesionales en el mercado laboral, además de la generación de un dependencia tecnologíca.

 ![Screenshot 3](https://iili.io/HDALiJt.jpg)
 
 #### Comentarios neutros

 Antes de emitir una opinión sobre CHATGPT, por el momento una gran cantidad de personas opinan que es necesario seguir monitoreando su desarrollo y aplicaciones para comprender mejor sus implicaciones a largo plazo.

 ![Screenshot 4](https://iili.io/HDAQ4Qj.jpg)
 
 ### Distribución de la opinión publica

 Más de la mitad de los tweets analizados tienen opiniones positivas sobre la aparición de CHATGPT, sin embargo, hasta principios de este año (abril de 2023) 5 meses después de su liberación existe una gran cantidad de comentarios negativos que contienen preocupación sobre el futuro y temor por el reemplazo del ser humano en diferentes actividades.

 ![Screenshot 5](https://iili.io/HDAZd4p.jpg)
 
 Conclusiones
------------

 La llegada de ChatGPT representa un avance interesante en el campo de la inteligencia artificial y el procesamiento del lenguaje natural. Si se utiliza de manera adecuada y ética, esta tecnología podría tener aplicaciones útiles en áreas como la asistencia al cliente, la generación de contenido y la comunicación interactiva. Sin embargo, también plantea preguntas importantes sobre la privacidad, la veracidad de la información generada y el impacto en la comunicación humana genuina.