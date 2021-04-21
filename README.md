# Individuazione di stati di alterazione

Addestramento di una CNN con l'obbiettivo di individuare i soggetti in stato di ebrezza sfruttando le immagini a infrarossi come dato di input. Vi è un modulo che adatta le immagini e poi vi sono due moduli con diverse verianti architetturali, uno implementa ResNet, l'altro DenseNet.

# Requirements
- Google Colab o una GPU molto performante.
- Python 3.x
- Keras
- TensorFlow

# Ambiente di lavoro
Se si utilizza Colab come ambiente di lavoro, si consiglia di montare Google Drive, uploadare le immagini presenti negli archivi. Il primo modulo deve usare come input l'archivio FACE e produce le immagini presente nell'archivio FRONT, invece per addestrare i modelli è necessario solo l'archivio chiamato FRONT.

# Preparazioni delle immagini
0. Aprire il file Drunk_FrontDetection.ipynb con Colab
1. Uploadare le immagini del'archivio FACE su Drive
2. Montare Drive su Colab
3. Eseguire il codice

# Schema del modello ResCNN
![image](https://user-images.githubusercontent.com/71646435/115535786-5da93b80-a299-11eb-90a8-03dd8ec8650c.png)

# Addestramento del modello
0. Aprire il file Drunk_ResCNN.ipynb con Colab
1. Uploadare le immagini del'archivio FRONT su Drive
2. Montare Drive su Colab
3. Eseguire il codice

# Schema del modello DenseCNN
![image](https://user-images.githubusercontent.com/71646435/115536065-a6f98b00-a299-11eb-9f2f-b1a5aa2cb6c3.png)

# Addestramento del modello
0. Aprire il file Drunk_DenseCNN.ipynb con Colab
1. Uploadare le immagini del'archivio FRONT su Drive
2. Montare Drive su Colab
3. Eseguire il codice
