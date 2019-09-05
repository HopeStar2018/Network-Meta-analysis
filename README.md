# Network-Meta-analysis
HR 网络meta分析代码汇总
>声明：本资料仅代表个人观点，旨在促进学术信息的沟通和交流。
## Step 1 随机效应模型 & 固定效应模型
  这一步上传了两种方法，Method I & Method II，均可以通过R实现HR网络meta分析，Method II 相对auto 。分析数据没有上传，主要是通过 HR 和 95%CI 进行合并分析，请各位自行模拟数据。 
  anno文件为治疗方法的注释文件，格式为两列，第一列为干预措施的代号，第二列为干预措施的名称。



## Step2_network_plot
  参考丁香园 网络meta分析的套路，对代码进行了重新编程，改进了bug，参考：http://ebm.dxy.cn/bbs/topic/25146632
  
  
  
## Step3_inconsistency
  不一致性检验，由于R包的迭代升级，本人对自带R包进行了重新编程，避免了bug，如果您使用的R版本比较老不推荐使用。
  后面的步骤相对无脑，有一定R语言基础的可以自行学习。
