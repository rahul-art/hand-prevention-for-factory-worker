# hand-prevention-for-factory-worker



To run the project
1. clone the repo 
``` git clone https://github.com/rahul-art/hand-prevention-for-factory-worker.git ```
2. create seprate environment
``` conda create -n hand_safety python=3.6 ```
3. install requirements 
``` pip install -r requirements.txt ```
4. run hand_detection.py file ``` python hand_detection.py ```then you get the output similar as follows:
![alt text](https://github.com/rahul-art/hand-prevention-for-factory-worker/blob/main/example.png?raw=true)

here the red line below blue line is safety line if hand crosses that line it will raise an alarm and stop the machine 
the paerpendicular red thin line is measuring the distance from the safety line to the hands.
feel free to use the code, modify and play with it as per need.

