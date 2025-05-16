# Set-the-RSA-from-Windows-to-Linux

## Step1：Win+r打开cmd窗口
![step1_打开cmd](https://github.com/user-attachments/assets/dab8e5fc-2ff0-411a-95ed-7b2a4e9cc892)

## Step2：创建RSA公钥和密钥对（ssh-keygen）
![step2_创建密钥](https://github.com/user-attachments/assets/43631607-22a6-4dc6-a6c4-677d8a176314)

PS:创建时要记住private key passphrase以便后期登录使用

## Step3：在Linux账户~/.ssh路径下创建文件authorized_keys（权限600）并将公钥id_rsa.pub的内容加到authorized_keys中

## Step4：登录Linux账号，选择“接受并保存”，输入private key passphrase即可登录
![step4_登录验证密钥](https://github.com/user-attachments/assets/1cc500dd-3af3-4c24-a031-4e364616aa11)
