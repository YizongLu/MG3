# MG3
## Devlog
1. The default value of floats is 0.0. The default value of ints is 0. The default value of bools is false. The default value of strings is an empty string.
2. The Update method get called automatically by the Unity every frame. My code does not call it. 
3. In TimerText class, when the game start, the Start method is called by Unity to set up the timer to indecate rest of time. And, the Update method is called by Unity every frame to update the text of timer in order to display the left time. If the timer is end, it will call GameOver method in the Update method.
In KickWeapon class, when kick activated, the timer will set up as how long can the kick last. And, the Update method is called by Unity every frame to check whether the kick time is end, then the kick will deactivated. 

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)