# qshell 七牛云储存

```
# 保存单用户鉴权
qshell account ak sk
# 测试
qshell listbucket bucket-name

# 上传本地文件到指定空间, 可指定上传入口地址，比如北美
qshell fput bucket-name qiniu.jpg /Users/jemy/Documents/qiniu.jpg

# 同fput，但上传大文件，分片上传
# https://github.com/qiniu/qshell/blob/master/docs/rput.md
qshell rput bucket-name qiniu.mp4 /Users/jemy/Documents/qiniu.mp4

# 删除指定文件
# format: qshell delete <Bucket> <Key>
qshell delete bucket-name qiniu.mp4


```


## misc
download:
```
http://devtools.qiniu.com/qshell-v2.0.5.zip

```
