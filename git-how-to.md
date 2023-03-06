1) Чтобы создать ssh ключ, необходимо ввести команду:
ssh-keygen -t ed25519 -C "vasilev.ak@phystech.edu"
2) Чтобы добавить ключ в аккаунт на GitHub, необходимо ввести команду:
ssh-add .ssh/ip
3) Чтобы склонировать репозиторий, необходимо ввести команду:
git clone git@github.com:AndreyVasilev23/Vasilev.git
