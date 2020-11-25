	 _, _  _, _,_ __, _,   _, _, _
     |\/| / \ | | |_  |   / \ |\ |
     |  | \ / |_| |   |_, \ / | \|
     ~  ~  ~   ~  ~    ~   ~  ~  ~
                        
---------------------------
## Mouflon from Wikipedia 
---------------------------
The mouflon (Ovis gmelini) is a wild sheep native to the Caspian region from eastern Turkey, Armenia, Azerbaijan to Iran.[1] 
It is thought to be the ancestor of all modern domestic sheep breeds

https://en.wikipedia.org/wiki/Mouflon

![mouflon render](https://github.com/sirrobzeroone/Animal_Models/blob/main/Mouflon%20(Sheep%20Ancestor)/Mouflon_family_picture.png)

---------------------------
##     Coloring/Gender    
---------------------------
Male - Slightly larger with horns  
Female - Consistant brown shade no horns  
Lamb - Male & Female similar coloring to female.  

Adult genders - Have been modelled slightly differently, udders for female and testis for males, males larger horns and generally bigger.  
Lamb genders - A simple texture swap on the single model providing male/female differentiation.

---------------------------
##        Animation       
---------------------------
All 3 use the same animation rig although the one for the lamb was modified slightly so that it didn't sink so far into the ground on death.

The difference between walk/trot/run see this simple link which has a nice 2d representation of a quadrapeds walk cycle, although I did mess up slightly:
https://vimeo.com/215637283

|     | Start | End | FPS |
|-----|-------|-----|-----|
|Walk:|  216  | 231 |  10 |
|Trot:|   85  | 114 |  20 |
|Run: |  120  | 140 |  30 |
|Eat: |    0  |  30 |  15 |
|Chew:|   31  |  74 |  15 |
|Atk: |  145  | 160 |  20 |
|Die: |  191  | 211 |  10 |
|Lay: |   -   |  -  |   - |

---------------------------
##     Shearing   
---------------------------
The idea was to use the same base 3d model similar to 3d armour and then simply overlay the differnt textures as needed
When sheep is not shorn overlay wool onto shorn
When shorn simply update the model texture to remove wool
If you don't wish to allow shearing you can just use complete