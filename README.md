![Pandas Banner](https://user-images.githubusercontent.com/66378414/161291276-5edd2bc0-b539-478f-be68-272fcc03c6fb.png)
# Pandas Challenge
<br>

This project performs analysis on district-wide standardized test results, using an input csv file of student's math and reading scores, as well as various information on the schools they attend. This code aggregates the data to showcase obvious trends in school performance.
<br>  

## Methods Used  
PANDAS
<br>

## Data Source

Data found in:
<ul>
<li>pandas-challenge/PyCitySchools/Resources/students_complete.csv  </li>
<li>pandas-challenge/PyCitySchools/Resources/schools_complete.csv </li>
  </ul>
<br>

## Installation
Code was tested using Python 3.8.  The environment also needs pandas and matplotlib. The environment was setup as follows:

```bash
conda create -n envpy38 python=3.8 anaconda
source activate envpy38
jupyter notebook
```
If environment does not include pandas then install the following from terminal:
```bash
conda install pandas
```  
<br>

## Analysis and Conclusions
An analysis was conducted to determine student outcomes in terms of math and reading scores, based on several factors, including school size, type, and per student budget. The following conclusions were drawn from the data:
<ul>
  <li>Per student budget was, surprisingly negatively correlated with overall student success </li>
  <li>The data shows that students at larger schools struggled more academically than those at smaller schools </li>
  <li>An analysis of outcomes by school type showed that students fared better academically at Charter rather than District schools</li>
</ul>
![Spend](https://user-images.githubusercontent.com/66378414/161293168-18ab5d14-6126-4cd3-ab16-f97e062e6529.PNG)
![size](https://user-images.githubusercontent.com/66378414/161293164-05ce6785-533f-465c-a597-bb538e482823.PNG)
![type](https://user-images.githubusercontent.com/66378414/161293166-643d75b3-36da-4867-b398-7e02b69ba68b.PNG)




<br>



DO THIS (If you want to make it even more visually pleasing then you can use a website like [Canva](https://www.canva.com/web-banners/templates/) to make banners for the top of your readme.  There are some free options.  )
