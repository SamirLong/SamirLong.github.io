# 下载iStoreOS镜像
打开官网：https://site.istoreos.com/firmware
根据自己的机型下载镜像

<img width="2552" height="994" alt="Image" src="https://github.com/user-attachments/assets/abfac3e5-9559-4fe8-b6bd-bce27e9974a9" />

下载好的镜像放到飞牛的磁盘里面备用
# 打开ovs
打开飞牛的设置-网络设置-右上角三个点-打开ovs
# 飞牛配置虚拟机
打开飞牛应用市场下载虚拟机
打开虚拟机创建虚拟机
虚拟机名称随意可以填：istoreos
操作系统：linux
版本默认

<img width="671" height="554" alt="Image" src="https://github.com/user-attachments/assets/d34a42b9-ea38-4d8e-a804-89aa0c8d8039" />

上传刚刚下载好的镜像文件
主板类型默认：i440fx
主板固件：UEFI(根据你下载)
cup类型默认
核心根据主机配置：2核
内存也是根据配置：2G
GPU保持默认
打开开机自启动
打开剪切板

<img width="669" height="555" alt="Image" src="https://github.com/user-attachments/assets/2e466214-ab1b-4742-a89e-4da86978bf96" />

添加储存空间
保持默认
新建磁盘添加10G（根据自己需求）

<img width="669" height="556" alt="Image" src="https://github.com/user-attachments/assets/933a618f-3d0a-45f8-b217-4132e00c307a" />

添加网卡
类型选择intel E1000

<img width="666" height="556" alt="Image" src="https://github.com/user-attachments/assets/19780772-0939-4661-a8b1-98752ea41ca1" />

硬件直通跳过
# 开机安装镜像
点击开机旁边的电脑图标vnc访问
点击回车输入：quickstart
选择3 X86安装
回车默认
回车默认
回车默认安装
安装好后回车再次输入：quickstart
选择0查看IP地址

<img width="717" height="397" alt="Image" src="https://github.com/user-attachments/assets/3819c4b7-27e4-4624-b9a9-fb9059b89778" />

浏览器打开直接登录即可无需密码
打开后点击网络向导可快速设置

<img width="1323" height="574" alt="Image" src="https://github.com/user-attachments/assets/20ec8c18-494f-4f8e-a4ed-bf5a19740837" />

点击设置为旁路由
点击自动配置
点击刷新
点击自动填写
关闭提供DHCPv4服务
点击保存配置