基于原版小丸工具箱 / Maruko's Toolbox 修改而来
https://github.com/wzxjohn/marukotoolbox

使用.Net 4.8 构建
理论上支持win7，但工具箱带的 9.0ffmpeg可能不支持

更新：
为了缩小工具包体积，ffmpeg进行了重编译，版本还是9.0.2，
完全去除了硬件加速和其他没用上的编码器

新增
视频编码
svt-av1 通过ffmpeg
编码预设，便于更灵活的控制编码质量
音频编码
Opus 通过ffmpeg

修改
x264不再走之前的exe文件，改为ffmpeg

删除
字幕内嵌功能（封装功能没动），大肥鱼想偷懒，以后再说吧
AVS滤镜页
后黑功能，已过时
启动向导，已过时

NeroAAC：请另行下载编码器放入./tools文件夹中
https://www.videohelp.com/software/Nero-AAC-Codec
