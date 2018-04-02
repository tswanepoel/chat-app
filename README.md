## Run [PeerServer](https://github.com/peers/peerjs-server)

Install the library:

    $> npm install peerjs -g

Run the server:

    $> peerjs --port 9000 --key peerjs
    
## Run the app

Install [http-server](https://github.com/indexzero/http-server):

    $> npm install http-server -g

Run the app:

    $> http-server -p 4200
    
## Browse the app

From one browser, visit:

http://localhost:4200/?id=id&peerid=peerid

And from another browser, visit:

http://localhost:4200/?id=peerid&peerid=id
