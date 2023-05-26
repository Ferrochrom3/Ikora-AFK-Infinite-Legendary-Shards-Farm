# Macros

!!!Important Note!!!
If your mouse is not going where the exotic is in Ikora's menu, it's because Ikora has some different paragraph length for different exotics, ikora_x_pos and ikora_y_pos may be off the the exotic.

Try the following to find your exact coordinates.
Add the following lines after line 27, which line 27 is while run:
print(pyautogui.position())
break

Run the file, it will give you your current mouse location (make sure to put your mouse where you wanted it to before executing). Then it's going to break out of the loop to prevent further execution. Just remove those two lines of code after you found your coords. The coordiates you get will be your new ikora_x_pos and ikora_y_pos.

1920x1080
adjustment_value: 100
ikora_x_pos: 1169
ikora_y_pos: 753
x and y pos: 1392, 270 (Helmet)
x and y pos: 1392, 394 (Gaunlets)
x and y pos: 1392, 518 (Chest)
x and y pos: 1392, 642 (Leg)

2560x1440
adjustment_value: 156
ikora_x_pos: 1541
ikora_y_pos: 1006
x and y pos: 1856, 364 (Helmet)
x and y pos: 1856, 527 (Gaunlets)
x and y pos: 1856, 690 (Chest)
x and y pos: 1856, 853 (Leg)

Required Library Installs: 
pip install pyautogui
pip install keyboard


