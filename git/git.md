# git代理设置  

## 全局代理  

```cisco
    git config --global https.proxy "http://127.0.0.1:7899"

    git config --global http.proxy "http://127.0.0.1:7899"
```  

## 查看代理

```c
git config --get --global http.proxy
git config --get --global https.proxy

```  

## 删除代理

```
   git config --global --unset http.proxy
   git config --global --unset https.proxy
    
```