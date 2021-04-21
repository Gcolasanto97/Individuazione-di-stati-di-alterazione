# Individuazione di stati di alterazione

Addestramento di una CNN con l'obbiettivo di individuare i soggetti in stato di ebrezza sfruttando le immagini a infrarossi come dato di input. Vi è un modulo che adatta le immagini e poi vi sono due moduli con diverse verianti architetturali, uno implementa ResNet, l'altro DenseNet.

# Requirements
- Google Colab o una GPU molto performante.
- Python 3.x
- Keras
- TensorFlow

# Ambiente di lavoro
Se si utilizza Colab come ambiente di lavoro, si consiglia di montare Google Drive, uploadare le immagini presenti negli archivi. Per addestrare i modelli è necessario solo l'archivio chiamato FRONT.

# Schema del modello ResCNN
![image](https://user-images.githubusercontent.com/71646435/115535786-5da93b80-a299-11eb-90a8-03dd8ec8650c.png)

# Schema del modello DenseCNN
