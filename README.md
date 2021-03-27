# Prosopagnosia
Prosopagnosia, also known as face blindness, is a cognitive disorder of face perception in which the ability to recognize familiar faces is impaired. It is estimated that  around two and a half percent of the world population.

Here, we developed a solution to prosopagnosia. Essentially, the main idea is to develop a machine learning model to match a query face with a set of reference, known faces. This model can then be deployed on glasses such as [Spectacles](https://www.spectacles.com/uk/), which are equipped with small, hidden cameras. Using this method, people with prosopagnosia can discreetly indentify the person in front of them.

We implemented a prototype of the approach based on the [face_recognition](https://github.com/ageitgey/face_recognition) Python library and the [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) database from the University of Massachusetts. Please see `demo.ipynb` for a quick demonstration.

# Credits
Thank you Jo Baker, Doris Webb, Anton Chepaldin, Hector Minto, and Owain Williams for the nice ideas and insightful comments. Thank you to the organisers of the AstraZeneca Neurodiversity Hackathon.
