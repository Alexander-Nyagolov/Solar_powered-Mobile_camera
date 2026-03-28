# Solar powered mobile camera
To monitor the progress of a personal 3D printer,
I’m combining a standard CMOS camera with an ESP32. The headers are read in real time
and converted into an image via a library,
which is sent at each iteration of the cycle.
Power is supplied primarily by a lithium battery,
which is charged via a solar panel, but also has the option of
micro USB. The device is enclosed in a specially
designed and printed case and features a power
button. OTA updates are also supported here.
