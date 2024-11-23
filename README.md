# Reinforced-Learning-Snake-Game
https://www.google.com/search?q=snake+game&sourceid=chrome&ie=UTF-8
This is our attempt at making snake.

What we decided on the meeting:

Technology:
- Pytorch
- OpenCV

We will make matrix that resembles the matrix provided in the link to the snake game above.
The snake speed, and movement should be exactly the same!.

- Snake is allowed to go into the wall and into his body, but this will be punished!
- Going towards the fruit is always lightly rewarded!
- Staying alive (moving everywhere, except into the wall is rewarded but only ~3 times)
- Going nearby the fruit (even if its not exactly towards the fruit is also rewarded)


API:
- jsname informing about highscore does not change
- We Transform moves of snake into keyboard moves (WASD)


Snake is informed:
- How far to snake's body - Question (Do we create value for the distanse to EACH part of his body or ANY part of his body?)
- How far to the fruit
- How far to the wall
- ![image](https://github.com/user-attachments/assets/063a94a3-17a9-4511-adee-2ddd144196c1)
