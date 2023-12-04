# hust_cse_crypto

------

这是华中科技大学密码学课程设计2023年秋的git仓库，一共9题，分别对应9个md

需要安装openssl，步骤如下：

```bash
sudo apt update
sudo apt install openssl libssl-dev
```

编译运行，注意链接了ssl：

```bash
g++ -o your_cpp_name your_cpp_name.cpp -lssl -lcrypto
chmod 777 your_cpp_name
./your_cpp_name
```

