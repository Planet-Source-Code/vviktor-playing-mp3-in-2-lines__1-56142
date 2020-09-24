<div align="center">

## Playing MP3 in 2 lines \!


</div>

### Description

Playing MP3 with 2 lines of code !
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[vViktor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/vviktor.md)
**Level**          |Beginner
**User Rating**    |5.0 (25 globes from 5 users)
**Compatibility**  |VB 6\.0
**Category**       |[Sound/MP3](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/sound-mp3__1-45.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/vviktor-playing-mp3-in-2-lines__1-56142/archive/master.zip)





### Source Code

Just copy this code to Form_Load event and replace !path to file! to path of mp3:<br><br>
Set MP = Controls.Add("MediaPlayer.MediaPlayer.1", "MP", Me)<br>
MP.object.FileName = "!Path to file here!"

