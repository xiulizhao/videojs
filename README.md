# videojs  
视频播放器<br>
控制属性<br>
data--vsrc	需要播放的视频的路径。首先把需要播放的视频文件放入当前项目/static 文件中, 那么视频地址就为 /xxx.mp4. 注意:只有对应的视频文件存在, 本元素才可正常播放。若开启视频清晰度选择按钮,则视频源路径不需要设置.	/oceans.mp4<br>
data--poster	设置视频的海报,视频的海报表现为视频初始化之后，视频表面默认显示的图片.	/img/demo.jpg<br>
输出属性<br>
data-x-currenttime	视频播放时，输出视频播放的时间，该时间是指视频目前播放了多久。该值为秒数，即如果值是6，表示视频已经播放了6秒	"6.698357"<br>
data-x-duration	播放器添加视频,输出该视频时间总长度,以秒计算.	"366.6"<br>
data-x-state	视频播放器输出当前的播放状态	play/pause/ended<br>
元素事件<br>
#	属性名	属性说明	值示例<br>
发出事件<br>
videoended	当视频播放结束的时候发出的事件<br>
videoplay	当视频播放开始的时候发出的事件<br>
videotimeupdate	视频正在播放时触发，即只要视频正在播放，该事件就存在<br>
videoplaying	当视频播放中的时候发出的事件<br>
videopause	当视频暂停中的时候发出的事件<br>
videovolumechange	当视频音量改变的时候发出的事件<br>
