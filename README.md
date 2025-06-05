# ♞ Passeio do Cavalo (Knight's Tour)

Este projeto apresenta uma solução para o desafio do Passeio do Cavalo, utilizando a técnica de **backtracking** para percorrer um tabuleiro de forma completa e sem repetições.

## 🏫 Contexto Acadêmico  
Trabalho desenvolvido como parte da disciplina de programação na **Faculdade UNA - Unidade Sete Lagoas**.

## 📌 Descrição  
Em um tabuleiro de dimensões *n x n*, o objetivo é fazer com que o cavalo do xadrez visite todas as casas **exatamente uma vez**, iniciando a partir de uma posição definida (por padrão, o canto superior esquerdo).

## 🧠 Estratégia  
A lógica se baseia no uso de **backtracking**, onde o algoritmo tenta todos os caminhos possíveis de forma recursiva, marcando cada movimento realizado. Isso permite encontrar um caminho válido (quando possível).

## 🚀 Como executar  

Copie e cole o comando abaixo diretamente no terminal para clonar o repositório, entrar na pasta e executar o script:

```bash
git clone https://github.com/AlcidesjNeto/passeiodocavalo && cd passeio_do_cavalo && python passeio_do_cavalo.py
## 🧪 Demonstração no terminal
Você verá algo semelhante a esta saída quando executar o programa com passeio_do_cavalo(5):
 1  8 13 18  3
14 19  2  7 12
 9  6 15  4 17
20 23 10 11  0
 5 16 21 24 22
## 📚 Base Teórica
O algoritmo adota a abordagem de tentativa e erro (backtracking), muito utilizada para resolver problemas de busca onde há diversas combinações possíveis de solução.
