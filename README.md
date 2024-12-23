# Crypto Tool

## 项目简介

Crypto Tool 是一个简单的文件加密和解密工具，使用异或算法对输入文件进行加密或解密。该工具可以处理二进制文件，并能够通过提供的密钥实现安全的文件数据保护。

## 功能

- 文件加密：将指定的输入文件加密，并保存为输出文件。
- 文件解密：使用相同的异或算法，重新将加密文件解密为原始文件。
- 简单易用：通过命令行界面使用，参数清晰，操作简单。

## 使用说明

### 编译

在使用 Crypto Tool 之前，您需要先编译源代码。可以在终端中执行以下命令：

```bash
gcc -o crypto crypto.c


### 运行
运行工具的基本命令格式如下：
./crypto <输入文件> <输出文件> <密钥>
<输入文件>：要加密或解密的源文件。
<输出文件>：存放加密或解密结果的目标文件。
<密钥>：用于加密或解密的密钥（这里是一个整数）。
### 示例
加密文件：

./crypto input.txt encrypted_output.txt 123
解密文件：

./crypto encrypted_output.txt decrypted_output.txt 123
在上面的示例中，input.txt 是待加密的文件，encrypted_output.txt 是加密后的输出文件，123 是用于加密的密钥。

## 作者信息

- 姓名: xxmllj83
- 邮箱: 3049616592@qq.com
- GitHub: [https://github.com/xxmllj83](https://github.com/xxmllj83)
- 了解更多信息请联系我。

