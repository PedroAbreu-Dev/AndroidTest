# Desafio Dex - Android

## :pushpin: Contexto
O objetivo deste desafio é desenvolver um aplicativo Android simples, porém, funcional, para exibir informações sobre filmes utilizando a API gratuita **The Movie DB**. O aplicativo deve permitir que o usuário:

- Visualize uma lista de filmes.
- Pesquise e filtre filmes.
- Consulte detalhes de um filme selecionado.
- Salve filmes como favoritos para consulta posterior.

## :wrench: Stack
O aplicativo deve ser desenvolvido utilizando as seguintes tecnologias: 

- **Kotlin** → Linguagem principal para o desenvolvimento Android.
- **Coroutines & Flow** → Para gerenciar chamadas assíncronas de forma eficiente.
- **Retrofit** → Para consumo e tratamento das requisições (HTTP).
- **LiveData & StateFlow** → Para observação de dados e atualização da UI.
- **Jetpack Compose & XML** → Para construção da interface de usuário.
- **Koin** → Para injeção de dependências.
- **Coil** → Para carregamento eficiente de imagens.
- **Paging 3** → Para implementação de paginação.
- **Room Database** → Para armazenamento local.

## :dart: Requisitos do Aplicativo
O aplicativo deve conter as seguintes funcionalidades:

1. **Listagem de Filmes**
- Consumir a API do The Movie DB e exibir os filmes.
- Implementar paginação para carregar mais filmes conforme o usuário rola a tela.

2. **Detalhes do Filme**
- Exibir título, sinopse, data de lançamento e imagem do filme ao selecioná-lo.

3. **Filtragem e Pesquisa**
- Permitir ao usuário pesquisar por filmes específicos.
- Implementar filtros para refinar os resultados exibidos.

## :ticket: Bônus
Implementações opcionais que agregam valor ao projeto:

- **Exibição de Estados de Carregamento** → Mostrar um indicador de loading durante a busca de dados.
- **Tratamento de Erros** → Exibir mensagens adequadas para erros de conexão, requisição inválida, etc.
- **Aprimoramento da Experiência do Usuário** → Criar uma interface intuitiva e agradável, seguindo princípios de design moderno.
- **Favoritos** → Permitir que o usuário salve filmes e armazene-os localmente utilizando **Room Database** para consulta posterior.

## :white_check_mark: Critérios de Avaliação
Os seguintes pontos serão analisados na sua implementação:

- **Boas práticas de código e arquitetura** → Estrutura bem organizada e utilização de tecnologias atuais.
- **Legibilidade e organização** → Código claro, bem estruturado e documentado.
- **Experiência do usuário** → Interface limpa, intuitiva e responsiva.
- **Gerenciamento de estados** → Implementação eficiente dos estados de loading, erro e sucesso.

## :outbox_tray: Submissão do Desafio
1. Crie um repositório no GitHub contendo o código-fonte e a documentação do projeto.
2. Realize um pull request para o repositório de avaliação.
3. Envie um e-mail ao responsável pelo desafio contendo o link do PR.

Boa sorte! :rocket:
