# Low Light Face Enhancement
For advanced CV project in University of Houston.  Goal is to reimplement the state-of-art paper "Deep Retinex Decomposition for Low-Light Enhancement", and test it on low light faces.     
Here is the paper website: https://daooshee.github.io/BMVC2018website/         
The author also has published its code and dataset. You can find it on above website.        


## Network architecture    
![](https://github.com/stephenkung/FaceEnhancement/blob/master/P1.jpg)


## Result for image decomposition       
{low Light, normal light, reflectance, illumination}        
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/epoch49img1.png)
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/epoch9img1.png)


## Result for low light image enhancement       
{low light, normal light, illumination, enhanced illumination, reconstructed image}
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/epoch39img1.png)
   
   
## Result for relighted low light faces       
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/face_relight.png)


## Result for facial landmark detection    
landmark detection method: https://github.com/1adrianb/face-alignment   
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/landmark.png)
      
