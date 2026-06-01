背景：初见时遇到的是关于泰坦尼克的模型预测问题，除了使用kaggle notes以外，可以在code，pycharm等工具中导出开源数据库，在自己建立模型预测

问题：当pip install kagglehub,导入kagglehub时，kagglehub导入失败

解决办法：
1.打开终端命令窗口（cmd），python --version,查看是否有第二个python源，show python可查看python路径
2查看终端环境路径，目前我使用的虚拟环境 <img width="1011" height="316" alt="image" src="https://github.com/user-attachments/assets/c605685b-eb65-4ef1-a4e1-fd5bf160b7d7" />
3.查看当前项目环境路径
<img width="1073" height="954" alt="image" src="https://github.com/user-attachments/assets/9d6c2fe1-898c-438a-b540-2da3fea3fe80" />
4.匹配1和2是否相同即可解决

问题：当正常pip install之后显示kagglehub正常import时，但是显示import错误，诸如图<img width="1820" height="306" alt="image" src="https://github.com/user-attachments/assets/e40c83cb-86aa-4843-85a5-2db5cdcf5ebb" />

解决办法：
查看kagglehub版本，查看是哪一个落后需要更新
<img width="1266" height="76" alt="image" src="https://github.com/user-attachments/assets/7ec7162d-4178-4dae-9ca5-3300cd20f7ae" />
这里会显示，需要更新到0.3.6
执行 pip install kagglehub==0.3.6 命令，即可解决


