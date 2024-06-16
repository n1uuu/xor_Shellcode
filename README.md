# xor_Shellcode
xor加密shellcode并转换成go语言的字符切片格式
密钥是用户主目录路径的第四个字符的 ASCII 值

用法：
xor_Shellcode.exe -h   //显示帮助命令

xor_Shellcode.exe -f 指定要加密的二进制文件 -n (可选）指定加密次数，默认值为1  -o （可选）将加密后结果保存到文件，默认直接打印到命令窗口
