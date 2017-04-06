## WebSocket Jetty
WebSocket on Jetty server in different implementations: <br />
JSR 356, Jetty WebSocket


### Technologies
WebSocket, Jetty, JSR 356

JSR 356 Server Endpoint: <br />
javax.websocket.ServerEndpoint

Jetty WebSocket Server Endpoint: <br />
org.eclipse.jetty.websocket.api.annotations.WebSocket <br />
javax.servlet.annotation.WebServlet


### Steps
##### Server
Start Jetty Server, deploy Endpoints: <br />
*mvn jetty:run*


##### Clients
Run Client JSR 356: <br />
*mvn exec:java@client356*

Run Client Jetty WebSocket: <br />
*mvn exec:java@client*

Path to HTML Client: <br />
*localhost:8080/websocketecho.html*



### Original Source
https://examples.javacodegeeks.com/enterprise-java/jetty/jetty-websocket-example/