<p align="center">
  <a href="https://mackaulyn.github.io/O-Patio-Cafe/">
    <img src="./img/github-header-banner.png" alt="Banner O Pátio Café" width="100%">
  </a>
</p>

# 🎲 Bingo de Ditados Populares - Recreação Cognitiva

O **Bingo de Ditados Populares** é uma aplicação desktop desenvolvida em Java para proporcionar entretenimento e estímulo cognitivo a idosos, como os residentes do Lar dos Velhinhos. O sistema substitui os números tradicionais pela primeira parte de provérbios conhecidos, incentivando os participantes a completarem as frases e exercitarem a memória de longo prazo durante a dinâmica.
🔗 **Acesse o projeto:** [Clique aqui para visualizar](https://mackaulyn.github.io/O-Patio-Cafe/)

---

## 🛠️ Tecnologias Utilizadas

Para a construção deste projeto, foram utilizadas as seguintes ferramentas:

| Categoria | Tecnologias |
| :--- | :--- |
| **Linguagem** | ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) |
| **Ferramentas** | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google-gemini&logoColor=white) |

---

## 📌 Sobre o Projeto
O software foi desenvolvido com foco em acessibilidade e utilidade social, aplicando conceitos de:
* **Interface Gráfica (GUI):** Construída com Java Swing para proporcionar botões grandes e leitura clara.
* **Lógica de Sorteio:** Algoritmo que garante a aleatoriedade sem repetição dos 30 ditados.
* **Programação Orientada a Objetos:** Organização modular entre lógica de jogo, cartelas e sorteador.
* **IA como Co-piloto:** Utilização do Google Gemini para auxiliar na estruturação do código, resolução de bugs e documentação.

## ✨ Funcionalidades do Código
Com base nos arquivos desenvolvidos, o sistema possui:
* **Sorteio Automatizado:** Exibe o número sorteado e a primeira parte do ditado correspondente na tela.
* **Gestão de Jogadores:** Permite configurar de 1 a 20 jogadores, atribuindo nomes personalizados a cada cartela.
* **Painel de Controle Visual:** Um "Cartelão" que marca em verde os ditados já sorteados e em vermelho o último sorteado.
* **Verificação em Tempo Real:** O sistema confere automaticamente as cartelas a cada rodada e interrompe o jogo ao encontrar um vencedor.

## 📂 Estrutura de Arquivos
* `JanelaPrincipal.java:` Frame principal que gerencia todos os eventos da interface e botões.
* `BingoGame.java:` Motor do jogo que contém o banco de dados dos ditados e as regras de negócio.
* `Cartela.java:` Representa a cartela individual de cada jogador e controla a marcação dos itens.
* `Sorteador.java:` Lógica responsável por embaralhar e retirar os ditados da urna virtual.

## 🚀 Como Executar
1. Clone este repositório:
   
   ```bash
   git clone https://github.com/seu-usuario/bingo-ditados.git

2. Certifique-se de ter o JDK 17 ou superior instalado.

3. Compile os arquivos:

   ```bash
   javac com/mycompany/bingogame/*.java

4. Execute a aplicação:

   ```bash
   java com.mycompany.bingogame.JanelaPrincipal

---

## 👥 Autores
Este projeto foi desenvolvido por:

* Mackaulyn Rocha - [GitHub](https://github.com/Mackaulyn)

* Matheus Santos Gomes - [GitHub](https://github.com/MatheusGomes100)

* Google Gemini (IA Co-piloto)
