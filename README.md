# squid-sarg-configuration
Configurações de um arquivo de servidor Squid com Sarg
# INSTALANDO O SARG
apt-get install sarg

# VERIFICAR AS LINHAS
output_dir /var/www/html/squid-reports
access_log /var/log/squid/access.log

# PARA SABER MAIS SOBRE AS CONFIGUAÇÕES DO SARG, OS ARQUIVOS ESTÃO NA PASTA DO SARG
# MAS OS ARQUIVOS MAIS USADOS SÃO O sarg.conf E O sarg-reports.conf

# SE NECESSÁRIO, CRIAR UMA PASTA EM: /var/www/squid-reports
