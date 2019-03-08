# TensorFlow Auto
Using TensorFlow Extended components to mix-and-match pipelines through genetic algorithms.
# Inspiration
TPOT is an automated machine learning tool which combines scikit-learn components in order to compose complete pipelines which receive raw data as input and generate predictions as output. The module makes use of the scikit-learn standardized API in order to combine selectors, preprocessors, regressors, and others, into a pipeline. The sequences of components are treated as indivuduals in a genetic algorithm. Through evolution operators such as mutation, cross-over, selection, and others, the pipelines improve their performance which each generation.

TensorFlow Extended is a Google-production-scale machine learning platform based on TensorFlow. It provides a configuration framework and shared libraries to integrate common components needed to define, launch, and monitor your machine learning system.

TensorFlow Auto is the TPOT of TensorFlow. Instead of using scikit-learn components, it uses the TFX ones.
