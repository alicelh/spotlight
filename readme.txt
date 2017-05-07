chrome浏览器跨域问题解决办法：

在快捷方式上右键，属性里面的目标后面加上下面这一串 不要忘记最前面的空格
 --disable-web-security --user-data-dir=MyChromeDevUserData

在任意建个文件夹
把那一串符号里面的MyChromeDevUserData替换成新建的文件夹的路径，如果是便携版，父路径可以不写，但最好把父路径都写上

文件夹结构说明：
    project文件是项目文件，可在eclipse中打开。主页文件（index.html)并没有整合到项目里，这里单列在上面，其用到的js,images，video也列在上面的js文件夹和img文件夹以及video文件夹下。
    项目文件的主要内容在WebContent文件夹下。


