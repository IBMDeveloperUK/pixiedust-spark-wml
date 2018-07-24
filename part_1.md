### Static data analysis using Python, Apache Spark, and PixieDust

Learn how to analyze data in a Python notebook using Apache Spark and PixieDust

![part_1](images/part_1.png)

#### Prerequisites
 * Apache Spark
 * PixieDust (A Python helper library for developers and data scientists)
 
#### Getting started
 * Open [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio)
 * Create a new project by clicking on the tile as below. Choose `Complete` and `OK`. 
 
 ![](images/new_project.png)
 
 * Give your Project a name
 * Select an Object Storage from the drop-down menu or create a new one for free. This is used to store the notebooks and data. Do not forget to click refresh when returning to the Project page.
 * click 'Create'.  
 
 * Associate the project with an Apache Spark service instance. Go to Settings and scroll down to Associated Services. Click + and select Spark from the drop-down menu. Select an existing service or create a new one for free.
 
![spark](images/add_spark.png)

 * Add a new notebook from URL https://raw.githubusercontent.com/IBMCodeLondon/localcart-workshop/master/notebooks/part-1-analyze-customer-data.ipynb
 * Make sure you select Spark as your runtime.
 
 ![notebook](images/new_notebook.png)
 
 * Follow the notebook instructions.
