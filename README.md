# Usage

    
    var io = require('./lib/io.js');
    
    var socket = io.connect('http://127.0.0.1');
    socket.on('connect', function(){
    
      console.log('haha');
    
    });

## Only websocket transport is supported