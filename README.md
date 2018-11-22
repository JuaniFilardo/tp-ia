# tp-ia
--------------------------------------------------------------------------------
### Trabajo Práctico de Inteligencia Artificial de la Universidad Tecnológica Nacional, Facultad Regional Córdoba

El presente trabajo está basado en una competición planteada por [WCCI].<br>

En pocas palabras, se provee un dataset con tweets etiquetados según su relevancia respecto a la ciberseguridad.
Mientras que los tweets relevantes se etiquetan con un 1, los irrelevantes tienen como etiqueta un -1.<br>
Los tweets relevantes son aquellos que mencionan una amenaza a un elemento de una infraestructura de IT (por ejemplo, una vulnerabilidad o un exploit) o una medida de seguridad para proteger ese elemento (por ejemplo, una actualización o un parche).

<br>
El objetivo es clasificar tweets 'nuevos' en alguna de estas dos clases.<br>
<br>
La notebook de jupyter adjunta muestra la clasificación realizada mediante el uso de un Naive Bayes Classifier y una Support Vector Machine.<br>
Obviamente, esta clasificación puede ser mejorada *un montón*.<br>


> Agradezco a los organizadores de la competencia, que compartieron conmigo el Evaluation Set.

--------------------------------------------------------------------------------

This project was intended as an approach to solve the competition proposed by [WCCI].<br>

In a nutshell, a dataset containing labeled tweets is provided. Each label shows if the tweet is relevant in a cybersecurity context.
While tweets labeled as 1 are relevant, the tweets labeled as -1 are irrelevant.<br>
A tweet is relevant if it mentions a threat to an element of an IT infrastructure (e.g., a vulnerability or an exploit) or a security measure to protect that element (e.g., an update or a software patch).
<br>
The goal here is to classify 'new' tweets as either relevant or irrelevant.<br>
<br>
The jupyter notebook found in this repo shows how our efforts to classify the tweets using a Naive Bayes Classifier and a Support Vector Machine.<br>
Needless to say, this classification can be improved *a lot*.<br>


> Special thanks to the competition organisers, who shared with me the Evaluation Set.

[//]:# (Links. This won't be seen after it's interpreted.)

[WCCI]: <http://disiem-project.eu/index.php/wcci-2018-competition/>
