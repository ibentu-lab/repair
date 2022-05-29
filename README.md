# 基于对比度受限的自适应直方图均衡化的夜视增强

## 1.环境
- 系统：Windows10
- IDE:Pycharm(Profession):2018.3.7
- Python:3.6.8
- opencv:4.5.5.64

## 2.模块
### 1. 文件夹
- pic(将视频转化为图片序列)
- new_HE(对pic文件中的图片序列进行全局直方图均衡化)
- new_CLAHE(对pic文件中的图片序列进行对比度受限的自适应直方图均衡化)
- new_SSR(对pic文件中的图片序列进行(单尺度Retinex)
- new_MSR(对pic文件中的图片序列进行多尺度Retinex)
- video(原始视频video.mp4以及经过各个算法生成图片序列合并的he.mp4,clahe.mp4,ssr.mp4,msr.mp4)
### 2. .py文件
- videoTransformPicture.py(将视频转化为图片)
- pictureTransferVideo.py(将图片转化为视频)
- HE.py(全局直方图均衡化)
- CLAHE.py(对比度受限的自适应直方图均衡化)
- SSR.py(单尺度Retinex)
- MSR.py(多尺度Retinex)
