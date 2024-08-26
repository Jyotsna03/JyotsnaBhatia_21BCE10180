
# Chess Turn-based Battle

A turn-based chess-like game with a server-client architecture, utilizing websockets for real-time communication and a web-based user interface.

## Tech Stack

**Client:** HTML, CSS, JavaScript, WebSockets (via Socket.IO). 

**Server:** Node.js, Express.js, Socket.IO (Server), HTTP Server.


## Deployment

1.Server Setup:



Change directories to the server folder and install the required dependencies using npm:

```bash
  npm run 
```
2.Start the Server:

Run the server using the following command:

```bash
  node server.js  
```
This will start the server, typically running on https://chess-websocket-rolh.onrender.com/
## Features

🎯 The game is designed for two players. Each player controls a team of five characters: 2 Pawns, Rook, and Bishop. Players take turns strategically moving their characters across the board according to the game rules.


- Pawn (P): Moves 1 step forward.
- Rook (R): Moves up to 2 steps in any straight direction.
- Bishop (B): Moves up to 2 steps diagonally.
- Queen (Q): Moves up to 3 steps in any direction.


It also involves websocket communtication along with :
- 🎯 Game state update
- 🎯 Invalid move notification
- 🎯 Game over notification


🎯 How to Play:

On your turn, simply click on one of your characters and choose a valid move from the available options. As moves are made, the game state updates in real-time, reflecting the new positions of all characters. The game continues until one player eliminates all of the opponent's characters, claiming victory!


## Screenshots

![Chess 3](https://github.com/user-attachments/assets/2526e800-32d3-420b-ad8e-21a4de497751)
![Chess 4](https://github.com/user-attachments/assets/e67e32a7-4cfb-4648-abe8-974050c46215)![Chess 1](https://github.com/user-attachments/assets/d6cf72f6-7659-41fd-8dd9-5157dc2cad82)
![Chess 2](https://github.com/user-attachments/assets/af619a22-7272-4103-a0c3-213e067548c3)



##  MIT License

Copyright (c) 2024 Jyotsna03

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## 🚀 About Me
- 🔭 Hello World!
- 🚀This is @Jyotsna03, a student at @VIT Bhopal, open to collaborate and work with you.
- 👯 I am currently looking for internships and jobs as a fresher.
- 🤝 I'm a Code Wizard in the day and by night, I'm a Visionary mind exploring designs and learning about product management
- 🌱 I’m into Big Data and Machine learning.
- 🎗️ I am digging my hands on Web Development.
- 💬 You can contact me at work.jyotsna01@gmail.com
- ⚡ Fun fact: Why do Java developers wear glasses? Because they don't see sharp.



