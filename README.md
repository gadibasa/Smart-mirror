# Smart-mirror with Raspirry pi
smart mirror integrates various features such as weather updates, calendar events, and news headlines into a single interactive interface. This project aims to enhance your daily routine by providing essential information at a glance.
- Weather Updates: Fetch real-time weather updates for your specified city using the OpenWeatherMap API.
- Calendar Events: Display upcoming Google Calendar events with seamless integration.
- News Headlines: Fetch and display the latest news headlines using the NewsAPI.
![image](https://github.com/user-attachments/assets/e15cb4ae-edaa-46f0-ad38-82c545e22b75)

Hardware requirments:
- Raspberry Pi (any recent model)
- MicroSD Card (8GB or larger)
- Power Supply for Raspberry Pi
- HDMI Monitor or Smart Mirror Setup
- USB Keyboard and Mouse (for initial setup)
- Internet Connection
![image](https://github.com/user-attachments/assets/b762de82-04ee-4094-975a-e755a851aa25)
SW Requirments:
- Raspberry Pi OS: Ensure you have the latest version of Raspberry Pi OS installed.
- Xvfb: X Virtual Framebuffer for running GUI applications in a virtual display environment.
![image](https://github.com/user-attachments/assets/1a7cc32f-5f9c-474d-af2d-55f054b63ea9)
The Smart Mirror project successfully integrates weather updates, calendar events, and news headlines into a single interface. Its robust timeout mechanism ensures smooth functioning even with feature-specific issues. Enhance your daily routine with essential information conveniently!
![image](https://github.com/user-attachments/assets/75feeb65-7ccd-4e7e-8af4-d00174671961)

you can build and run following to get simulation in hand on linux machine:
./run_smart_mirror.sh 
Starting application... 
Updating display... 
Fetching weather... 
Weather fetched: Clouds, 26.97°C 
Fetching calendar events... 
Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=422196075405-cipcr83hn263e38t0pbutooqg659po5u.apps.googleusercontent.com&redirect_uri=http%3A%2F%2Flocalhost%3A38263%2F&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcalendar.readonly&state=MsligTxyQZnn0znQUMuOPw5JNpxk0q&access_type=offline 
Calendar request timed out. 
Fetching news... 
NewsAPI response: {'status': 'ok', 'totalResults': 0, 'articles': []} News fetched: 0 articles Display updated.
 Application running.
![image](https://github.com/user-attachments/assets/b133661b-2ad5-4ce5-8a21-18a5c0286b1b)





