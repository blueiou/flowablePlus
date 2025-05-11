# flowablePlus
Spring Boot 、flowable、LLM(DeepSeek)工作流引擎+AI智能对话
AI问答模块
![image](https://github.com/user-attachments/assets/0510f89f-028a-420c-8726-427ec1aec954)

工作流模块
1、新增流程分类
![image](https://github.com/user-attachments/assets/0704d5cd-94d2-4ddd-b50b-8616df331450)

2、新建表单
演示用，弄个比较简单的样式
![image](https://github.com/user-attachments/assets/19dc6c69-d79f-4fa5-95c0-97909c3eccf2)

3、新增流程模型
选择对应的流程分类，新增流程模型
![image](https://github.com/user-attachments/assets/ab72a23d-9294-4ead-b8ad-6ffd4dca7db5)
4、新增成功后，选择【设计】，设计工作流
![image](https://github.com/user-attachments/assets/41495cca-81cf-4764-95da-6ba49f170756)
5、点击后，进入对应的设计界面，开始节点，选择对应的表单
![image](https://github.com/user-attachments/assets/79e15aee-2b78-4472-b913-fe7ca152d8bf)
6、绑定流程审批人，可根据指定人员、角色、部门、发起人来配置
![image](https://github.com/user-attachments/assets/f75b3a0b-84a4-4e1e-82bb-ed7efaeafc09)
7、执行监听器（可选）
执行监听器（Execution Listener）可以在流程执行中发生特定的事件时，执行外部Java代码或计算表达式。
事件类型：start（开始）、end（结束）
监听器类型：
    1) Java类：填写类的全路径，如：com.ruoyi.flowable.listener.ReceiptExecutionListener
    2) 表达式：使用UEL进行表达式解析。
    3) 代理表达式：监听器接口，通常为@Component的value值，如：${receiptExecutionListener}
    4) 脚本

8、部署流程
点击【部署】，流程在成功部署后，才可发起
![image](https://github.com/user-attachments/assets/90e964ff-ea70-4567-a37a-c47a215f0c64)

部署成功后，在【部署管理】页面，可看到相应的流程
![image](https://github.com/user-attachments/assets/b2e8d3c9-01c6-400f-a2b0-f627c123ba7c)

9、用户发起流程
![image](https://github.com/user-attachments/assets/224299ee-1ca3-4aa3-9310-e2aabc906a4b)

10、审批时，可选择通过、退回、转办等操作
![image](https://github.com/user-attachments/assets/cf911965-87dd-41cd-9bd4-a470946c15ef)

11、流程记录如图所示：
![image](https://github.com/user-attachments/assets/e5510e61-25e8-416f-bd10-cc038d5acc34)





