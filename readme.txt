basic archietecture (system design )
writing backend 
writing frontend 
### Backend Architecture ###

### Backend (Node.js)
- [x] Create a new project using `npm init` and install Express, body-      
parser, and cors with npm (`express`, `


2 browser ''

lot of event 
push to server 
-- use server xxhttp 
websokets using 
1 user makes a move - push to ws 
ws pushes the this move to user 2 
and ...
init game = 
browser 1 waiting (pending )
and another comes than 
browser1+browser2 = game 

why no mainting a queu - single variable called 

server maintain the current state of the game 
game {
    part 1
    part 23
    current state 
    events (move and time )
    startTime 
}
good idea to store in memory
1 validate the move 
store in mewmory 
send back to client
-----checkmate 
 whenever a game start and the user moves gets stores and get broadcastin to the user 2 
 server crashes thn you use all 
 and hence assume server crashes and recreate the game 

 fronend of the chess 
 - [ ] Implement front end using React 

 recovery  and scaling 
 -- if server goes down
 autoscale - more ppl more server 

 code the backend first 
