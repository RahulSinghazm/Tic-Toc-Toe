# Tic-Toc-Toe
![photo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSd0kMyTFgmAudk1BkoUtp3TX0HGK9k_lBc6rbIOYlSgH_8znRUNw)

## About
Game using python Basics Tuples,Dictionary,Lists and etc.
![photo](https://i.ytimg.com/vi/V3LhwtmjlOY/maxresdefault.jpg)
Using jupyter notebook tictoctoe game
# Possible Cases
![photo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkFBkYkQdhR5nYFLhIJEbRIdrH3Wuw7fxgO3AL6ZGm0aDr5_WQGw)
Many more!
# Codes
## Use of while loops and the functions you've made to run the game!

 while game_on:
 
        if turn == 'Player 1':
        
            display_board(theBoard)
            position = player_choice(theBoard)
            place_marker(theBoard, player1_marker, position)
            if win_check(theBoard, player1_marker):
                display_board(theBoard)
                print('Congratulations! You have won the game!')
                game_on = False
            else:
                if full_board_check(theBoard):
                    display_board(theBoard)
                    print('The game is a draw!')
                    break
                else:
                    turn = 'Player 2'
        else: 
        
            display_board(theBoard)
            position = player_choice(theBoard)
            place_marker(theBoard, player2_marker, position)
            if win_check(theBoard, player2_marker):
                display_board(theBoard)
                print('Player 2 has won!')
                game_on = False
            else:
            
                if full_board_check(theBoard):
                    display_board(theBoard)
                    print('The game is a tie!')
                    break
                else:
                    turn = 'Player 1'
                    
    if not replay():
        break


![screenshot 72](https://user-images.githubusercontent.com/34129569/40606487-22bcb1cc-6283-11e8-89bb-ea51d0e8462f.png)

![screenshot 71](https://user-images.githubusercontent.com/34129569/40606529-486d15d8-6283-11e8-9e84-edec2d6c8d0f.png)
