# 🕹️ Arkplains: Crônicas de Arkadia

RPG 2D com visual pixel art, combate por turnos e foco em exploração top-down. O jogo está sendo desenvolvido com C# na Godot Engine, com foco em plataforma PC e exportação futura para mobile.

## 🎯 Objetivo

Este projeto está em desenvolvimento com o intuito de aprender e aplicar:

- Organização de projeto em Godot.
- Estruturação de mundo com mapas e exploração.
- Criação de assets visuais (sprites, tilesets, HUD).
- Exportação futura para plataformas desktop e mobile.

---


## 🛠️ Ficha Técnica

| Item                        | Detalhes                                     |
|-----------------------------|----------------------------------------------|
| **Nome do Projeto**         | *Arkplains: Crônicas de Arkadia* (provisório)|
| **Gênero**                  | RPG 2D, Combate em Turnos                    |
| **Estilo de Visual**        | Pixel Art / Estilo retrô, top-down           |
| **Plataforma-alvo**         | PC (Windows/Linux), possível exportação mobile |
| **Motor de Jogo**           | Godot Engine 4.4.1                           |
| **Linguagem de Programação**| C# (.NET Core)                               |

## ⚙️ Mecânicas Básicas

- **Exploração top-down**: mundo semiaberto com NPCs e cenários.
- **Combate por turnos**: sistema de batalha com inimigos visuais.
- **Sistema de diálogo simples**: interação com menus e personagens.
- **Sistema de moeda e inventário**: desbloqueados após o tutorial.

## 🧰 Ferramentas Utilizadas

- [![Figma](https://img.shields.io/badge/Figma-Design-red?logo=figma&logoColor=white)](https://www.figma.com/)  
  **Função:** Criação de interfaces e protótipos  
  **Detalhe:** Design de layouts e esboços interativos

- [![Libresprite](https://img.shields.io/badge/Libresprite-Pixel%20Art-blue)](https://libresprite.github.io)  
  **Função:** Produção de sprites e tilesets.                    
  **Detalhe:** Criação de gráficos em pixel art.

- [![Tiled](https://img.shields.io/badge/Tiled-Editor%20de%20Mapas-blue?logo=mapbox&logoColor=white)](https://www.mapeditor.org)  
  **Função:** Criação de mapas abertos e interiores.              
  **Detalhe:** Ideal para layouts contínuos e detalhados.

- [![LDtk](https://img.shields.io/badge/LDtk-Mapas%20de%20salas-orange?logo=ldtk&logoColor=black)](https://ldtk.io)  
  **Função:** Criação de mapas de masmorras e cavernas.               
  **Detalhe:** Organização modular de mapas segmentados.

- [![Godot](https://img.shields.io/badge/Godot%20Engine-4.4.1-478cbf?logo=godotengine&logoColor=white)](https://godotengine.org)  
  **Função:** Motor de jogo e lógica.                                
  **Detalhe:** Implementação de gameplay, colisão e menus.

## 📦 Estrutura Inicial do Projeto

```bash
res://
├── assets/ # Sprites, tilesets e imagens
├── maps/ # Cenas criadas no Tiled ou LDtk
├── scenes/ # Cenas do jogo (mapas, batalhas)
├── scripts/ # Scripts em C# (.cs)
├── ui/ # Interfaces gráficas e HUDs
├── project.godot # Arquivo principal do projeto
└── README.md
```
---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/arkplains.git
```
2. Abra o projeto na Godot Engine 4.4.1+
3. Compile os scripts em C# se necessário.
4. Execute a cena Main.tscn

## 📝 Status do Projeto
- ✅ Tema, estilo visual e jogabilidade
- 🔁 Design técnico
- 🔁 Prototipação e arte
- 🔁 Criação de tilesets
- 🔁 Sistemas (colisão, interação, movimentação)
- 🔁 Animações
- 🔁 HUD básico
- 🔁 Tutorial
- 🔄 Exportação e testes em plataformas

**Status**: Em Desenvolvimento.

---
**Desenvolvido por [Junior010101](https://github.com/Junior010101)**
