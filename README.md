## Learning to Code: Automatic Occupation and Business Coding via Machine Learning Approaches<br>
Hsin-Min Lu, Yu-Hao Lee, Chih-Chia Huang, Yu-Ting Tu.<br>
Information Management, National Taiwan University.<br>

- <b>The code is written in Python 3, so be sure to check your Python version.</b>

### Execute the following code to install python packages.
```
pip install -r requirements.txt
```
If you have both Python 2 and Python 3 in your computer, be sure to add "3" after ```python``` or ```pip``` command, i.e., 
```
pip3 install -r requirements.txt
```
### Try to execute the code ```test_program.py```
```
python test_program.py
```
or
```
python3 test_program.py
```

### Try to open the code ```test_program.py``` and modify it.
Instantiate a model, enter the predict target and converter.<br>
```target```: "business" / "occupation"<br>
```converter```: "bagofwords" / "tfidf"<br>

### Sample test data
There is a sample test data called ```sample_dataset.xlsx```, you can open it via Excel to see the data structure for our experiment.
