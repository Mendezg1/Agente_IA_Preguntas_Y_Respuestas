# Agente IA Preguntas y Respuestas

Este repositorio contiene cuatro agentes de inteligencia artificial diseñados para responder preguntas. A continuación se presenta una breve descripción de cada uno de ellos:

## roberta_general.ipynb
Este agente utiliza el modelo RoBERTa para responder preguntas de manera general. Es adecuado para una amplia variedad de contextos y proporciona respuestas precisas basadas en el análisis de texto.

## roberta_palabras_exactas.ipynb
Este agente también se basa en el modelo RoBERTa, pero está optimizado para buscar respuestas que coincidan exactamente con las palabras clave proporcionadas en la pregunta. Es útil cuando se requiere una precisión exacta en las respuestas.

## roberta_con_deepseek.ipynb
Este agente combina el modelo RoBERTa con la herramienta DeepSeek para mejorar la precisión de las respuestas. Sin embargo, se recomienda utilizar los otros agentes debido a las dudosas respuestas obtenidas por el modelo de DeepSeek. En caso continuar con este agente, se recomienda explorar opciones sobre cómo tener instancias de DeepSeek en local.

## LABse_general.ipynb
Este agente utiliza el modelo LABSE (Language-Agnostic BERT Sentence Embedding) para proporcionar respuestas generales. Es una opción robusta para responder preguntas en múltiples idiomas y contextos. Se recomienda especialmente su uso debido a que es un agente más personalizable ya que se codificó cada parte del procedimiento.

## Recomendación
Se recomienda el uso de los agentes `roberta_general.ipynb`, `roberta_palabras_exactas.ipynb` y `LABse_general.ipynb` para obtener respuestas precisas y eficientes. Se recomienda especialmente el agente `LABse_general.ipynb` por su adaptabilidad y personalización ante cualquier caso. No se recomienda el uso del agente `roberta_con_deepseek.ipynb`. 
