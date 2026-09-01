# 🎮 2048 em Python com Pygame

Uma implementação do clássico jogo **2048**, desenvolvida em **Python** utilizando a biblioteca **Pygame**.

O objetivo é combinar os números iguais até chegar ao bloco **2048**.

## 🕹️ Sobre o jogo

O jogo possui uma grade de **4×4** e começa com alguns blocos numerados.

A cada movimento:

* Os blocos podem ser movimentados para cima, baixo, esquerda ou direita.
* Blocos com o mesmo valor podem se combinar.
* Ao combinar dois blocos iguais, seus valores são somados.
* Um novo bloco é adicionado ao tabuleiro após cada movimento válido.
* O objetivo é alcançar o bloco **2048**.

## ⌨️ Controles

| Tecla | Ação                |
| ----- | ------------------- |
| `↑`   | Mover para cima     |
| `↓`   | Mover para baixo    |
| `←`   | Mover para esquerda |
| `→`   | Mover para direita  |

## 💻 Tecnologias utilizadas

* **Python**
* **Pygame**

## 🚀 Como executar o projeto

### Pré-requisitos

É necessário ter o Python instalado no computador.

Clone o repositório:

```bash
git clone https://github.com/DouglasTardioli/python-pygame-2048.git
```

Entre na pasta:

```bash
cd python-pygame-2048
```

Instale o Pygame:

```bash
pip install pygame
```

Execute o jogo:

```bash
python main.py
```

## 🪟 Executável para Windows

O projeto também possui uma versão compilada em **`.exe`**, permitindo executar o jogo no Windows sem precisar instalar Python ou Pygame.

### Executar

Baixe o arquivo:

**`MeuJogo.exe`**

Depois basta abrir o executável para iniciar o jogo.

> O executável foi criado utilizando **PyInstaller**.

### Observação

O executável foi gerado para **Windows**. O funcionamento pode variar dependendo da versão e arquitetura do sistema operacional.

## 📁 Estrutura do projeto

```text
python-pygame-2048/
│
├── main.py
├── MeuJogo.exe
├── README.md
└── LICENSE
```

## 📸 Projeto

Este projeto foi desenvolvido como prática de programação utilizando Python e Pygame, com foco na criação de um jogo completo e na geração de um executável para Windows.

## 📄 Licença

Este projeto está disponível sob a licença **MIT**.

---

Desenvolvido por **Douglas Tardioli**.

🔗 [GitHub](https://github.com/DouglasTardioli)
