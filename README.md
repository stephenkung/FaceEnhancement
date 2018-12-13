# Low Light Face Enhancement
For advanced CV project in University of Houston. Goals:
1) reimplement the state-of-art paper "Deep Retinex Decomposition for Low-Light Enhancement".    
2) test it on low light faces.    
3) run a pretrained face&landmark detection model to test improvement on low light faces.                 
>Here is the paper website: https://daooshee.github.io/BMVC2018website/         
>The author also has published their code and dataset. You can find it on above website.        

-----
## Documents
Final presentation    
Final report      
lowlight.ipynb: implementation of Retinex-Net    
Traditional_enhance.ipynb: implemenation of Gamma enahncement 
landmark.ipynb: face and landmark deteciton     

-----

## Dependency
This work is done by tensorflow 1.10 + Python3.6.6    
Training can be finished in 1 hour, with a GTX1060(6G RAM).    

-----

## Network architecture    
![](https://github.com/stephenkung/FaceEnhancement/blob/master/P1.jpg)

-----

## Result for image decomposition       
{low Light, normal light, reflectance, illumination}        
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/epoch49img1.png)
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/epoch9img1.png)

-----
## Result for low light image enhancement       
{low light, normal light, illumination, enhanced illumination, reconstructed image}
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/epoch39img1.png)
   
-----   
## Example for relighted low light faces       
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/face_relight.png)

-----
## Example for facial landmark detection    
landmark detection method: https://github.com/1adrianb/face-alignment   
![](https://github.com/stephenkung/FaceEnhancement/blob/master/pics/landmark.png)

      
