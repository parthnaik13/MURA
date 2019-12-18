# MURA

![](../master/Poster%20DL.png)

<b>[Our best model notebook](../master/MURA_VGG16.ipynb)</b><br><br>
<b>[Detailed report of our project](../master/MURA%20Report.pdf)</b>

Bone X-Rays are widely used for detecting and localizing abnormalities in various body parts such as shoulder, humerus, elbow, finger, forearm, wrist and hand. The automatic detection of abnormalities with accuracy better or equivalent to human radiologists’ performance could be a tremendous improvement in the diagnosis process. Automatic detection of abnormal
musculoskeletal conditions can help radiologists select and prioritize the affected people. This is particularly important in underdeveloped and developing countries which have a scarcity of experienced radiologists. Computer-aided detection can provide reliable and informed results for a large volume of cases in very less time.

We got the idea of this project from an ongoing Bone X-Ray Deep Learning competition on the topic, ‘Abnormality Detection in Musculoskeletal Radiographs’. For our work, we collected data from https://stanfordmlgroup.github.io/competitions/mura/. MURA is a large data set of musculoskeletal radiographs containing 40,561 images from 14,863 studies. Each study was labeled by radiologists manually as abnormal or normal. We train a VGG16 model, VGG19 model and an InceptionV3 model to detect abnormalities. Our best model (VGG16) achieved AUROC of 0.91 with sensitivity 0.88.

The model performance is compared with that of the radiologists on the Cohen’s Kappa statistic, which expresses the agreement of our model and of each radiologist with the gold standard.
