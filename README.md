# 神经网络实现手写字符识别系统

1. 运用BP神经网络
2. 输入层维数 400，隐藏层神经元 15，输出层维数 10，学习率 0.1
3. 激活函数 sigmoid
4. 参数保存在 nn.json

## 运行
1. 下载图像和标签数据
   ```
   wget http://labfile.oss.aliyuncs.com/courses/593/data.csv
   wget http://labfile.oss.aliyuncs.com/courses/593/dataLabels.csv
   ```

2. 训练模型

 ```
 python neural_network_design.py
 ```
3. 创建服务器
 ```
 python -m SimpleHTTPServer 3000
 ```
4. 加载服务器
 ```
 python server.py
 ```
5. 访问
 ```
 浏览器访问 localhost:3000
 ```


