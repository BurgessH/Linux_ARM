HSPW  水平同步信号脉宽  
HBPD  水平同步信号前肩   
HFFD  水平同步信号后肩  

一行通信的过程：控制器先发送一个HSYNC高电平脉冲（脉冲宽度是HSPW），脉冲告诉驱动器下面的信息是一行信息，然后开始显示行信息。 起始信息HSYNC高电平（脉冲宽度是HSPW）+ HBPD + 有效信息 + HFFD。  
一帧图像显示过程：VSPW+VBPD+有效信号+VFPD；  
像素：pixel  
像素间距：pitch 最佳观看距离小的近距离，间距适合远距离看；  
分辨率：resolution  横向和纵向的像素个数；800*480  
清晰度：  
像素深度：bits per pixel  多少位二进制数表示一个像素  
