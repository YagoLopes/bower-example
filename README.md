## Bower

- O [Bower](https://bower.io/) é um gerenciador de pacotes estilo npm, porem mais voltado para pacotes do frontend

### Comando básicos

- `bower init` Inicia o bower
- `bower install` Instala um novo pacote
- `bower install --save` Instala um pacote e anota no packege.json
- `bower install --save-dev` Instala um pacote como dependencia de desenvolvimento
- `bower uninstall` Remove pacotes
- `bower update` Atualiza os pacotes
- `bower search` Pesquisa por pacotes com o nome digitado
- `bower list` Lista os pacotes instalados

### Versionamento de pacotes

- `1.2.16` (apenas 1.2.16)
- `~1.2.16` (aceito a 1.2.28, não aceito a 1.4.5) **_apenas o patch_**
- `^1.2.16` (aceito a 1.4.5, não aceito a 2.0.0) **_patch e minor_**
- `>1.2.16` (aceito qualquer versão maior)
- `>=1.2.16` (aceito qualquer versão maior ou igual) **_caso 1.2.16 seja uma versão ele fica com ela_**
- `<1.2.16` (aceito qualquer versão menor) **_ele vai para a primeira menor que essa_**
- `<=1.2.16` (aceito qualquer versão menor ou igual) **_caso 1.2.16 seja uma versão ele fica com ela_**
- `latest` (a ultima versão disponível)
