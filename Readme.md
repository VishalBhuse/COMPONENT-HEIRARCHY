 Tic Tac Toe

In this project we have to create three component 
 <Game />
<Board />
<Square />

In <Game /> component is the parent component . In this component we are managing all our states , which tells us whether the latest move was a winning one. In this we also maintain move history.
 In the <Board /> component using props create a square box and map 9 div wrapped in the Square component.
 In the <square /> component add a button onclick all 9 div  positions and using props we are able to update value .
When all boxes  x and o check horizontal,vertical and diagonal are using the helper.js file in this file we are checking all positions which are the winner.
We are mainly <Game /> components that maintain our all states and they choose who is the winner.   


### `hierarchy diagram`
![image](https://user-images.githubusercontent.com/101569259/176237732-6f0cac3a-3280-4eac-a571-14eb51658d3e.png)
