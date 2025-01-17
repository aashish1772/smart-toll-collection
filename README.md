# smart-toll-collection
This is a computer vision project aiming in helping reduce traffic at the toll booths.
<br />**Team name: Noice**
<br />**Team members - Kush Daga(COE branch), Madhav Pareek(COE branch), Hemant Kumar Taneja(ENC branch)**
<br />**Year - 1st year**
<br />**Institute - Thapar Institute of Engineering and Technology**

# PROBLEM

The problem that we aim to address is the increasing amount of traffic in the tolls, even after the introduction of
fasTag in India, still there is alot of traffic jams as there are only two lanes in most places and many non fasTag users
also enter the lanes. We are proposing a solution to solve this issue.

# Technology Used

We are using Flask combined with openCV and libraries like numpy to identify the license plates and recognize the characters of the plate.
Right now we are using stock photos for testing out our application which you can input in line 38 in Main.py in app/views/ml/.

# Installation

1. Clone this repo and make a virtualenv if you wish to, im using python3 in this project.
2. Then install the requirements via "pip install -r requirements.txt" command.
3. Run the run.py file and open the localhost:4000 page on your browser. (python run.py OR python3 run.py)
4. After the installation you will notice three images showing basic steps of image processing, click the pic and enter any key to continue.
5. Open the browser and see the result, you will see the identified plate number shown.

# To view the sample form that we are proposing to use for registrations, please visit localhost:4000/form

Visit the website for more information after running it locally.

Screenshots :
![1](https://i.imgur.com/q3vUPzX.png)
![2](https://i.imgur.com/rdhWDM6.png)
![3](https://i.imgur.com/apqWjIN.png)
![4](https://i.imgur.com/YOaOs0z.png)
![5](https://i.imgur.com/LeSyrA9.jpg)
![6](https://i.imgur.com/Hozv4TU.png)
![7](https://i.imgur.com/MMTl7LQ.jpg)
