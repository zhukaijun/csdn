# csdn
爬取csdn博客的爬虫

## 详情
[CSDN博客转高清PDF](https://spygg.github.io/2019/04/12/CSDN%E5%8D%9A%E5%AE%A2%E8%BD%AC%E9%AB%98%E6%B8%85PDF/)

来源:主要是为了学习ffmpeg,然后看到雷神大人的博客太好了(但是广告太多了....),就爬取下来了,理论上可以爬取所有的csdn

请注意:
因为不能上传大的附件,所以有需要做好的pdf,请发邮件至liushidc@163.com
如果是爬取雷霄骅的博客,请将csdn.zip(数据库文件)解压到当前文件夹后运行>>>>>

$ python csdn.py
这样可以避免不必要的服务器压力,请低调使用()

致敬雷神大人!

## 注意事项
* 安装所有需要的库
* 安装 wkhtmltopdf

## 更新
更新:修正了pdf中图片可能会挂掉的bug

更新:修正了目录页面,但是会引入页面图片被csdn封的bug(暂时无法解决)

更新:修正了反爬措施,修正了Windows下编码错误

更新:修正了图片索引为src="//img-blog"的错误,修正转化成PDF时死循环的bug(发现目录索引为空的bug)

更新:(20191113)


