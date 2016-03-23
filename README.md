#README ME
Open edX dogwood版的简体中文语言包

当前完成度大约93%，采用的是transifex的最新未审核版本。处理了几十处bug，主要集中在变量部分。

应该是能找到的追完备的版本了，预期自己动手，不如加入我们一起改进它吧 

翻译不当的地方欢迎在issue中指出,或者直接提交pull requests

#Usege
###切换环境
```
sudo -u edxapp bash
source /edx/app/edxapp/edxapp_env
```

###拉取到本地
```
cd /edx/app/edxapp/edx-platform/conf/locale/zh_CN/LC_MESSAGES/
rm *
wget 
wget 
```

###使用翻译文件
```
cd /edx/app/edxapp/edx-platform
paver i18n_fastgenerate
```
###重启edxapp
```
exit
sudo /edx/bin/supervisorctl restart edxapp:
```
