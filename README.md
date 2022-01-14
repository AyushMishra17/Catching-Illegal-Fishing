# Catching-Illegal-Fishing
Using Global fishing watch's data to build a machine learning model that can identify illegal fishing and poaching activities through satellite and geo-location data.

Global fishing watch is a partnership between Google and Oceana to map all trackable fishing activity in world, in almost real time. This is a personal project using the data provided by global fishing watch.

The data provided has vessel ids, types and coordinates of encountered vessels.

Given same vessel type and are, a fishing vessel has a different trajectory than a non fishing vessel. I used the data provided to train my model on predicting whether a vessel is fishing or not. 

#Local Environment Setup
Python 3.7++
Tensorflow version >1.14.0,<2.0 from (https://www.tensorflow.org/get_started/os_setup)
pip install google-api-python-client pyyaml pytz newlinejson python-dateutil yattag

#Model Result
![image](https://user-images.githubusercontent.com/97682962/149486800-6dead3c3-e799-44b2-84d4-c2fdf8e4a6ca.png)

![image](https://user-images.githubusercontent.com/97682962/149486926-9934f5ef-d4d0-44f7-a550-f07106fdb28b.png)


![image](https://user-images.githubusercontent.com/97682962/149486959-cb843abb-710d-42bd-a7e5-d5afd35aa78a.png)

![image](https://user-images.githubusercontent.com/97682962/149486993-3e0aec1e-2cd9-4c39-b5ba-9dcbaa2e75b2.png)


![image](https://user-images.githubusercontent.com/97682962/149487045-e1c7841d-0595-4ee7-8718-85766405a543.png)

![image](https://user-images.githubusercontent.com/97682962/149487067-1d02a44f-50e2-42d0-8aac-31b23bab584d.png)

As you can see the predicted tracks are extremely close to the real paths.
