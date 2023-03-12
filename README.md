# OpenAi-Usage
use OpenAi API to complete some applications

1、确保节点代理正常（使用全局代理）

2、能正常访问 API 文档 https://platform.openai.com/docs，若不能访问则切换节点

3、创建OpenAi API密钥

3、测试工具 Postman 请求头 Headers 添加 API密钥 格式key：Authorization  value：Bearer空格YOUR_API_SECRET，如Bearer sk-xxxxxxxxxx
使用Get方法 调用URL https://api.openai.com/v1/models，send
![image](https://user-images.githubusercontent.com/104081545/224558331-09e424ec-2da7-4858-a03a-f4916bcaa569.png)

4、正常输出
![image](https://user-images.githubusercontent.com/104081545/224558768-c6a9c0be-88c7-4ecd-954e-818dc45fe9c2.png)
