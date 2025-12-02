## 功能作用
python3实现与佛论禅“佛曰”和“如是我闻”两种加密字符串的离线自动解密  
方便网站无法访问时使用或作为企事业单位内部CTF赛离线工具  

## 依赖安装  
pip3 install pycryptodome py7zr==0.15.0 -i https://pypi.tuna.tsinghua.edu.cn/simple  
> 注意py7zr新版本删除了如read/readall等旧函数，所以安装旧版即可  

## 源码参考  
https://github.com/lersh/TudouCode/  
https://gist.github.com/qinmenghua/7538e1888764587c914f2413ec299935  

## 使用方法
直接修改py文件中foYu字符串变量即可，支持“佛曰”|“如是我闻”开头的字符串；也支持直接输入密文，程序会自动判断加密类型并尝试解密
