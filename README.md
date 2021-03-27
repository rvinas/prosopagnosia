# Prosopagnosia
Prosopagnosia, also known as face blindness, is a cognitive disorder of face perception in which the ability to recognize familiar faces is impaired. This sometimes includes one's own face. It is estimated that around two and a half percent of the world population are affected by prosopagnosia.

Here, we developed a solution to prosopagnosia. Essentially, the main idea is to develop a machine learning model to match a query face with a set of reference, known faces. This model can then be deployed on glasses such as [Spectacles](https://www.spectacles.com/uk/), which are equipped with small, hidden cameras. Using this method, people with prosopagnosia can discreetly indentify the person in front of them.

<img src="https://cdn.vox-cdn.com/thumbor/z0QEPe4zse8wnDnnGIcj7MXNR8M=/0x0:2000x1125/920x613/filters:focal(840x403:1160x723):format(webp)/cdn.vox-cdn.com/uploads/chorus_image/image/65007689/1_PRIMARY_Spectacles3_Campaign.0.jpg" width="500" class="center" />

We implemented a prototype of the approach based on the [face_recognition](https://github.com/ageitgey/face_recognition) Python library and the [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) database from the University of Massachusetts. Please see `demo.ipynb` for a quick demonstration.

# Credits
Thank you Jo Baker, Doris Webb, Anton Chepaldin, Hector Minto, and Owain Williams for the nice ideas and insightful comments. Thank you to the organisers of the AstraZeneca Neurodiversity Hackathon.
