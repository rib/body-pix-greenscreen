Experimental green screening based on BodyPix TensorFlow model

This little test uses [BodyPix](https://github.com/tensorflow/tfjs-models/tree/master/body-pix)
to segment your body from your background and then simply clears the background to green.

The idea is that something like this could then be composited within OBS as if you were standing
in front of a real greenscreen.

Live demo at https://rib.github.io/body-pix-greenscreen/

(Note it takes a little while to load the model after enabling your cam and doesn't currently give
any feedback until it's loaded)
