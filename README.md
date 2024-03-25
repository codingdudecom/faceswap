# [Face Swap in Python](https://www.coding-dude.com/wp/ai/face-swap-python/)

See the link for an explanation of the code.

To run the script you'll need to install dlib (http://dlib.net) including its
Python bindings, and OpenCV. You'll also need to obtain the trained model [from
sourceforge](http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2).

Unzip with `bunzip2` and change `PREDICTOR_PATH` to refer to this file. The
script is run like so:

    ./faceswap.py <head image> <face image>

If successful, a file `output.jpg` will be produced with the facial features
from `<head image>` replaced with the facial features from `<face image>`.

## Alternative Face Swapping Solutions

This script offers great results and the advantage of running locally. It has been successfully integrated with Photoshop as a Photoshop action that you can download here: [Face Swap in Photoshop](https://www.psd-dude.com/tutorials/resources/face-swap-in-photoshop.aspx).

In some cases, results are not so great and you might notice color differences or abnormal warping. The best results are offered by proffessional face swap and deep swap tools. For example, the best tool available at this moment is something like the MockoFun's [online face swap](https://www.mockofun.com/face-swap/) tool. It is 100% free to use offering free monthly swaps or a Premium Subscription for even more swaps and options!

