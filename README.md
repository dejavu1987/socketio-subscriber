# socketio-subscriber
Simple Class that manages events for your socketio app

## Usage
```js
import { socketSubscriber } from '.';

// Add event handlers
socketSubscriber.addHandlers({
  'hello': (data) => {
    // do something on hello
  }
});

// emit / broadcast events
socketSubscriber.socket.emit('message', "I am online");
```
