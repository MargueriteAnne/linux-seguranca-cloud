# Permissões aplicadas
## Ambiente utilizado
Linux (WSL/Ubuntu no computador local)
## Utilizador e grupos
whoami: anne
id: uid=1000(anne) gid=1000(anne) groups=1000(anne),4(adm),20(dialout),
24(cdrom),25(floppy),27(sudo),29(audio),30(dip),44(video),46(plugdev),
100(users),107(netdev)
groups: anne adm dialout cdrom floppy sudo audio dip video plugdev users 
netdev
## Ficheiros criados
- publico.txt:
- restrito.txt:
- script.sh:
## Permissões aplicadas
| Ficheiro | Permissão | Justificação |
|---|---:|---|
| publico.txt | 644 |Permite leitura para todos, escrita apenas pelo 
proprietário|
| restrito.txt | 640 | Permite acesso apenas ao proprietário e grupo |
| script.sh | u+x |Permite execução apenas pelo utilizador, seguindo o 
princípio do menor privilégio |
## Relação com o princípio do menor privilégio
As permissões foram definidas para garantir que cada ficheiro tenha apenas
 o nível de acesso necessário. Isso reduz riscos de alteração ou acesso não
 autorizado, garantindo mais segurança no sistema.
