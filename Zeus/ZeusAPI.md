# The Zeus API

The Zeus API is written in TypeScript.

## Technology

### Node.js

The Zeus API uses Node.JS to communicate with devices. Net sockets are utilized for
bidirectional communication.

### TypeScript

TypeScript was chosen as the language due to its strictness. I also have not done a project
of my own in TypeScript and wanted to try it out. I utilize the typing library provided by
DefinitelyTyped who run a huge library of TypeScript types.

### Jest

The testing framework of the API is written in Jest.

### PM2

To keep the API up and running, PM2 is utilized as the daemon.

## Challenges

### API

I have very little experience with writing server-side code, and this is the lowest level I
have gone with JavaScript/TypeScript. Using the raw Node.js library is something new to me.
Previously, the furthest server-side code I had written was with Express.js. However, since
I wanted to have bidirectional communication, an Express.js API was not going to work for
me. Socket.io seemed to be a viable option, but I decided not to since I was going to have
cross platform communication, and wanted to have more control over the overall architecture.
