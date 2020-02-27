# Algorithm-Exploration
# Solving various puzzles and timing them for a Computer Science Project.

**This page's sole purpose is to record my progress with these puzzles.**

Will be using Markdown for this repository. Link for help in markdown : https://guides.github.com/features/mastering-markdown/. 

## Pyraminx Duo
![Image of Pyraminx Duo](https://www.maskecubos.com/4979-large_default/lefun-pyraminx-duo.jpg)  

### Daily Log 

Februrary 13th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   12.01
12 | 12.37 
25 | 12.37

Februrary 14th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   13.56
12 | 12.58 

Februrary 15th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   11.47
12 | 12.02 

Februrary 16th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   10.02
12 | 12.05


Februrary 19th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |  15.06 
12 | 11.06 


### Techniques used

Due to the puzzle's lack of complexity compared to the other puzzles, no specific algorithm was used. Hence due to this reason, there are no names of the algorithms. 

#### Solved edges with a different color centre 

Perspective required when the color of the centre is adjacent to the same colored side 

_Solution_: L R' R L

#### Different edges and different centre color

Find the common 'side' of a chosen color by tracking the edges and the location of the centre with the edge.  

_Solution_: U L' R' U

Sources: 
[Z3Cubing on Pyramix Duo and Optimal moves!](http://youtube.com/watch?reload=9&v=P-Zt7GEyYuE), [Z3Cubing on Pyramix Duo Intermediate Method](https://www.youtube.com/watch?v=xRBGC4Bxv1w)

## Pyraminx

### Daily Log 

Februrary 13th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   96.09
12 | 81.01
25 | 82.00

Februrary 15th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   120.01
12 | 96.03
25 | 95.00

Februrary 16th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   97.02
12 | 86.01
25 | 84.02

Februrary 17th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   96.56
12 | 80.03

Februrary 18th

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   82.03
12 | 80.66


### Techniques Used : Layer By Layer 

Involves finding the right sides for each color by solving for the centre pieces. No specific algorithm as this requires observation and planning ahead. 

Then in order to fill the edges of the sides, align the piece with the side's color and the color of the 'base'. Align three pieces with the same color, making a 'block' and follow this algorithm. 

![Image of Pyraminx](https://ruwix.com/pics/puzzles/pyraminx/pyraminx-solve-top-layer-edges.jpg)  

_Left_ : R U' R 
_Right_ : L' U L 

![Image of Pyraminx](https://ruwix.com/pics/puzzles/pyraminx/solving-last-layer-pyraminx-algorithm.jpg)

Referring to the image above, 

_Clockwise cycle_: U' R U R'

_Counter-clockwise cycle_ : U L' U' L

Lastly, when the pieces are in the right place but the color is 'flipped' and the rest of the pieces are in the correct position, follow this algorithm. 

_Solution_ : L R' L' R U' R U R'

![Image of Pyraminx](https://i.ytimg.com/vi/BzsKT6Uayfs/maxresdefault.jpg)

Lastly, the **'Headlight' Algorithm** where two edge pieces are the same color but in a different side, with the edge's color side being in the left or the right of the Pyraminx. Solution as follows.

_Right_: R U R' U R U R'

_left_ : R U' R' U R' U' R


Sources : [Z3Cubing on Pyramix Beginner](https://www.youtube.com/watch?v=xIQtn2qazvg), [Noah Richardson on Pyramix](https://www.youtube.com/watch?v=2H0FUvaaUsI) and [Ruwix on Pyraminx Puzzle](https://ruwix.com/twisty-puzzles/pyraminx-triangle-rubiks-cube/)

## 2x2x2 Rubik's Cube

February 20

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   120.36
12 | 130.65
25 | 110.25

February 21

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |  110.57
12 | 99.36
25 | 90.23

February 22

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   115.77
12 | 101.69
25 | 99.33

February 23

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   90.36
12 | 85.06
25 | 70.37


February 24

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   62.01
12 | 70.22
25 | 45.02

February 26

Number of Attempts | Average Time (seconds)
 -------------------|---------
5     |   55.89
12 | 42.38
25 | 35.99



Validated Time Trial (February 26th)

Attempt #| Time (seconds)
 -------------------|---------
1   |   34.908
2 | 35.908
3 | 25.251
4 | 46.864 + 2
5 | 37.793

(+2 on unsolved cube)

**Personal Best** : 25.251 seconds

**Average of 3 best** : 31.689 seconds 


### Technique Used : 'Layer By Layer'

Involves solving the white and the opposite yellow side to solve the whole cube. Mainly used by beginners to learn and get the 'feel' of the cube, eventually moving to the Ortega method and the 3x3x3.

![2x2x2 First Step goal](https://www.youcandothecube.com/resources/images/solve-it/2x2-step-3-goal.jpg) 

First step is to solve the white side. Pick a piece with white and place it on the 'top' of the cube. Pick another color on the same piece and white another piece with the two colors. Align the other piece to the bottom left front face of the cube. 

Follow this : R' D R D' (until the pictured 'goal' is the result and repeat until the white side is solved) 

![image](https://www.youcandothecube.com/resources/images/solve-it/2x2-stage-3-goal.jpg)

Now solve yellow side
* If there is one yellow piece left, then put it in bottom left. 
* No yellow pieces shown up? Align the two yellow pieces on the sides of the cube to the left. 
* If two yellow pieces show up, align one yellow piece on the side of the cube to left up of the yellow side. 

Follow this : R U R' U R U2 R' until yellow side solves. 

Lastly, solve the whole cube. 
Go back to the white side and look at the sides of the cube. Move the sides of the cubes in such a way that one side face is solved. 
If it does not, it does not matter and no change in the algorithm. 

Make sure that the solved side, if any, is at the bottom of the cube with the white side in front.

Follow this : R' U R' D2 R U' R' D2 R2

Repeat if not cube not solved. 


Sources : [Z3Cubing solving 2x2x2 Beginner](https://www.youtube.com/watch?v=rJlh5p2wAKA&t=330s), [HowToWeekly on solving 2x2x2](https://www.youtube.com/watch?v=bCn8TajrPqc&t=262s)


