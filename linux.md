### Chave SSH

Coloque o email dentro das Aspas
```bash
ssh-keygen -t rsa -b 4096 -C ""

eval "$(ssh-agent -s)"

ssh-add 

cat ~/.ssh/id_rsa.pub

```

