---
title: Contagem de Palavras
emoji: 💾
metaDescription: Este projeto Java permite ao usuário inserir um URL e uma frase, em seguida, faz uma requisição HTTP para a página indicada, analisa o conteúdo da página e conta quantas vezes a frase e cada palavra da frase aparecem no texto.
date: 2024-08-29
summary: Projeto Java que conta as ocorrências de uma frase e suas palavras em uma página web a partir de uma URL fornecida.
tags:
  - Java
---

### <pre>🖥 [Repositorio](https://github.com/Nugguet/contador_palavras)</pre>

## Descrição

Este projeto Java permite ao usuário inserir um URL e uma frase, em seguida, faz uma requisição HTTP para a página indicada, analisa o conteúdo da página e conta quantas vezes a frase e cada palavra da frase aparecem no texto.

## Demonstração

[Assista ao vídeo do projeto](https://www.youtube.com/watch?v=j4kesxWtHbQ)

[Assista ao vídeo do projeto](https://github.com/user-attachments/assets/b1620fd1-9955-4aab-a904-ace5468511a7)

## Funcionalidades

- Validação de URL fornecida pelo usuário.
- Requisição HTTP para obter o conteúdo da página web.
- Análise do conteúdo da página para encontrar e contar ocorrências da frase e das palavras contidas nela.
- Exibição dos resultados em uma caixa de diálogo gráfica.

## Tecnologias Utilizadas

- Java 8
- Maven - Gerenciamento de dependências
- Apache HttpClient - Para realizar as requisições HTTP
- Jsoup - Para parsear e manipular o conteúdo HTML
- Swing (JOptionPane) - Para criar a interface gráfica de usuário

## Como Executar

1. Clone o repositório:

    ```bash
    git clone https://github.com/Nugguet/contador_palavras.git
    cd contador_palavras
    ```

2. Compilar o projeto usando Maven:

    ```bash
    mvn clean package
    ```

3. Usar o programa:
   - Insira um URL quando solicitado.
   - Insira a frase que deseja procurar no conteúdo da página.
   - Veja o resultado das ocorrências em uma janela de diálogo.

## Docker

O projeto também pode ser executado usando Docker. Certifique-se de ter o Docker instalado e siga os passos abaixo:

1. Construir a imagem Docker:

    ```bash
    docker build -t contador_palavras .
    ```

2. Executar o contêiner Docker:

    ```bash
    docker run -it contador_palavras
    ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
