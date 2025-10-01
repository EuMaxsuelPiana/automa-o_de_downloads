# Automação de Busca e Conversão de Músicas

Este projeto são **scripts em Python com Selenium** que automatizam as buscas de músicas
com base em um tema definido pelo usuário e, em seguida, tenta convertê-las para MP3 usando um site externo de conversão online.  
Além disso, o script mantém um **histórico em CSV** das músicas já processadas, evitando repetições.

---

## Funcionalidades

- Abre o navegador automaticamente com Selenium.
- Pesquisa músicas no YouTube de acordo com um tema (ex: "músicas dos anos 80").
- Coleta **título e link** dos primeiros vídeos encontrados.
- Acessa um site de conversão e tenta baixar os vídeos em MP3.
- Mantém um **arquivo CSV (`musicas_baixadas.csv`)** com as músicas já processadas.
- Evita duplicação de músicas no histórico.

---

## 📂 Estrutura do Projeto

automa-o_de_downloads
 ┣ 📜 automacao_download.py   # Script principal
 ┣ 📜 musicas_baixadas.csv    # Arquivo gerado com os títulos e links
 ┗ 📜 README.md               # Documentação do projeto

 git clone https://github.com/EuMaxsuelPiana/automa-o_de_downloads.git
cd automa-o_de_downloads
