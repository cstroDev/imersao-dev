# 🚀 Base de Conhecimento - Imersão Dev

Este é um projeto de uma página web simples que funciona como uma "Base de Conhecimento" para tecnologias de programação. Ele foi desenvolvido como parte dos desafios da **Imersão Dev da Alura**.

A aplicação exibe uma coleção de cards, cada um representando uma linguagem, framework ou ferramenta de desenvolvimento. O usuário pode visualizar todas as tecnologias ou buscar por um termo específico para filtrar os resultados.


## ✨ Funcionalidades

- **Listagem de Tecnologias:** Exibe dinamicamente as tecnologias a partir de um arquivo `data.json`.
- **Busca em Tempo Real:** Filtra as tecnologias exibidas conforme o usuário digita no campo de busca.
- **Cards Interativos:** Cada tecnologia é apresentada em um card com seu nome, ano de criação, descrição e um link para a documentação oficial.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web fundamentais:

- **HTML5:** Para a estrutura da página.
- **CSS3:** Para a estilização e layout dos componentes (no arquivo `style.css`).
- **JavaScript (ES6+):** Para a lógica de busca, manipulação do DOM e carregamento dos dados.
- **JSON:** Como fonte de dados para as tecnologias.

## 📂 Estrutura do Projeto

```
./
├── 📄 index.html       # Arquivo principal com a estrutura da página
├── 🎨 style.css        # Folha de estilos para a aplicação
├── ⚙️ script.js        # Lógica de busca e renderização dos cards
└── 📦 data.json        # Banco de dados com as informações das tecnologias
```

## 🏃 Como Executar o Projeto

Como o projeto utiliza a API `fetch` do JavaScript para carregar o arquivo `data.json` localmente, abri-lo diretamente no navegador (`file://...`) pode causar um erro de CORS (Cross-Origin Resource Sharing).

A maneira recomendada de executá-lo é através de um servidor local.

### Usando a extensão Live Server (VS Code)

1.  Instale a extensão Live Server no Visual Studio Code.
2.  Abra a pasta do projeto no VS Code.
3.  Clique com o botão direito no arquivo `index.html`.
4.  Selecione a opção "Open with Live Server".

### Usando Python

Se você tiver Python instalado, pode iniciar um servidor simples:

1.  Abra o terminal na pasta raiz do projeto.
2.  Execute o comando:
    ```bash
    # Para Python 3
    python -m http.server
    ```
3.  Abra seu navegador e acesse `http://localhost:8000`.

## 👤 Autor

Este projeto foi desenvolvido por **cstroDev**.

- **GitHub:** @cstroDev

---
*Projeto criado durante a Imersão Dev da Alura.*