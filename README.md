# Cloak_Of_Invisibility :sparkles:
This project will mask the Red color but you can change the values according to your desired color in the respective part of the code: <br/><br/>
*This is for Red:* :red_circle:      <br/>
```md
red = np.uint8([[[0, 0, 255]]])                       
hsv_red = cv2.cvtColor(red, cv2.COLOR_BGR2HSV)
l_red = np.array([0, 100, 100])
u_red = np.array([40, 255, 255])
 ```
        
 *If you wish to change it to Blue :large_blue_circle: then these are the values that worked for me:* <br/>
```md
blue = np.uint8([[[255, 0, 0]]])                       
hsv_blue = cv2.cvtColor(blue, cv2.COLOR_BGR2HSV)
lower_blue = np.array([110,50,50]) 
upper_blue = np.array([130,255,255])
```
        
 #### Steps to run <br/>
 1. Run `Background.py`
 2. Run `Invisible_Cloak.py`
 
