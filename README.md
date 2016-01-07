# real-time-video-looper

I could not find a way to set loop points for a video in real time, so I decided to give it a shot at making one.

To set loop start you bang the blue button which gets the current time in the video, outputted by the route object, 
and sets that to to the loop start of the jit.movie object. The same goes for the loop end. Each loop's respective button
determines which gate outlet is sending out the current movie time.

The button marked clear sets the loop start to the loop end marker, and the loop end marker is set to the very end of the video.

