#Log4j highlight for Sublime
对日志进行按线程和关键类型进行高亮，方便查看。
##安装
讲所有文件进入下目录即可。安装后可能需要重启Sublime。
```
C:\Documents and Settings\$user\Application Data\Sublime Text 2\Packages\GCLog4j
```
##Feature：
1. 按线程着色。
2. 关键组件高亮。
3. xml、SQL等格式识别。

##FAQ:
1. 打开日志后无法正确自动识别日志格式：
```ctrl```+```shift```+```p``` ```gclog``` ```enter```.
2. 无法正确着色：
将```GCLog4j.sublime-settings```文件拷贝到同级目录User下，重启编辑器。
