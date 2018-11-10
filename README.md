# KrishiSeva
To identify disease in the leaf of Apple and Tomato

It uses two models to predict the disease present in the leaf of the Apple and Tomato plant:
<ol>
<li>Random Forest Classifier</li>
<li>Logistic Regression</li>
</ol>
<br>
Both of the model is deployed on Azure ML Studio as a web service so we don't have to train it again and again.
<br>
<h3>Required Python Packages</h3>
<br> 
<ol>
<li>Numpy</li>
<li>Mahotas</li>
<li>OpenCv (cv2)</li>
</ol>
To run the program open command prompt and type:
<pre>/path/to/your/python/interpretor TestPlant.py path/to/image nameOfThePlant
<br>
For eg: python.exe TestPlant.py apple.jpg Apple
</pre>
<br>
Images for testing purpose are provided in this repo.  