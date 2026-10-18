# MG3
## Devlog
1. When adding float as a member variable to the Timer class, the default value is 0. The same is for int where the default value is also 0. When adding bool as a member variable to the Timer class, the default value is a check box where I can click on the box to either have a checkmark or not, likely meaning if it's true (checkmark) or false (no checkmark). When adding string as a member variable to the Timer class, the default value is a empty text box where I can type anything I want in there.

2. In this assignment, the Update method is not being called in by code this assignment. Rather, Unity is the one running this method every frame and by using the BeginTimer method, the time is update every frame because Unity is calling the Update() method every single frame.

3. The Timertext class uses the timer by displaying the amount of time left on bottom right every frame. So, the timer code that I wrote decreases the timer every frame. By using the Update() method, the timer is constantly being updated every frame by as Unity is the one calling it. However, the timer is not displayed within the game itself. This is where the Timertext class comes into play. The Timertext class allows the player to see how much time there is left as well as displaying the game over screen once time runs out.


## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
