# BandMatch

O BandMatch é uma plataforma focada em **Front-end e consumo de APIs**, desenvolvida para conectar músicos e bandas através de filtros personalizados e integração com APIs musicais. O projeto foi criado com fins educacionais para praticar tecnologias modernas de desenvolvimento web, responsividade e manipulação de dados dinâmicos. Todos os usuários, **bandas e informações presentes na plataforma são fictícios e utilizados apenas para demonstração.**

## Índice

1. [Sobre o Projeto](#sobre-o-projeto)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Como Iniciar](#como-iniciar)
4. [Estrutura de Diretórios](#estrutura-de-diretórios)
5. [Desenvolvimento](#desenvolvimento)
6. [Integração com APIs](#integração-com-apis)
7. [Desenvolvedores](#desenvolvedores)
8. [Licença](#licença)


### Funcionalidades Principais:

- **Filtros Personalizados**: Permite filtrar músicos por idade, instrumentos musicais e gêneros musicais.
- **Busca de Cifras**: Integração com APIs musicais para pesquisa de cifras, músicas e artistas.
- **Perfis de Usuários**: Cada músico possui um perfil personalizado com descrição, gostos musicais, instrumentos e portfólio.
- **Sistema de Bandas**: Exibição de bandas fictícias procurando novos integrantes.
- **Portfólio Musical**: Visualização de músicas favoritas e repertórios dos usuários.


## Tecnologias Utilizadas
- **Next.js**: Framework React utilizado para construção da interface e renderização das páginas.
- **JSON Server**: Utilizado para simular uma API REST e armazenar dados fictícios durante o desenvolvimento.
- **Bootstrap**: Framework CSS utilizado para responsividade e estilização da interface.

## Como Iniciar

### Pré-requisitos

Antes de começar, é necessário ter as seguintes ferramentas instaladas em sua máquina:

- **Node.js** (versão >= 14.x)


### 1. Clonar o repositório

```bash
git clone https://github.com/ArthurBenedett/BandMatch
```

### 2. Instalar dependências

Execute o comando abaixo para instalar as dependências do projeto:

```bash
cd BandMatch
npm install
cd API_CifraClub
npm install
cd ..
```

### 3. Configuração do JSON Server
O projeto utiliza o **JSON Server** para simular uma API REST com dados fictícios.
Antes de iniciar o projeto, execute o comando abaixo em um terminal separado para iniciar o servidor na porta **3333**:
```bash
json-server --watch server.json --port 3333
```
### 4. Inicializando a API do CifraClub

Para iniciar a API responsável pelo consumo de cifras e informações musicais, abra um novo terminal e entre na pasta `API_CifraClub`:

```bash
cd API_CifraClub
```



Agora execute a API com o comando:

```bash
npm run dev
```

Se tudo estiver funcionando corretamente, o terminal retornará:

```bash
Servidor rodando em http://localhost:3000
Teste a API em: http://localhost:3000/api/cifra?artist=legiao-urbana&song=tempo-perdido
```
### 5. Inicializando a API do CifraClub

Para iniciar a API responsável pelo consumo de cifras e informações musicais, abra um novo terminal e entre na pasta `API_CifraClub`:

```bash
cd API_CifraClub
```



Agora execute a API com o comando:

```bash
npm run dev
```

Se tudo estiver funcionando corretamente, o terminal retornará:

```bash
Servidor rodando em http://localhost:3000
Teste a API em: http://localhost:3000/api/cifra?artist=legiao-urbana&song=tempo-perdido
```


### 6. Inicie o projeto Front-end

Volte para a raiz do projeto e execute:

```bash
npm run dev
```

O sistema estará disponível em:

```bash
http://localhost:3001
```
---

## Estrutura de Diretórios

A estrutura de diretórios do projeto segue a organização padrão do Next.js, com separação entre páginas, componentes, APIs e serviços utilizados na aplicação:

```bash
/public                    # Arquivos públicos estáticos
/src                       # Código fonte principal
  /app                     # Páginas do frontend (Next.js)
  /components              # Componentes reutilizáveis da UI
  /styles                  # Arquivos de estilização
  /utils                   # Funções utilitárias
  /services                # Serviços e consumo de APIs
/API_CifraClub             # API responsável pela busca de cifras
/.next                     # Build gerada automaticamente pelo Next.js
/node_modules              # Dependências do projeto
/server.json               # Banco de dados fictício utilizado pelo JSON Server
```

## Desenvolvimento

Este projeto foi desenvolvido utilizando tecnologias modernas de desenvolvimento web, com foco em **Front-end**, consumo de APIs e construção de interfaces responsivas. A aplicação utiliza **Next.js** e **React.js** para criação das páginas e componentes, além de **Bootstrap** e CSS customizado para estilização da interface.

Os dados da aplicação são consumidos através de APIs externas e de uma API fictícia criada com **JSON Server**, permitindo simular requisições e manipulação dinâmica de informações durante o desenvolvimento.

Além disso, o projeto conta com uma API própria para busca de cifras musicais, localizada na pasta `API_CifraClub`, responsável pela integração com conteúdos relacionados ao universo musical.

---


## Desenvolvedores

- [Giovanni Benedetti](https://github.com/GiovanniBBenedetti)
- [Davi de Souza Leocadio Ramos](https://github.com/DaviLeocadio)
- Arthur Buscarino Benedetti

---


## Licença

Este projeto foi desenvolvido para fins educacionais 