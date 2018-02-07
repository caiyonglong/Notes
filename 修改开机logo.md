#设置开机logo
```
1、修改的文件路径
LINUX/android/bootable/bootloader/lk/splash
2、准备好logo图片(png、bmp格式)
3、查看中原图片的分辨率，修改logo图片*保证分辨率一致*
4、生成splash.img镜像文件
```
生成splash 步骤
```
The steps to generate a splash.img:

1 sudo apt-get install python-imaging

2 python ./logo_gen.py boot_001.png (*.bmp)

```
