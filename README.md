# Challenge - Machine Learning and Computer Vision basis

En el siguiente challenge se abarcan los conceptos básicos de Machine Learning y Computer Vision, tanto la teoría y definiciones como el preprocesamiento y entrenamiento de modelos.
El mismo consta de 4 secciones:
- [Teoría de Machine Learning](https://github.com/githubmec/challenges/issues/4)
- [Manipulación y análisis de datasets](https://github.com/githubmec/challenges/issues/5)
- [Preprocesamiento de datasets para Computer Vision](https://github.com/githubmec/challenges/issues/6)
- [Entrenamiento de modelos de Computer Vision](https://github.com/githubmec/challenges/issues/7)

### Descarga de datasets:

Para usar el [AWS Command Line Interface](https://aws.amazon.com/cli/) en el enviroment se instala con ```pip3 install awscli```. Luego, se ejecuta la siguiente linea para descargar todos los datasets del challenge

```
aws s3 cp s3://datasets-mecantronic/ datasets/ --recursive
````
