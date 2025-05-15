# WICS stands for WORKER ID CARD SYSTEM
A C++ project with sci-fi design to simulate a futiristic worker ID registration 

# Features 
- Register a new user (worker/w) [id , name , role , country , etc ]
- Display clean output inspired by futiristic ID card design i found on Pinterest 
- Save and Load to '.text' , '.json'  or '.csv' formats for impression later maybe 
- Planned a GUI using ImGUI lib
## Project Structure
- src main entry file 
- worker contain display and logic 
- worker-save output folder for all saved data 

in short the map is like this == > 

WICS/
│
├── README.md                  ← Project description + setup guide
├── /src/
│   └── main.cpp               ← Entry point of the program
│
├── /worker/
│   ├── worker.h               ← Struct and function declarations
│   └── worker.cpp             ← Function implementations (I/O logic)
│
├── /display/
│   └── visual.h               ← Optional: Display layout functions (border, color later, etc.)
│
├── /worker-save/
│   ├── data.txt               ← Saved text version
│   ├── data.json              ← Optional: JSON save format
│   └── data.csv               ← Optional: CSV export format
├── /config/
│   └── app_info.h   ← Here defined metadata (app name, version, author)

## FINALY HOW TO RUN 
  You need to have MinGW for windows installed or any c++ compiler 

the compile bash is : g++ src/main.cpp worker/logic/worker.cpp -o WICS/./WICS ...you normally dont need the .exe at the end but well tweak it until its works heh XD 


## FINALY HOW TO RUN 
  You need to have MinGW for windows installed or any c++ compiler 

the compile bash is : g++ src/main.cpp worker/logic/worker.cpp -o WICS/./WICS ...you normally dont need the .exe at the end but well tweak it until its works heh XD 

## NOTES 
- This not a web app...cant be deployed on services like VERSEL
- Everything needed inside the repo
- Terminal based on Version v.0.0.1