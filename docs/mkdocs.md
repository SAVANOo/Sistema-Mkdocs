### MkDocs

# O que é o MkDocs?

[**MkDocs**](https://www.mkdocs.org/) é uma ferramenta para documentação estática que converte arquivos Markdown (.md) em um site estático com as informações inseridas. Ele é fácil de configurar e utilizar, oferecendo uma maneira rápida e eficiente de criar fichas técnicas para seus projetos e facilitando todo o processo de documentação das empresas.

## Principais Funcionalidades do MkDocs

- Conversão de arquivos Markdown para Sites
- Navegação aprimorada feita em forma de arvore
- Ferramenta de busca fácil
- Inúmeros temas que podem ser baixados pela internet 

### Instalação do Python

1. Acesse o site da [Linguagem de Programação Python](https://www.python.org/) que é a linguagem que roda o mkdocs e baixe a versão mais recente

2. Instale e certifique-se durante a instalação de que a opção `Add Python to PATH` esteja marcado para setar a variável de ambiente do python correntamente


### Instalação do MkDocs
No seu terminal:
1. Baixe o MkDocs com o pip (gerenciador de pacotes do python) : `pip install mkdocs`

2. Navegue até a pasta que deseje criar o projeto com MkDocs (cd 'nome da pasta')

3. Crie um projeto MkDocs e entre para dentro da pasta

        mkdocs new 'nome-do-projeto' 
        cd 'nome-do-projeto'

4. Faça o build do seu projeto MkDocs

        mkdocs build

5. Rode o servidor MkDocs

        mkdocs serve


### Entendendo sobre criação de documentação com o MkDocs

Primeiramente deve-se entender que a build do mkdocs converte arquivos .md em arquivos html e possui um tema padrão que pode ser alterado futuramente.

Com isso em mente devemos colocar todos os nossos arquivos de markdown dentro do diretório docs

Devemos formatar os arquivos seguindo as convenções que possuem, [Documentação de Ajuda com Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

### Configuração de Temas

MkDocs possui várias possibilidades de temas e assim possui várias formas de instalação também, segue o tutorial de como instalar o tema utilizado nesse projeto : 

1. Baixe o tema com o pip 
    
        pip install mkdocs-kpn

2. Atualize o arquivo mkdocs.yml na raiz do seu projeto configurando corretamente o tema (Muito cuidado com a identação do seu arquivo)

        theme:
          name: 'kpn'

