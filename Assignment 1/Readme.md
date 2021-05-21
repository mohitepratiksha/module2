Process Management

Maintain Efficient Process Utilization on Windows 

Collect process information using the Task Viewer.

![TaskManager](https://user-images.githubusercontent.com/78703624/119179039-15de2580-ba8c-11eb-9e60-a6d652904c23.png)

Find Process ID which needs to be killed. Task Manager → Details and finds PID

![PID](https://user-images.githubusercontent.com/78703624/119179049-1a0a4300-ba8c-11eb-9f64-e86756c39e6d.png) 

Terminate a specific process using Windows PowerShell.

Open Windows Power Shell and type the command 

taskkill /pid [your pid]

![Taskkill](https://user-images.githubusercontent.com/78703624/119179070-20002400-ba8c-11eb-9bfe-9142e1b40a99.png)

Terminate multiple processes using Windows PowerShell.

Open Windows Power Shell and type the command 

taskkill /pid [your pid]  /pid [your pid]

![Multiplekill](https://user-images.githubusercontent.com/78703624/119179045-18d91600-ba8c-11eb-855e-dbd155a5dce7.png)

The task which is running in the computer gets terminated

