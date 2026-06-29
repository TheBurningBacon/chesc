# chesc

version of chess but worse

monks    (◉ ) can move 1 diagonally(in an x) or 2 orthogonally(in a +)

bankers  (◬ ) can move 3 diagonally or 3 orthogonally

bakers   (◓ ) can move 8 orthogonally

farmers  (◇ ) can move 8 diagonally or 1 orthogonally

truckers (◈ ) can move 4 diagonally or 4 orthogonally

guards   (▣ ) can move exactly 2 orthogonally then 1, 2, or 3 orthogonally in a perpendicular dircetion

    guards are special as they can move through pieces but get scared and can't move if there are 3 or more pieces nearby
'''text
        | |x| | | |x| |
        |x|x|x| |x|x|x|
        | |x| | | |x| |
        | | | |0| | | |
        | |x| | | |x| |
        |x|x|x| |x|x|x|
        | |x| | | |x| |
'''
royals   (▣ ) can move 1 in any direction
advisors (◦◦) can move 2 diagonally 

if you have no farmers and no truckers you lose the game

if you have no bankers and 2 bakers you lose the game

if you have no bakers and 2 bankers you lose the game

if the enemies advisor is next to your royal you lose the game

if you get all your monks on the last rank you win the game

notation is entered in as (piece you want to move)(were to move) with no spaces
ex: A3A2 would move the piece on the A3 tile to the A2 tile