# 一、命令行（Command）

## 1、开关机及登出（off、on and login out）



## 2、系统信息（system information）

### 2.1 uname【unix name】

**用于显示系统信息**

语法格式：

```
uname [-option][--help][--version]
```

使用方法如下：

![uname-help](/Users/solerho/Documents/command-shortcuts/Linux_images/uname-help.png)

具体实例：

|        Command         | Function                                                     | Examples                                                     |
| :--------------------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|       `uname -a`       | 显示系统的所有信息<br />show all of system information       | <img src="/Users/solerho/Documents/command-shortcuts/Linux_images/显示系统所有信息.png" alt="显示系统所有信息" style="zoom:80%;" /> |
| `uname -m`<br />`arch` | 显示计算机的架构类型<br />show architecture of system        | <img src="/Users/solerho/Documents/command-shortcuts/Linux_images/uname-m.png" alt="uname-m" style="zoom:80%;" /> |
|       `uname -n`       | 显示机器节点的名字<br />show name of machine node            | <img src="/Users/solerho/Documents/command-shortcuts/Linux_images/uname-n.png" alt="uname-n"  /> |
|       `uname -r`       | 显示正在使用的发行内核版本<br />Display the released kernel version in use | <img src="Linux_images/uname-r.png" alt="uname-r"  />        |
|       `uname -s`       | 显示内核的名字<br />show name of kernel                      | ![uname-s](Linux_images/uname-s.png)                         |

