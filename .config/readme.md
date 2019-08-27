## 恢复软件安装

> pacman --needed -S - < packages-repository.txt

> cat packages-AUR.txt | xargs yaourt -S --needed --noconfirm

## 清理多余软件包

> yaourt -R `pacman -Qdqt`
