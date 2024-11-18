# pc3_nlp2024-2
Retrofitting de concept embeddings con RNNs para mejorar la comprensión semántica


Reconocimiento de Entidades Nombradas con Embeddings Retrofitted
Este proyecto implementa un modelo de Reconocimiento de Entidades Nombradas (NER) utilizando PyTorch. Se basa en embeddings preentrenados GloVe, que son mejorados mediante retrofitting con un léxico semántico, y utiliza un modelo basado en LSTM para identificar entidades nombradas en texto.

Descripción General
El Reconocimiento de Entidades Nombradas (NER) es una tarea clave en el Procesamiento de Lenguaje Natural (NLP) que consiste en identificar y clasificar información clave (entidades) en texto. Este proyecto demuestra cómo construir un modelo de NER utilizando:

Embeddings preentrenados GloVe para la representación de palabras.
Técnicas de retrofitting para mejorar los embeddings mediante un léxico semántico.
PyTorch para construir y entrenar el modelo basado en LSTM.
Requisitos
Python 3.6 o superior
PyTorch
NumPy
Pandas
scikit-learn
Requests
tqdm (opcional, para barras de progreso)

Dataset
El dataset utilizado en este proyecto es dataNER.csv, que debe contener:

Sentence: Una lista de oraciones, donde cada oración es una cadena de palabras.
Tags: Las etiquetas NER correspondientes para cada palabra en las oraciones


Referencias
Embeddings GloVe:

GloVe: Global Vectors for Word Representation
Técnica de Retrofitting:

Faruqui, Manaal, et al. "Retrofitting word vectors to semantic lexicons." Proceedings of NAACL-HLT. 2015.
Documentación de PyTorch:

PyTorch Official Documentation