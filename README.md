#Log4j highlight for Sublime
对日志进行按线程和关键类型进行高亮，方便查看。
![截屏](https://raw.github.com/kidylee/GCLog4j/img/img/Screen.png)
##安装
所有文件放置在目录中即可，安装后可能需要重启Sublime。 
```
C:\Documents and Settings\$user\Application Data\Sublime Text 2\Packages\GCLog4j
```
##Feature：
1. 按线程着色。
2. 关键组件高亮。
3. xml、SQL等格式识别。
4. 高亮所有以[$USE_CASE_NAME]开头的日志。

##FAQ:
1. 打开日志后无法正确自动识别日志格式：
```ctrl```+```shift```+```p``` ```gclog``` ```enter```.
2. 无法正确着色：
将```GCLog4j.sublime-settings```文件拷贝到同级目录User下，重启编辑器。
