# Team AO1

## Project Summary

The project deviated a little from my previously submitted design document. I decided to use WebAssembly and WebRTC together. This way, the code will be close to the metal.

### Final Expected State

The final state of the application is supposed to be using a GPU based background substraction tool ported to webassembly, and integrated with JavaScript to remove the background in real-time. The getUserMedia stream is provided to the webassembly code on which the operations are performed.

### Current State

**The code is incomplete and not compilable** since I couldn't complete the webassembly integration with webrtc in time. I was able to port one of the C++ file with chroma key filtering to webassembly.

## Technology Used

* WebAssembly
* WebRTC
* C++ (for chroma key filtering)

## Feasibility

This solution is completely doable and given enough time and resources.
