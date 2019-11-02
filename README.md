# escalada (documentation in course)

<p align="center">

<img src = "https://user-images.githubusercontent.com/54853371/68062611-ba164500-fd0b-11e9-858f-2552375650ef.jpg" >

</p>

<br><br>

<h1>What i need for this project</h1>

1) Python 3.x - https://www.python.org/downloads/

2) Download CV2 and Numpy with the command "pip install open-cv" and "pip install numpy"

3) Use git clone command or copy manually each document with the <strong>same composition</strong>


<br><br>

<h1>How the project functions ?</h1>

1) Lunch wall_parameters from <strong>wall_parameters/wall_parameters.py</strong> with f5 or Run/Run Module from the tool barre.

2) Lunch main and click on a key when picture appears.


<br><br>

<h1>Architecture</h1>

We have 4 folders:
  
  - picture for the wall picture with holds ! 
  
      - The picture for a detection need to be on <strong>pictures/wall_pieces/</strong>.
  
  - wall_parameters for delete the background.

     - put our absolute path for have acces to the app like: C:User/pictures/wall.jpg.

  - info_data who's contains parameters for the background delete.


  - Main
    
    - It call path and pictures_functions.
    
      - In the








<br><br>

<h1>Wall_parameters</h1>


<strong>wall_parameters</strong> permet to modify parameters of the wall. With the file we can raise the background and recup the pieces.



<h2>How to use it ?</h2>


<h3>Demonstation</h3>

Carefull we need to do it 2 times. One time on the top of picture (blue/black colors) and one time one bottom of picture (green). So we can have top and bot objects.

picture


In some, we need top black, bottom white. You just have to press "q" and parameters are save into a file.


Note: 

#top [0, 46, 0, 79, 255, 255] <br>
#bot [0, 95, 0, 255, 255, 255] are the good parameters the current wall. With this light intensity (day intensity different night intensity)







<br><br><br><br><br><br>

But this is for the three first picture who's represent the same caracteristics of light. It show the importance of the wall parameters.

So for each hours or a changement of light (like a cloud pass) <strong>the wall_parameters</strong> must be modify.

For the moment it must be manually, maybe it could be automatic.
