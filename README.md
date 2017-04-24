# 创建本地仓库

# step1 配置

config.yaml文件设置：（不需要http://）
uplinks:
  npmjs:
    url: localhost:4873/
	
	
.npmrc文件：（prefix是仓库位置）
prefix=C:\Users\Administrator\AppData\Roaming\sinopia\storage
registry=http://localhost:4873/


# step2 运行：

cmd执行sinopia
另一个cmd 打开项目文件夹
执行npm install <module_name>
即可下载本地仓库模块