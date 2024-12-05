java cFinal Project Proposal 
 
Project Descriptton 
Our project involves creattng an innovattve card fusion game, named “2048 Fusion Card Game”, 
using MATLAB's App Designer. This game combines the logic of the classic 2048 game with card 
game mechanics, with the objecttve of achieving a 2048 card in all ffve columns of the game 
board. 
Game Rules: 
1. Card Generatton and Dragging: 
o The game interface is divided into two secttons: 
▪ Bottom Card Tray (3 slots): Three random cards will be generated, with 
values 2, 4, 8, 16, 32, or 64. 
▪ Top Game Board (5 columns x up to 10 rows): Players can drag cards 
from the bottom tray to any of the ffve columns on the game board. 
o Each ttme a card is placed in the top board, a new random card is generated in 
the bottom tray. 
2. Card Fusion Rules: 
o When two adjacent cards on the top board have the same value, they will 
automattcally fuse into one card with a value equal to the sum of the two 
original cards. 
o Cards with higher values cannot be placed directly on top of cards with lower 
values. For example, an 8 card cannot be placed on top of a 4 card; the player 
must ffrst fuse two 4 cards to form an 8 card before proceeding. 
3. Winning Conditton: 
o The player wins when each of the ffve columns on the top board contains at 
least one card with a value of 2048. 
4. Losing Conditton: o The player loses if any column on the top board exceeds 10 cards. 
o 
General Descriptton of Implementatton 
We will use MATLAB's App Designer to develop the game. The main functtonalittes include: 
1. Card Generatton and Dragging: o Implement a random number generator to control card creatton in the bottom 
tray. 
o Create drag-and-drop functtonality to allow players to move cards from the 
bottom tray to the top game board. 
2. Card Fusion and Placement Rules: 
o Develop a fusion logic functton to detect and merge adjacent cards with the 
same value. 
o Enforce placement restricttons to ensure proper gameplay mechanics. 
3. Winning and Losing Condittons: 
o Conttnuously monitor the top game board to determine if the player wins (2048 
in all columns) or loses (a column exceeds 10 cards). 
4. Game Interface Design: 
o Design a user-friendly graphical interface using App Designer, complete with 
animattons and nottffcattons. 
Reach Goals 
1. Add animatton effects for card generatton and fusion to enhance the visual appeal. 
2. Include sound effects, such as card drag sounds, fusion sounds, and victory/defeat 
alerts. 
3. Introduce difffculty setttngs, such as: 
o Increasing the probability of generattng higher-value cards. 
o Adding pre-existtng cards on the top board at the start of the game. 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
