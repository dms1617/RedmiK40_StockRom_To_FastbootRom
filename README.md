# 使用方法

用github actions，只需要填写K40官方卡刷包链接，全自动云端转为线刷包。

1、首先登录你的github帐号，点击右上角的Fork这个项目到你的帐号。

2、打开.github/workflows/FastbootTool.yml编辑
ROM_URL后面换成自己想要的k40官方包链接，ROM_Version后面填写版本名字（这个随便填写，只是方便区分）

3、编辑完后点击start commit，commit Changes进行保存。

4、点击那个星星Star,然后就开始自己处理了(过程一般大概三四十分钟)

5、查看进度，点击Actions菜单栏（如果第一次使用有Workflows aren’t being run on this forked repository提示，点击绿色的I understand my workflows, go ahead and enable them按钮，然后取消星星重新第4步），打开make,Upload to WeTransfer中找到Download link:xxx就是下载地址

6、注意，由于刷机包太大，打包时候进行了分卷压缩，下载链接会有两个，请下载两个压缩包（xxx.7z.001和xxx.7z.002），放在一起解压。
