# MultiLayerPerceptron

Basic multi layer perceptron

Learns XOR:
```python
X: [0 0] y: 0 
y_pred: 0.02801529097677105

X: [0 1] y: 1 
y_pred: 0.96521603348442

X: [1 0] y: 1 
y_pred: 0.9648998041481337

X: [1 1] y: 0 
y_pred: 0.040263703553695275
```

hypothesis(node03) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/|\    
bias02 node12 node22  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/|\ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//|  
bias01 node11 node21  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/|\ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//|  
bias00   x0     x1    

