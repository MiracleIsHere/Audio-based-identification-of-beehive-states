# Audio-based-identification-of-beehive-states
A system that can automatically identify different states of a hive based on audio recordings made from inside beehives.
*	Developed a custom features extraction method with librosa. Mel-frequency cepstral coefficients, melspectrogram, chroma_stft, chroma_cqt, chroma_cens features were extracted from the audio signal.
*	Fine-tuned convolutional neural networks with Keras to classify beehive states, achieving a classification accuracy rate of 99%. The BeeNoBee model works as a preselector of relevant samples. The BeeSound model makes the decision regarding the state of the hive.
*	[Used React to implement frontend and Flask for machine learning model deployment.](https://github.com/MiracleIsHere/Beehive-states-identification-system)
## Results
BeeNoBee (0 – Bee, 1 – Noise)|BeeSound (0 – NoQueenBee, 1 – QueenBee, 2 – Swarming)
:-------------------------:|:-------------------------:
![](https://imgur.com/03i9re0.png) | ![](https://imgur.com/9yCMkse.png)
## Demo
Homepage|Quick Guide
:-------------------------:|:-------------------------:
![](https://imgur.com/DmLz7xJ.png) | ![](https://imgur.com/KLhQFoX.png)
Make A Record Of A Hive Or Upload An Existing Record|Labels Description
![](https://imgur.com/U5Mmjjw.png) | ![](https://imgur.com/pjZzshO.png)

Distinguish Your Hive – Pick A Color
:--------------------------------------------------:
![](https://imgur.com/zEWLGw6.png)
## Data
*	[J. Salamon, C. Jacoby and J. P. Bello, "A Dataset and Taxonomy for Urban Sound Research", 22nd ACM International Conference on Multimedia, Orlando USA, Nov. 2014.](https://urbansounddataset.weebly.com/) – put it under 'Data Bee\\Raw Recordings'.
*	[Nolasco, Inês, & Benetos, Emmanouil. (2018). To bee or not to bee: An annotated dataset for beehive sound recognition [Data set]. Zenodo. https://doi.org/10.5281/zenodo.1321278](https://zenodo.org/record/1321278#.W2XswdJKjIU) – put it under 'Data Urban\\'.

