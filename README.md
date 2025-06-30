# Dianzhong
点众
git报错：
1，取消代理设置
git config --global --unset http.proxy 
git config --global --unset https.proxy

2，重新设置代理
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy http://127.0.0.1:7890

3，查看配置
git config --global -l

提交代码
git add .
git commit -m "提交信息"

git remote add origin https://github.com/CreateKMM/python.git

git push -u origin master
