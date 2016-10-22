# ImageParticle
 把图片像素生成粒子效果

 关于出现：Uncaught SecurityError: Failed to execute 'getImageData' on 'CanvasRenderingContext2D': The canvas has been tainted by cross-origin data，错误的

Chrome:
1、得到Chrome的安装路径，例如：‘C:\Users\-your-user-name\AppData\Local\Google\Chrome\Application>’
2、在命令行窗口，输入安装路径，加上–allow-file-access-from-files参数，例如：‘C:\Users\your-user-name\AppData\Local\Google\Chrome\Application>\chrome.exe –allow-file-access-from-files’，回车执行，启动Chrome
3、测试的一个临时方法:：复制一个Chrome的快捷方式，右键》属性》目标的文本框中加上参数–allow-file-access-from-files，例如：”C:\Program Files (x86)\Google\Chrome\Application\chrome.exe” –allow-file-access-from-files
Firefox，IE：默认可以加载本地图片

On Mac：

Chrome：从命令行窗口中启动，启动命令为open /Applications/Google\ Chrome.app –args –allow-file-access-from-files

Safari：
1、Safari》偏好设置》高级》勾选“在菜单栏中显示‘开发’菜单”
2、开发》勾选“启用WebGL”
3、开发》勾选“停用本地文件限制”
