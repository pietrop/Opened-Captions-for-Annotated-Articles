# What is Opened Captions?

At a high level Opened captions gives you a live text stream of C-Span Channel 1 captions. 

Project by Dan Schultz, made while on a Knight-Mozilla fellowship at the Boston Globe.



## Opened Captions service // overview

<!-- TODO: this needs revie by Dan -->


>Getting a live transcript requires three things:
- A video feed that can be connected to a computer.
- Something (hardware or software) to extract and parse closed captions.
- A server to push those captions to the web.

>Opened Captions runs on a Mac mini connected to a DirecTV feed in Globe Lab, the newspaper’s skunkworks.
“When the Lab started, we were like, ‘We need a video feed in here,’ and we didn’t really know why,” Chris Marstall, who runs the Lab, told me. “But this really fits that perfectly.”

>Between the video feed and the Mac mini is TextGrabber, a $300 converter (literally a black box) that extracts closed captions and feeds text over a serial port. The Mac mini runs an instance of the Opened Captions server, a Node.js application that pushes captions to a web server at MIT. If you connect to the Opened Captions website, you’re hitting that server at MIT, which acts as a proxy.
The beauty of this system is that, in theory, the captions feed could come from anywhere. Schultz’s grand vision for Opened Captions involves lots of inputs transcribing lots of channels. CNN, for example, could start feeding its own broadcast into Opened Captions (or it could run its own captions server).


