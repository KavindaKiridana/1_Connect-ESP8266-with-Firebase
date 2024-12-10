# 🚀 1_ESP8266 connect to Firebase
 Very beginner-level Firebase project; this project shows how to connect ESP8266 with Firebase and then pass dummy data to the Firebase database.

## 📂 Step guide to do this project
1. You need to have already installed VS Code with the PlatformIO extension
2. Download this project zip file and unfip it and then open the project folder from VS code
3. You need open "1_Connect-ESP8266-with-Firebase-main" on VS code and then go to src->main.cpp file
4. At the main.cpp file you will see this at line No25-No33
```
// Insert your network credentials
  #define WIFI_SSID "YOUR-WIFI-CONNECTION'S-NAME"
  #define WIFI_PASSWORD "WIFI-PASSWORD"

  // Insert Firebase project API Key
  #define API_KEY "YOUR-API-KEY"

  // Insert RTDB URLefine the RTDB URL \*/
  #define DATABASE_URL "URL"
```
5. change this "YOUR-WIFI-CONNECTION'S-NAME" , "WIFI-PASSWORD" , "YOUR-API-KEY" , "URL" according to your wifi connection name,it's password,api key,url
to get "YOUR-API-KEY" and "URL" visit this link given below 
https://randomnerdtutorials.com/esp32-firebase-realtime-database/
