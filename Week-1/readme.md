A web browser is basically a tool/software that helps us to browse the internet. Basically it gives the access to get opened to the world. So a web browser works in a way to get the data from all over the web/internet and format it and then display to the user. The data basically travels through HTTP protocols and a web browser interprests these data and helps us to retrieve information. So the browser is able to do all these things due to the different components that a browser has. All these components make the browser work efficiently and give the data/information as expected. So the major components of a browser are -: 

1. UI - user Interface is the most important part of the web browser as it contains the essential parts i.e the back/forward button, address bar, menu, etc.
2. Browser Engine - It acts as a middle man between UI and the rendering engine.
3. Render Engine - The rendering engine does all the action in displaying the requested content.
4. Networking - The networking tells about the different protocols behind the the platform-independent interface.
5. UI Backend - The backend uses O.S interfaces so that the browser becomes platform independent.
6. JavaScript interpreter - This helps browser to execute JavaScript code.
7. Data Storage - This helps browser to save cache or sesion data or some local data which may help browser to save some time in next renders.

The tree construction in a browser happens with tokens from the tokenization system where the DOCTYPE, start tag, endtag and all other identifers are presnet and then the DOM construction starts with the DOM object from the parser and then followed by the HTMl ending and closing tags and head and body atgs where all the nodes are attached to the body tag.

Then when the browser encounters with any script tag then browser pauses all the other actions to download the script and once it is downloaded the rest of the tasks proceeds. If the HTML is paused then again it starts rendering.

So what happens when we type a url into the address bar?

The browser basically performs a particular action step by step to get the result into our page.

1.When we type the url and press enter or hit it the URL gets devided into 4 parts basically using the browser Engine.
    1. Sheme- It basically checks for the https or http. So basically it tells the broser to go with transport layer security or not.
    2. Domain- The domain name is the address that we easily remember like google.com and in the dns of google we will get the ip address of it.
    3. Path- This basically checksany additional path in the url like /user or /signin.
    4. Resource- this basically is the final content that the browser needs to render like an HTML file.
2. The browser gets the IP address of the URl by doing a DNS lookup. once it is able to get the IP in the DNS and then it starts with searching the IP in the internet using the network engine of the browser.
3. After finding the IP then the browser initiates a TCP connection with the server and then the data exchange happens with the help of Packages and the rendering engine parses the HTML tree and the rendering tree is generated and also Javascript interpreter handles the JavaScript Code, where all the storage layer and Ui backend comes into picture in establishing the proper Render tree and the exact Javascript output.
4. As now the connection is established the browser tries to follow HTTP protocol for getting and sending back data to nad from the server using this protocol.

![alt text](./Drawing.png)