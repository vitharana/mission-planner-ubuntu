Adding A script that will automatically create the destop entry for the mission planner app

```nano ~/.local/share/applications/missionplanner.desktop```


```[Desktop Entry]
Name=Mission Planner
Exec=mono /home/chamika/Downloads/MissionPlanner-latest/MissionPlanner.exe
Icon=application-x-executable
Type=Application
Categories=Development;Utility;
Terminal=false
```

```
chmod +x ~/.local/share/applications/missionplanner.desktop
```




