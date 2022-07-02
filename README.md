# Connect-Four
The famous minimax algorithm, which is a decision rule used in AI, is applied. The project goal is to investigate how a decision tree is applied using the minimax algorithm in this game by Artificial Intelligence.

A Decision tree is a tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label

When the game begins, the first player gets to choose one column among seven to place the colored disc. There are 7 columns in total, so there are 7 branches of a decision tree each time. After the first player makes a move, the second player could choose one column out of seven, continuing from the first player’s choice of the decision tree.

Minimax algorithm is a recursive algorithm which is used in decision-making and game theory especially in AI game. It provides optimal moves for the player, assuming that the opponent is also playing optimally. For example, considering two opponents: Max and Min playing. Max will try to maximize the value, while Min will choose whatever value is the minimum. The algorithm performs a depth-first search (DFS) which means it will explore the complete game tree as deep as possible, all the way down to the leaf nodes

![image](https://user-images.githubusercontent.com/104484529/177006498-2dcc463b-e3ab-4ff6-8930-127f30a7601d.png)
