# mpv.conf

```
# mpv conf>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

# 忽略默认快捷键！
no-input-default-bindings

# 消息文字尺寸
osd-font-size=40

# 开始播放时短暂显示的信息：文件名
osd-playing-msg="${filename}"

# 播放结束后不退出
keep-open=yes

# 高优先级
priority=high

# 图形>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

# 全屏独占
#d3d11-exclusive-fs=yes

# 外部边框
border=yes

# 置顶
ontop

# 窗口缩放50%
geometry=50%

# 平滑刷新
#video-sync=display-resample
#interpolation
#tscale=oversample

# 记忆播放
save-position-on-quit

# 软解
hwdec=no

# 增强4K解码性能
vd-lavc-dr=yes
opengl-pbo=yes

# GPU API - d3d11
gpu-api=d3d11

# 渲染质量 - 高
profile=gpu-hq

# 渲染算法
scale=ewa_lanczossharp
cscale=ewa_lanczossoft
dscale=mitchell
scale-antiring=0
cscale-antiring=0
dither-depth=auto
correct-downscaling=yes
sigmoid-upscaling=yes
deband=yes

# 视频输出格式
d3d11-output-format=auto

# RGB范围
video-output-levels=full

#补帧
#vf-append=vapoursynth="~~/FPS.vpy"

# 全屏时HDR直通(实验性，需提前开启Windows10 HDR开关)
#d3d11-output-csp = pq

# 声音>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

# 默认音量
volume=45

# 最大音量
volume-max=200

# 重映射为立体声
audio-channels=stereo

# 规格化
audio-normalize-downmix=yes

# 音频API-WASAPI
ao=wasapi
#audio-exclusive=yes

# 字幕>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

# 修正字幕
#sub-ass-vsfilter-aspect-compat=no
#sub-ass-vsfilter-blur-compat=no

# 字幕分辨率渲染同步
blend-subtitles=video
```
