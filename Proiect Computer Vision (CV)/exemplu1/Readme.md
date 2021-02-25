# Plan pentru un proiect Clasificarea Imaginilor
In aceasta sectiune vom descrie de ce ai nevoie pentru a incepe un proiect unde sa clasifici imaginile in cateva categorii.

Autori: [Ion Moșnoi](https://www.linkedin.com/in/ionmosnoi/) 

Comunitate AI in actiune [group FB](https://www.facebook.com/groups/aiinactiune)

## Bazele

### ML notiuni
Pentru inceput ar trebui sa stii notiunile de baza, ce inseamna diferite cuvinte cheie
#### Invatare supervizata [medium en](https://towardsdatascience.com/a-brief-introduction-to-supervised-learning-54a3e3932590) [video en](https://www.youtube.com/watch?v=kE5QZ8G_78c&ab_channel=Simplilearn) [short video en](https://www.youtube.com/watch?v=TJveOYsK6MY&ab_channel=Quantopian)
* Clasificarea [free course ro](https://course.elementsofai.com/) 


### programare 
* [run in browser + examples](https://www.w3schools.com/python/default.asp)
* [video en](https://www.youtube.com/watch?v=QXeEoD0pB3E&list=PLsyeobzWxl7poL9JTVyndKe62ieoN-MZ3&ab_channel=Telusko)
#### variabile
* [run in browser](https://www.w3schools.com/python/python_variables.asp)
#### conditii if
#### loops
#### functii

### librarii
#### sklearn
* [video en](https://www.youtube.com/watch?v=rvVkVsG49uU&ab_channel=GoogleCloudTech)
#### numpy
* [video en](https://www.youtube.com/watch?v=xECXZ3tyONo&ab_channel=PythonProgrammer)
#### opencv
* [video en](https://www.youtube.com/watch?v=kdLM6AOd2vc&list=PLS1QulWo1RIa7D1O6skqDQ-JZ1GGHKK-K&ab_channel=ProgrammingKnowledge)


### algoritmi/modele de invatare automata
Alege Unul
#### knn
* [video](https://www.youtube.com/watch?v=UqYde-LULfs&ab_channel=ThalesSehnK%C3%B6rting)
* [medium en](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761)
#### decision tree
* [video](https://www.youtube.com/watch?v=a5yWr1hr6QY&ab_channel=MBAbullshitDotCom)
#### neural networks
* [video]()
#### Convolutional neural networks (CNN) - il vom folosi
* [video]()

### tehnici folositoare
#### augmentarea imaginilor (optional)
* []()
#### dropout
* []()
#### trasnfer learning
* [video]()
#### scraping data (optional)
* [video]()



### IDE
Alege unul
#### jupyter notebook
* [video](https://www.youtube.com/watch?v=HW29067qVWk&ab_channel=CoreySchafer)
#### google colab 
* [video](https://www.youtube.com/watch?v=inN8seMm7UI&t=3s&ab_channel=TensorFlow)
#### pycharm
* [video](https://www.youtube.com/watch?v=56bPIGf4us0&ab_channel=TechWithTim)


*HINT* daca nu intelegi un subiect, cauta pe net folosind cuvintele cheie + terminatia 'explaned' sau 'tutorial'

## Pasii unui proiect
### data processing
Trebuie sa ai cateva mape cu imagini, in fiecare folder sa fie doar imagini de acelasi fel, de exemplu imagini cu pisici.
### modeling
Vom folosi transfer learning pentru a reantrena reteaua neuronala VGG16 sa clasifice imagini de pisici si caini.
### testing
Calculeaza acuratetea folosind sklearn
