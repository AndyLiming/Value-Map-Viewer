# Value-Map-Viewer
A software to visualize some special images that saved as non-regular files
在视差、深度、光流估计等任务中，我们往往需要查看视差图、深度图等信息。一方面我们需要保存的文件或数据集中的文件需要保存其原始数值，没有任何归一化或缩放，一般保存为.npy, .exr, .pfm, .pgm等文件格式；另一方面如果想要查看及可视化这样的图片，则需要归一化到0-1或0-255保存为如.png或.jpg等文件格式。
本工程实现了读入并显示包括常规图片格式、以及npy,exr这样保存原值但不能直接可视化的图片。