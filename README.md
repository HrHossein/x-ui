# Enable Root in VPS
```
sudo sed -i 's/#PermitRootLogin prohibit-password/PermitRootLogin yes/' /etc/ssh/sshd_config && sudo systemctl restart ssh && sudo passwd
```
##

# x-ui
```
bash <(curl -Ls https://raw.githubusercontent.com/NidukaAkalanka/x-ui-english/master/install.sh)
```

## suggestion system

- CentOS 7+
- Ubuntu 16+
- Debian 8+
##


# V2ray For Mobile
armeabiv7a
```
https://drive.google.com/file/d/116jCPhMKEx43LZDiCZShYVldpo-Tbp1F/view?usp=share_link
```
armeabiv8a
```
https://drive.google.com/file/d/11F9TcG9yNW1cSggasCsonFoVQndES_M1/view?usp=share_link
```
X86
```
https://drive.google.com/file/d/11DZZ6ZLyE5hM-yatnWw0C55HoLLiOscg/view?usp=share_link
```
X86/X64
```
https://drive.google.com/file/d/11BuHIadwOcQ5OkrzYhQGB_MjrIvY1aOt/view?usp=share_link
```

# V2ray For Pc
```
https://drive.google.com/file/d/113tp0iMuDyaM5CYz-2ULNzwkIVGFTArh/view?usp=share_link
```



##
# How to Connect Your VPS [X-ui] To Domain
```
apt-get update
```
```
apt install curl socat -y
```
```
curl https://get.acme.sh | sh
```
```
~/.acme.sh/acme.sh --set-default-ca --server letsencrypt
```
```
~/.acme.sh/acme.sh --register-account -m  youremail@gmail.com
```
```
~/.acme.sh/acme.sh --issue -d YourDOMAIN --standalone --force

```
```
~/.acme.sh/acme.sh --installcert -d YourDOMAIN --key-file /root/private.key --fullchain-file /root/cert.crt
```



##
