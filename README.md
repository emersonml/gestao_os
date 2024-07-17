sudo chmod 777 app/updates/; sudo chmod 757 app/application/;
chmod 777 app/updates/; chmod 757 app/application/;


# no redirecionamento no NPM o SCHEME tem que ser HTTP e nao https 
# hostnamer não pode contar espaço no inicio e fim


    # QUANDO APARECER O AVISO:
    Warning: require_once(/var/www/html/application/vendor/autoload.php): Failed to open stream: No such file or directory in /var/www/html/index.php on line 57

    Então esperar um pouco ou aplicar o comando chmod ou verificar o compose php