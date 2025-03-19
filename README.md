# Minecraft_Server

### 怎么打开server？
git pull origin 后，双击run.bat

### 怎么改server ram？
右键`run.bat`,可以用notepad edit`java -Xmx2048M -Xms2048M -jar server.jar`
break
1GB = 1024M,2GB = 2048M ...

#### 每次玩前
```shell
git pull origin
```
#### 每次玩后
```shell
close server in UI using command /stop
git add .
git commit -m "Your message"
git push origin
```
