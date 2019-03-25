### pyautogui
---
https://github.com/asweigart/pyautogui

```py
import pyautogui
buttonx, buttony = pyautogui.locateCenterOnScreen('button.png')
buttonx, buttony (1441, 582)
pyautogui.click(buttonx, buttony)

import pyautogui
im1 = pyautogui.screenshot()
im1.save('my_screenshot.png')
im2 = pyautogui.screenshot('my_screenshot2.png')

import pyautogui
button71location = pyautogui.locateOnScreen('button.png')
button7location (1416, 562, 50, 41)
buttonx, buttony = pyautogui.center(button7location)
buttonx, buttony (1441, 582)
pyautogui.click(buttonx, buttony)

import pyautogui
pyautogui.alert('This is an alert box.')
pyautogui.confirm('Shall I proceed?')
pyautogui.prompt('what is your name?')
pyautogui.password('Enter password (text will be hidden)')

import pyautogui
screenWidth, screenHeight = pyautogui.size()
currentMouseX, currentMouseY = pyautogui.position()
pyautogui.moveTo(100, 150)
pyautogui.click()
pyautogui.moveRel(None, 10)
pyautogui.doubleClick()
pyautogui.moveTo(500, 500, duration=2, tween=pyautogui.tweens.easeInOutQuad)
pyautogui.typewrite('Hello world!', interval=0.25)
pyautogui.press('esc')
pyautogui.keyDown('shift')
pyautogui.typewriter(['left', 'left', 'left', 'left', 'left', 'left'])
pyautogui.keyUp('shift')
pyautogui.hotkey('ctrl', 'c')
```

```
```

```
```


