<h1>Machine learning</h1>
<p>Os algoritmos deste repositório foram baseados no livro *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* de Aurelien Geron e, também nos o paper de 2017 de Meelis Kull, Telmo Silva Filho (UFPE) e Peter Flach entitulado *Beta calibration: a well-founded and easily implemented improvement on logistic calibration for binary classifiers*.</p>
<h2>Dummy_dataset_and_calibration.ipynb</h2>
<p>Este notebook aplica logistic regression e beta calibration em um Dummy dataset para tetar a eficiência de ambos na calibração das probabilidades associadas a cada label. Esses metódos foram feito para serem aplicados em classificadores binários e, embora possam ser aplicados métodos multi-class classifition como OvO (One-versus-one) e OvR (One-versus-rest), o processo escrita terá que ser manual e é extremente complicado pois, no caso do beta-calibration, ao menos no momento de publicação deste arquivo, não existem módulos no scikit-learn com o intuito de facilitar este processo.</p>
<h2>Iris_dataset_and_calibration.ipynb</h2>
<p>Este outro notebook aplica métodos de calibração aos classificadores SVM e Logistic regression com o intuito de verificar qual método de calibração possui a melhor performance, no sentido de aproximar a grau de confiança da previsão com a probabilidade associada a cada classe. Os métodos de calibração usados foram **platt's scalling**, **isotonic regression** e beta calibration, sendo os dois primeiros baseados no paper *Predicting Good Probabilities With Supervised Learning* de Alexandru Niculescu-Mizil e Rich Caruana.</p>
