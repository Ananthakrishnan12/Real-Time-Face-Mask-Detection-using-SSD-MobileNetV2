# Real Time Face Mask Detection using SSD-MobileNetV2:
Abstract: After the outbreak of COVID-19, mask detection, as the most convenient and effective means of prevention, plays a
crucial role in epidemic prevention and control. An excellent automatic real-time mask detection system can reduce a lot
of work pressure for relevant staff. However, by analyzing the existing mask detection approaches, we find that they are mostly
resource-intensive and do not achieve a good balance between speed and accuracy. And there is no perfect face mask dataset at
present. In this paper, we propose a new architecture for mask detection. Our system uses SSD as the mask locator and classifier,
and further replaces VGG-16 with MobileNetV2 to extract the features of the image and reduce a lot of parameters. Therefore,
our system can be deployed on embedded devices. Transfer learning methods are used to transfer pre-trained models from
other domains to our model. Data enhancement methods in our system such as MixUp effectively prevent overfitting. It also
effectively reduces the dependence on large-scale datasets. By doing experiments in practical scenarios, the results demonstrate
that our system performed well in real-time mask detection.

Requirnments : IDLE: Google Colab to run notebook on GPU.. Annotations tool : LabelImg

Procedure for Running the code: Is instructed in the python file FaceMASKdetection.ipynb

Result: Resulted Image are stored as result.png....