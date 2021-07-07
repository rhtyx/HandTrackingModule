# HandTrackingModule
This is the module you can use to track hands.
These are the steps to use this module.

1. open "HandTrackingModule.py"
2. copy line 44 to 62 and paste it to your project file
3. type "import HandTrackingModule as htm" below "import time"
4. change "detector = handDetector()" to "detector = htm.handDetector()"

If you don't want to draw the line on to your hands, follow these steps.

1. open your file project with the code from HandTrackingModule.py
2. change "img = detector.findHands(img)" to "img = detector.findHands(img, draw = False)"
3. change "lmList = detector.findPosition(img)" to "lmList = detector.findPosition(img, draw = False)"
