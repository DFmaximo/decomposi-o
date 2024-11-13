# Decomposição de Peça de Carne para 100kg

Este projeto permite calcular a decomposição de uma peça de carne, levando em consideração o peso da peça principal e os cortes que você deseja fazer. O usuário pode inserir até 20 cortes, informando o nome e o peso de cada um. O sistema irá calcular os percentuais de cada corte, considerando uma peça de 100kg. 

Este projeto usa HTML, CSS e JavaScript para proporcionar uma interface simples e interativa. Ele também oferece a possibilidade de gerar um relatório em formato PDF com os resultados.

## Funcionalidades

- **Entrada de dados**: O usuário insere o peso da peça principal e o nome e peso de até 20 cortes.
- **Cálculo de decomposição**: Após inserir os dados, o sistema calcula automaticamente a porcentagem de cada corte, com base em uma peça de 100kg.
- **Geração de PDF**: Ao clicar no botão "Gerar PDF", o usuário pode baixar um arquivo PDF contendo os resultados.

## Requisitos

- Um navegador moderno (Chrome, Firefox, Safari, Edge).
- Internet para carregar a biblioteca `jsPDF` usada para gerar o PDF.

## Como Usar

### Passo 1: Inserir o peso da peça principal

No campo "Peso da peça principal", insira o peso da peça de carne que você deseja decompor.

### Passo 2: Inserir os cortes

Clique no botão **Adicionar Corte** para adicionar os campos necessários para inserir o nome e o peso de até 20 cortes. Você pode adicionar e remover campos conforme necessário.

### Passo 3: Calcular a decomposição

Após preencher os dados de todos os cortes, clique em **Calcular Decomposição para 100kg**. O sistema calculará automaticamente o peso de cada corte para uma peça de 100kg e exibirá os resultados em uma tabela.

### Passo 4: Gerar o PDF

Se desejar, clique no botão **Gerar PDF** para gerar um relatório em PDF contendo a decomposição calculada. O PDF será baixado automaticamente.

## Estrutura do Código

### HTML

- A estrutura HTML é responsável por definir a estrutura básica do formulário, onde o usuário pode inserir os dados e visualizar os resultados.
- Possui um formulário que permite inserir o peso da peça principal e até 20 cortes, bem como exibe os resultados em uma tabela.

### CSS

- O estilo foi feito para proporcionar uma experiência de usuário agradável e responsiva. 
- A interface ajusta automaticamente o layout para telas de diferentes tamanhos, utilizando `flexbox` e `media queries`.
- A aparência é moderna, com cores suaves e botões destacados.

### JavaScript

- O JavaScript é responsável pela interação do usuário com o formulário.
  - Ele valida os dados inseridos e calcula a conversão para 100kg.
  - A função `generatePDF` usa a biblioteca `jsPDF` para criar um PDF com os resultados da decomposição.

### Biblioteca Externa

- **jsPDF**: A biblioteca `jsPDF` é utilizada para gerar o PDF. Ela é carregada de uma CDN no início do código.


