1. 取消所有代理
```
	git config --global --unset http.proxy 
	git config --global --unset https.proxy
```
2. 设置代理（例如：clash）
```
git config --global http.proxy http://127.0.0.1:7890
```
3. 