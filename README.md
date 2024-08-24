# Lab: Using Markdowns in Jupyter Notebooks

Estimated time needed: **15** minutes

Jupyter Notebooks are composed of code and markdown cells. Markdown cells are used to present text, images, etc. and are useful to document and explain the contents of your notebook. In this lab, you will become familiar with writing markdown.

## Objectives

After completing this lab, you will be able to:
*	Identify in which Kernel your Jupyter notebook is running
*	Create headings, and add text in bold and italics in Markdown
*	Insert links and images using Markdown
*	Create Tables in Markdown
*	Create ordered and unordered lists in Markdown
*	Demonstrate your proficiency in using Markdown in Jupyter notebooks


# Exercise 1 

### Kernels in Jupyter notebook

* A notebook kernel is a computational engine that executes the code in a Notebook file. 
  
* When the notebook is executed, the kernel performs the computation and produces the results. 

* On the top right corner you can see the name of the kernel. For instance, in JupyterLite, the default kernel is **Pyolite**. Similarly, if you are working on JupyterLab, the kernel will be **Python 3** or **Python 2**, depending on the version.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/kernelforjupyterlite.jpg">


* You can also run other kernels by choosing the preferred kernel on the **launch page** or by clicking the top right drop down menu to switch the kernel to the preferred kernel from the menu. 

* When the kernel is in execution, the state of the kernel is changed from **Idle** to the **Running** state.

  # Exercise 2
### Create headings, and add text in bold and italics in Markdown

Let us explore basic markdown elements such as: 
* Headings
* Bold Text
* ItalicText

### Headings:

* You can create headings by adding a <code>#</code> sign before a **word** or a **phrase**.

   * There are six levels of headings.
   * The number sign <code>#</code> indicate the level of heading for example **# Hello** corresponds to **level 1**,the highest level heading.
   * Display the following text using six different heading levels.
      * H1: This is a level 1 Heading
      * H2: This is a level 2 Heading
      * H3: This is a level 3 Heading
      * H4: This is a level 4 Heading
      * H5: This is a level 5 Heading
      * H6: This is a level 6 Heading
 > Recall: to convert a code cell to markdown, first click inside the cell, then on the dropdown labelled **"Code"** in the toolbar and select **"Markdown"**. To run a cell, click inside the cell then press <kbd>Shift+Enter keys</kbd> together.    
   <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/markdown1.png">
   
   * Convert the cell below to markdown cell and execute it.
   * To see or edit the contents of a rendered Markdown cell after running it double-click on the cell. 
# Execute it as a markdown cell
# H1: This is a level 1 Heading
## H2: This is a level 2 Heading
### H3: This is a level 3 Heading
#### H4: This is a level 4 Heading
##### H5: This is a level 5 Heading
###### H6: This is a level 6 Heading


# Exercise 3

### Create Tables in Markdown

To create tables, use: 
* **hyphens** <code>(----)</code> for column headers 
* **pipes** <code>|</code> to separate each column
* **Text on a new line** to separate each row

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/tabledisp.png">

_Convert the code cell below to a markdown cell. Then recreate the example table above and execute the code._

# Exercise 4
#### Create the following table:

 <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/table.png">



