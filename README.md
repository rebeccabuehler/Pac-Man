# Pac-Man
Making a moving Pac-man  

For this program I am creating a game like Pac-Man. He will move left to right with the opening anf closing of his mouth to give that game like effect. I will four images for the opening and closing of the mouth, and the direction changing of the Pac-Man. This will in the end simulate the basic movements of Pac-Man's game.

Some steps for getting started are establishing variables:
1. 2D array to hold the images
2. two variables to hold the indexes of the array (direction and focus)
3. the image width and page width to calculate when to reverse direction
4. Make two functions, one to update position to make the moving Pac-Man, two will update the direction and focus to reverse the Pac-Man

Through the two functions and a calling of setInterval(), I expect to see the Pac-Man move left to right with opening and closing its mouth, and having it face the direction it is going. I expect that they will continuously update the variables to complete the motion of moving.

Sources I used in completing this project was a former project of mine where I reverse the direction of the ball. The idea behind using a reverse boolean was very similar and helped with processing the idea behind direction and focus. I also used some starter code from my course. That is where the function for Run() came in. I also used our courses slack channel for additional support in some small syntax errors.

I think something I would like to do in the future is implement Pac-Man into a maze, having his direction and motion be more than just left to right. Maybe instead of using setInterval to have the function being constantly called, having it be a user that makes the moves. Make it more game like instead of it being a simulator.