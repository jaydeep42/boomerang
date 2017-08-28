Crude implementation of Boomerang using the Android Camera2 API

This implementation takes a burst shot and write the images into a GIF writer (using ndk).

This implementation is pretty slow, a future enhancement would be to render the images onto a surface view in the required order (forward - reverse - forward) and [write the framebuffer objects using video encoder to an mp4](https://github.com/uditmukherjee/boomerang/blob/master/Application/src/main/java/com/example/android/camera2basic/Camera2BasicFragment.java).
