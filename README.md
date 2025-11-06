# Audacity Websockets Client
A client to recieve websocket commands for recording in Audacity.

## Usage
1. Download Python 3.10+
2. Once Python is installed download the src folder from github
3. Open the folder in your terminal
4. Run ```pip install -r requirements.txt```
5. Make sure Audactiy has scripting turned on!
6. Run Audacity
7. Run ```python main.py``` and it should (hopefully) start!
8. Currently it only has start and stop recording functionality, this can be done by sending a websocket request on port 8001
   - To start recording send the request: recStart
   - To stop recording send the request: recStop
### Please open issues with any issues and ill look at them, i have had issues with crashing on windows! So again any issues are appreciated :)

Have a wonderful day!
