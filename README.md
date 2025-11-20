待2025/11/23更新最新版本上传

说明:有些功能不同项目可能需要单独适配一下，文档中也进行说明了，需要配置的都封装成了配置文件或者文件直接使用方式等方式；不难，但如果感觉麻烦，可以联系我，我将你适配好

安装之前请先退出adb,执行一下adb kill-server

后续版本记录，采用日期形式，此次版本为V25.10.1

卸载点击安装目录下面unins000.exe即可:

<img width="490" height="382" alt="image" src="https://github.com/user-attachments/assets/f707f193-413b-4d3b-93c4-ec95ac319e2a" />


后续更新不需要点击卸载，直接重新点击安装，安装到原来路径，会自动更新内容

--在线更新由于网络限制，需要指定服务器才行，所以这里条件限制无法做，暂时选择如此更新

1.使用方式
**

安装好以后，桌面就有图标

2.常用工具
2.1 MTK导出日志功能

2.4 ADB指令集合

[图片]

2.4.1 高通PMIC查看指导:

[图片]

2.5 Fastboot指令集合

[图片]

2.6 dump功能

<img width="668" height="208" alt="image" src="https://github.com/user-attachments/assets/47b9bbf1-2a1a-47ac-9714-e1d7fa6e9897" />

3.高通DUMP功能
3.1 高通APDUMP功能

<img width="939" height="539" alt="image" src="https://github.com/user-attachments/assets/cde67552-ae2d-4818-8d7c-7bf3bd335f57" />

不同平台配置方式:--请自行适配，如果不会，可以沟通(关于中有联系方式)

<img width="1273" height="728" alt="image" src="https://github.com/user-attachments/assets/38c15488-5256-407d-a827-fde63f14349d" />

3.2 高通ADSP DUMP功能

T32工具需要自己安装一下(此工具涉及版权，这里不提供)
<img width="980" height="399" alt="image" src="https://github.com/user-attachments/assets/5939dd0f-0322-43f4-a13b-a3b7c2be9bea" />

3.3 高通RPM解析

<img width="990" height="306" alt="image" src="https://github.com/user-attachments/assets/06f2b5c3-8a1a-43bb-ae4e-5b15189b0a19" />

3.4 TZ解析

<img width="990" height="306" alt="image" src="https://github.com/user-attachments/assets/05a77611-82ad-4594-8e2d-63c705b921d1" />


3.5 高通9008解析 -- 此功能可能存在点问题，如果有问题，请反馈

4.右键功能说明
4.1 日志合并功能

4.1.1 配置说明:--根据需求不同，请自行配置及，即可

<img width="1571" height="278" alt="image" src="https://github.com/user-attachments/assets/588c000e-4946-4a64-b260-89f5bd509930" />


4.1.2 导fulldump日志

<img width="1055" height="474" alt="image" src="https://github.com/user-attachments/assets/ec05a24c-941c-47e7-92b6-24f01ca579c4" />


4.1.3 右键选中文件合并日志:

<img width="1565" height="340" alt="image" src="https://github.com/user-attachments/assets/54c06c58-a878-4e2a-ae58-5dbecd458a82" />
右键选中空白合并文件里面所有日志： 
<img width="990" height="486" alt="image" src="https://github.com/user-attachments/assets/5c522aeb-9518-4744-b514-4064385d968d" />

支持压缩包解压合并以及多个文件之间合并(如果发现有bug，请及时告知)

4.2 Trace以及火焰图获取

<img width="550" height="495" alt="image" src="https://github.com/user-attachments/assets/3b947cc1-6e2f-468d-a1e9-ed25b8d524a6" />
<img width="1657" height="884" alt="image" src="https://github.com/user-attachments/assets/541f0e34-f108-4570-a07e-9fe13ae3cee6" />

4.3 Bugreport解析:

<img width="1010" height="261" alt="image" src="https://github.com/user-attachments/assets/82a7e1b1-2e05-40a2-ac75-056498198295" />

4.4 新增文件拆分

<img width="950" height="718" alt="image" src="https://github.com/user-attachments/assets/6454cd93-60f6-434c-8107-3df8bec43202" />
<img width="950" height="718" alt="image" src="https://github.com/user-attachments/assets/493a13dd-c6a9-4cc7-abc2-f84a7a5fc84f" />


4.5 新增右键获取日志，清理日志，获取MTK DUMP功能

<img width="807" height="187" alt="image" src="https://github.com/user-attachments/assets/826035af-524d-42e8-83ba-48196c07797e" />


请找到安装路径下面如下文件，按需要进行单独配置即可:

<img width="1398" height="452" alt="image" src="https://github.com/user-attachments/assets/14e2e651-93c1-4bf8-989e-a5fcac63a35f" />


5.常用维测功能：

5.1 新增reboot压测测试

<img width="913" height="341" alt="image" src="https://github.com/user-attachments/assets/810866dc-e710-47d6-9249-d86a382f5027" />


6.BSP模块自动分析 -- 此项功能在不断优化中，如果有问题，欢迎联系

7.模块化动态图形绘制---此功能待后续开发添加

8.联系方式：承诺后续，无论在哪里，有啥好想法可以联系，更新，免费无偿奉献

9.全部由个人创造，无病毒，使用无违规，后续软件功能会不断优化，持续用此文档更新，欢迎提建议，创新不易，感觉还行，请点赞
