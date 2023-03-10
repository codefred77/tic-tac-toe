# tic-tac-toe

# Description
The classic Tic Tac Toe game implemented using React

# Roadmap of Future Improvements
1) Modify the Square component so that clicking is disabled after the first click. Once a player has entered X or O the square should be disabled. Use a new state variable ('filled') inside the Square component that is initially false and is set to true once it has been clicked. Use the this state to assign it to the disabled property of button:

    <button disabled = {filled} onClick={() => {setTik(takeTurn(id)); setFilled(true);}}>
    ...
    </button>
    
2) Disable all squares once a winner is determined or all 9 squres have been clicked. For this to be possible, the Board parent component would have to pass a new prop to the Square children components to force them all to get disabled

3) Add a "Reset" button to re-start the game

# License
MIT License

Copyright (c) 2022 codefred77

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
