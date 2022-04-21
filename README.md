# SmartObject AI template for UnrealEngine 5
SmartObject AI template for UnrealEngine 5


This is a project intended to make a AI that can select goals based on its current situation. Its heavly inspired by F.E.A.R.s goal oriented action planning AI
system. It uses smart object actors to trigger events like playing a animation. This can be tweaked into more interesting stuff for different use cases.

![image](https://user-images.githubusercontent.com/2607194/164281029-70a04e75-c65c-4369-9adc-a0778b315820.png)




# Known bugs:

* Animations out of bounds message is normal
* AI using smart object actor triggers animations multiple times
* Floor material needs re-adjusting, use these values: U tiling: -33,184689 V tiling: −38,202377 (In the text coord node)

![image](https://user-images.githubusercontent.com/2607194/164358115-12f45ca7-206e-45a4-b48e-d944eb7a1625.png)






# This is now ported to UE5. The new smart object AI system is super experimental, so use at your own risk! 

```diff
Keys:
* 1: Spawns the gun
* Left mouse button: Shoot
* Right mouse button: Aim
* Q/E: Lean left or right
* Left shift: Sprint
* Left ctrl: Crouch
* R: Reload
```


Unreal version: UE5
Size: 2GB 













