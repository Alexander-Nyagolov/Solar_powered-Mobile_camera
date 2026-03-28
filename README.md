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
![camera](https://github.com/user-attachments/assets/e22a8271-3e0b-4faa-a76c-912d7cd4b898)
<img width="272" height="340" alt="camera-show" src="https://github.com/user-attachments/assets/8f6a8abe-278d-4932-a9f1-b1281371f5db" />
<img width="609" height="358" alt="Schematic-no-fifo" src="https://github.com/user-attachments/assets/959af6b9-645c-46c2-bc43-ee0a0372cf2e" />
