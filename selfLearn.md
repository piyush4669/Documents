GUI
===

### 1\> Layout Design 1

![GUI Option 1](https://i.imgur.com/EEIM7kZ.png)

1.  This is the first design that can be implemented to accommodate all
    the required settings on a single page .

2.  Colors and layout can be changed as per the needs to match the Idea.

3.  This layout is divided into three sections in which:

         -> Right most section contains **Video Conferencing** tab
         and **Chat Support** tab.
         
         -> Middle section contains all the required **whiteboards**.
          (**Note** that teacher can create as many whiteboard
           needed for the class in this section.)

         - > The last section contains all the lesson materials required 
         for the class. This section will also have **Assignments** 
         tab for distribution of the assignments to class.

### 2\> Layout Design 2

![GUI Option 2](https://i.imgur.com/wkzCoPe.png)

1.  This is the second design to accommodate all the tools required for
    the class.

2.  This has two sections :

         -> The first sections contains whiteboard with all the tools for whiteboard.

         -> The second section will have all other tools like **Chat 
           Support** ,**File Sharing** and **Video Conferencing**
           support for the class.

API
===

### Sketch Pad

[Go to **Sketchpad.pro** API
Homepage](https://developers.sketchpad.pro/simple.html)

1.  [Sketchpad.pro](http://Sketchpad.pro) is a simple graphic editor
    written for the web. This drawing library uses HTML5 Canvas
    supported by all modern browsers (Chrome, Firefox, Opera, Internet
    Explorer…). You can use any device to draw on “sketchpad”. Drawn
    sketches you can export to jpeg/png or save as .json history file.

2.  [Sketchpad.pro](http://Sketchpad.pro) is using “slices of time” as
    inputs history to store events. This approach allows co-operating
    multiple users in real-time using WebSocket server.

3.  [Sketchpad.pro](http://Sketchpad.pro) is fully customizable
    javascript library written in ES5.

### Web Cam

[FsWebcam homepage](https://www.npmjs.com/package/node-webcam)

1.  Cross platform webcam usage
2.  Live stream on browser.

### Audio

[Websockets-streaming-audio Api
Homepage](https://www.npmjs.com/package/websockets-streaming-audio)

1.  Stream audio to a Web Audio API enabled browser from Node.js server
    using Web Worker and Web Socket

2.  Plan is to make this modular enough to get added to your process as
    simple API calls - using Angularjs.

3.  I have now introduced a Web Worker to handle all server side calls -
    this fixed glitches of early versions suffered due to the single
    threaded browser

4.  Basic architecture :

<!-- -->

    Browser   <-->   Web Worker   <-->   Web Socket   <-->   Node.js

### Chat

[Twilio](https://www.twilio.com/docs/chat/tutorials/chat-application-node-express)\
 This application allow users to exchange messages through different
channels, using the Twilio Programmable Chat API.

[Socket.io](https://socket.io/get-started/chat)\
 Sockets have traditionally been the solution around which most
real-time chat systems are architected, providing a bi-directional
communication channel between a client and a server.

### File Sharing

[Droppy homepage](https://www.npmjs.com/package/droppy)

1.  **droppy** is a self-hosted file storage server with a web interface
    and capabilities to edit files and view media directly in the
    browser. It is particularly well-suited to be run on low-end
    hardware like the Raspberry Pi.

-   Responsive, scalable HTML5 interface
-   Realtime updates of file system changes
-   Directory and Multi-File upload
-   Drag-and-Drop support
-   Clipboard support to create image/text files
-   Side-by-Side mode
-   Simple and fast Search
-   Shareable public download links
-   Zip download of directories
-   Powerful text editor with themes and broad language support
-   Image and video gallery with touch support
-   Audio player with seeking support
-   Fullscreen support for editor and gallery
-   Supports installing to the homescreen
-   Docker images available for x86-64, ARMv6, ARMv7 and ARMv8

