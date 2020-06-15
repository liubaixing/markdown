# 在CentOS7中使用 yum 安装 git2  
  
> 目前CentOS7的 yum base repository提供的git版本只有带1.8.3，内有git2X的版本，所以想要安装git2X版本需要执行如下步骤：
  
---  

### 1、删除系统自带的git 
 
```sudo yum remove git* ```

### 2、 下载对应版本的CentOS resp源
``` sudo yum -y install https://packages.endpoint.com/rhel/7/os/x86_64/endpoint-repo-1.7-1.x86_64.rpm ```

### 3、 下载完成后，下载git
``` sudo yum install git ``` 



这样就安装好了git2X。