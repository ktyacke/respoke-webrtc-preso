#Communicate All the Things!

Example source code from the Communicate All the Things Presentation. 

Documentation for Respoke can be found at: https://docs.respoke.io


##connect.html
A simple example demonstrating how to create a Respoke [Client](https://docs.respoke.io/js-library/respoke.Client.html) object, and how to connect to Respoke.


##messaging.html
Building upon the connect example, this sample illustrates how to obtain reference and send a message to another endpoint using the [getEndpoint](https://docs.respoke.io/js-library/respoke.Client.html#getEndpoint) and [sendMessage](https://docs.respoke.io/js-library/respoke.Client.html#sendMessage) methods of the Respoke [Client](https://docs.respoke.io/js-library/respoke.Client.html) object.

##video.html
Continuing down our path to awesomeness, this sample show just how simple it is to establish an Audio and Video call using Respoke! Building upon the connection code from connect.html, we add a few divs to house the video elements that get returned by Respoke, and use the [startVideoCall](https://docs.respoke.io/js-library/respoke.Endpoint.html#startVideoCall) method of the [endpoint](https://docs.respoke.io/js-library/respoke.Endpoint.html) object.

##style.css
Some basic CSS styles to make things just a bit more perty...
