# Instalar Chave SSH no Github

---

Comandos: 

$ ssh-keygen -t ed25519 -C **email**

$ → enter →$ senha → $senha novamente

$ cd /c/Users/**user**/.ssh/

$ ls

$ cat id_ed25519.pub 

copia a chave pública e cola no github

$ pwd

$ eval $(ssh-agent -s)

$ ssh-add id_ed25519

Ir para pasta que deseja 

$ git clone [git@github.com](mailto:git@github.com):cgaldino/myhome.git