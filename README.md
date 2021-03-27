# lab11

The weather script will refresh every 60 mins, using your IP address to determine your location. The following steps will help you install the service.

1. In your user home directory (ex. /home/<USER>), using the "mkdir" command create a folder "week11'
2. Now lets go into "week11" directory by using "cd week11", and using the same command above create a folder call bin using "mkdir bin" 
3. place the "weather", "weather.service", and "weather.timer" scripts here
4. using the following command, you will copy the "weather.timer" and weather.service" into your /etc/systemd/system directory
        - "sudo cp weather.service /etc/systemd/system"
        -  "sudo cp weather.timer /etc/systemd/system"
5. Using the following command will reload those files "sudo systemctl daemon-reload"
