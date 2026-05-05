# Top 5 Party: Uma Aplicação de Engenharia de Dados

**Autor:** Gustavo de Carvalho, Lauro Lobo e Felipe Mendonça

Este repositório contém a documentação e os arquivos referentes ao artigo científico do Projeto Integrador do **Top 5 Party**. O projeto alinha o desenvolvimento de um jogo interativo com as disciplinas de Inteligência Artificial, Banco de Dados, IoT e BI.

## 📖 Sobre o Projeto / Abstract

O presente projeto integrador propõe o desenvolvimento do **Top 5 Party**, uma aplicação interativa multiplayer local focada na coleta e gerenciamento de Conteúdo Gerado pelo Usuário (UGC). 

O sistema atua com uma arquitetura de rede em tempo real (Node.js e WebSockets), reduzindo o atrito de usabilidade ao transformar os smartphones dos usuários em interfaces de inserção de dados (controles), enquanto um host central gerencia o estado global. Além de aplicar mecânicas de *game design* assimétrico e teoria de jogos (vazas/blefe), o diferencial técnico do projeto reside na sua camada de persistência: todas as preferências subjetivas inseridas pelos usuários e os fluxos das partidas são estruturados e armazenados em um banco de dados relacional (PostgreSQL). 

Dessa forma, o projeto não apenas entrega uma experiência de entretenimento viável e escalável, mas também consolida um repositório de dados comportamentais locais, abrindo caminho para futuras aplicações analíticas e modelagem de dados que dialogam diretamente com as disciplinas de persistência e análise de software do curso.

---

## 🔑 Palavras-chave / Keywords

* Conteúdo Gerado pelo Usuário / *User-Generated Content (UGC)*
* Arquitetura Multiplayer Assimétrica / *Asymmetric Multiplayer Architecture*
* Aplicações Web em Tempo Real / *Real-Time Web Applications*
* Persistência de Dados Comportamentais / *Behavioral Data Persistence*
* Mecânicas de Vazas (Truco) / *Trick-taking Mechanics*

---

## 🛠️ Tecnologias e Arquitetura

O projeto atua como uma ferramenta de persistência de dados comportamentais utilizando a seguinte infraestrutura:
* **Backend:** Node.js com WebSockets para comunicação de rede em tempo real e baixa latência.
* **Frontend:** Telas web operando sob arquitetura multiplayer assimétrica, convertendo os celulares em controles via QR Code (com zero atrito de instalação).
* **Banco de Dados:** PostgreSQL local para persistência e estruturação massiva das preferências dos usuários e *logs* de partida.

---

## 📚 Revisão Bibliográfica Principal

A fundamentação teórica que baseia a construção desta arquitetura e sua relevância acadêmica/industrial inclui:

* DUAN, Haihan et al. User-Generated Content and Editors in Video Games: Survey and Vision. **IEEE Transactions on Games**, 2022.
* HOLLY, Michael; RESCH, Sebastian; PIRKER, Johanna. An Asymmetric Multiplayer Learning Environment for Room-Scale Virtual Reality and a Handheld Device. **Graz University of Technology**, 2023.
* MADURO, M. R. et al. Educação corporativa na Indústria 4.0: desafios, estratégias e competências. **Revista Cadernos Cajuína**, v. 11, n. 2, 2026.
* POLIAKOVA, Emma et al. SmartControllerJS: A JavaScript library to turn smartphones into controllers for web-based interactive experiments. **arXiv**, 2022.
* REIS, A. C. B. et al. Prospects for using gamification in Industry 4.0. **Production**, v. 30, 2020.
* SILVA, W. D. Gamificação na Engenharia de Produção: aplicação das ferramentas do lean manufacturing em um laboratório de ensino e experimentação. **Revista Produção Online**, v. 21, n. 2, 2021.
