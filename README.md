# Python Jogos – Aula

Repositório contendo dois pequenos jogos desenvolvidos em Python usando Pygame, como parte do curso do SENAI.

## Jogos incluídos

### 1. Acertar o Alvo

<img width="888" height="700" alt="image" src="https://github.com/user-attachments/assets/db12b6bb-21e1-479b-9433-5567e1ffb02b" />

* Arquivo: `acertealvo.py`
* Objetivo: mover o cursor (ou objeto) e “acertar” o alvo que aparece em posições aleatórias, acumulando pontos.
* Controles: usar teclado/mouse (dependendo da implementação) para atirar ou posicionar o alvo.
* Regras: quanto mais rápido acertar, maior o score; evite errar muitos tiros.

### 2. Pong

<img width="885" height="691" alt="image" src="https://github.com/user-attachments/assets/8415dd12-6ad4-4478-bb07-2d969fed02ce" />


* Arquivo: `pong.py`
* Objetivo: clássico “Pong” — dois jogadores (ou jogador vs IA) batendo a bola para frente e para trás, tentando marcar pontos no adversário.
* Controles:

  * Jogador 1: setas (↑ ↓)
  * Jogador 2 (se houver): teclas W/S (ou definir conforme código)
* Regras: primeiro a alcançar X pontos (ou tempo definido) vence; a bola aumenta velocidade com o tempo para dificultar.

## Como executar

Siga os passos abaixo para rodar os jogos em sua máquina:

### Requisitos

* Python 3.x instalado
* Pygame instalado — se ainda não estiver, execute no terminal:

  ```bash
  pip install pygame  
  ```
* Clonar este repositório ou fazer download dos arquivos `.py`.

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/GabrielBaldon/Python-jogos-aula.git  
   cd Python-jogos-aula  
   ```
2. Para rodar o jogo “Acerte o Alvo”:

   ```bash
   python acertealvo.py  
   ```
3. Para rodar o jogo “Pong”:

   ```bash
   python pong.py  
   ```
