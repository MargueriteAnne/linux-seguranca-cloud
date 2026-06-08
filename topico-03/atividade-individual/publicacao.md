# Publicação do serviço web
## Nível escolhido
Nível 1 - Essencial
## Rota escolhida
Nginx / Apache
## Página criada
index.html
## Local de publicação
/var/www/html/
## Comandos principais utilizados
mkdir -p atividade-individual/site
mkdir -p atividade-individual/evidencias
touch comandos.txt publicacao.md validacao.md README.md
nano index.html
systemctl status nginx
sudo cp index.html /var/www/html/
curl http://localhost
## Resultado obtido
Foi criada uma página HTML simples e publicada com sucesso através do 
servidor web Nginx. A página ficou acessível através do endereço 
http://localhost e respondeu corretamente aos testes realizados com o
navegador e com o comando curl.
## Limitações encontradas
Não foram encontradas limitações significativas durante a realização da 
atividade.
