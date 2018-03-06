# Website Franzininho

https://franzininho.github.io/

## Pre-requisitos

 - Jekyll

## Gerenciamento e Contribuição com o repositório

 Faça o fork do projeto em sua conta local.
 Crie as features e alterações no projeto e envie para o repositório central usando o recurso de Pull-Request
 No gerenciamento dos commits, é recomendado que se use o paradígma do Git-Flow.

 Se você quer colaborar com a construção desse projeto, entre em contato.

## Instalação local

Você precisará instalar o Jekyll na sua máquina local. Siga o passo a passo de instalação do Jekyll descrito no site.

## Estrutura de Projeto

```
 _includes/	# trechos de código recorrentes utilizados no projeto
 _layouts/	# templates princpais
 _posts/	# posts da área de blog (são arquivos formato markdown que utilizam como base o template _includes/post.html)
 _sass/		# arquivos sass
 _site/		# apenas visível na compilação do projeto
 assets/	# arquivos acessórios do projeto (imagens, scripts, css, fonts)
 404.html       # template do arquivo 404
 _config.yml    # configurações jekyll do projeto e parâmetros globais
 Gemfile        # Lista de gems
 Gemfile.lock
 index.md       # index do projeto base, utiliza o template _includes/default.html
 README.md      # este arquivo
```

