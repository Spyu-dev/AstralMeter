# AstralMeter ⚡

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-purple)
![License](https://img.shields.io/badge/license-AGPL--3.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-brightgreen)

**Overlay de DPS/HPS profissional para Star Resonance**

Monitore suas estatísticas de combate em tempo real com uma interface moderna e personalizável.

[📥 Instalação](#instalação) • [✨ Features](#features) • [⚙️ Configurações](#configurações) • [🎮 Como Usar](#como-usar)

</div>

---

## 📋 Pré-requisitos

> ⚠️ IMPORTANTE: Antes de instalar o AstralMeter, você precisa instalar o Npcap.

### Instalação do Npcap

O AstralMeter requer o Npcap para capturar pacotes de rede do jogo.

• Download oficial: https://npcap.com/#download

Instruções rápidas:
- Execute o instalador como Administrador
- Marque a opção "Install Npcap in WinPcap API-compatible Mode"
- Conclua a instalação e reinicie o computador

---

## 🚀 Instalação

1. Confirme o Npcap instalado (veja acima)
2. Baixe a versão mais recente do AstralMeter
3. Extraia o ZIP em uma pasta de sua preferência
4. Execute AstralMeter.exe

---

## ✨ Features

### 🎯 Monitoramento em Tempo Real
- DPS (Damage Per Second)
- HPS (Healing Per Second)
- Estatísticas totais e ranking de jogadores
- Atualização rápida (intervalos de ~100 ms)

### 🎨 Interface Moderna
- Glassmorphism (efeito de vidro) e tema roxo
- Transparência ajustável (opacidade)
- Layout compacto com scroll suave

### � Temas e Cores
- Seletor de tema diretamente na tela de Configurações
- Temas disponíveis: Purple, Blue, Red, Orange, Cyan, Gray e Rainbow
- No tema Rainbow, as barras adotam cores por subclasse automaticamente (cores diferentes para cada classe)

### �🎭 Ícones de Classe
- Ícones dedicados para especializações (subclasses)
- Identificação visual rápida e integrada ao tema

### ⚡ Modos de Visualização
- Modo Dano (DPS)
- Modo Cura (HPS)
- Alternância rápida via atalho ou toggle na interface

### 🧩 Modo Compacto
- Reduz altura das barras, margens e espessura da barra de rolagem para caber mais jogadores
- Atalho rápido: Ctrl + M (pode ser alternado também nas Configurações)
- Ideal para raids com muitos jogadores visíveis

### 🌐 Idiomas
- Idiomas suportados: Português (pt), Inglês (en) e Espanhol (es)
- Seleção de idioma nas Configurações;

### 🎛️ Configurações
- Opacidade da janela
- Mostrar porcentagem de contribuição
- Limpar ao trocar de servidor
- Atalhos de teclado personalizáveis

### ⌨️ Atalhos de Teclado (padrões)
- Ctrl + ←  — Modo Dano (DPS)
- Ctrl + →  — Modo Cura (HPS)
- Ctrl + End — Limpar estatísticas
- Ctrl + Home — Bloquear/Desbloquear (Click-through)
- Ctrl + ↑  — Rolar lista para cima
- Ctrl + ↓  — Rolar lista para baixo
 - Ctrl + M  — Alternar Modo Compacto

Todos os atalhos podem ser configurados na tela de Configurações.

---

## ⚙️ Configurações

Abra a tela de Configurações pelo ícone de engrenagem (⚙️) no canto superior direito.

### Aparência
- Opacidade da janela (30% a 100%)
- Tema: Purple, Blue, Red, Orange, Cyan, Gray, Rainbow
- Modo compacto: habilitar/desabilitar

### Comportamento
- Limpar ao trocar de servidor
- Mostrar porcentagem de contribuição

### Idioma
- Selecione o idioma da interface: pt, en, es (aplica imediatamente)

### Atalhos de teclado
- Defina combinações personalizadas para cada ação (DPS, HPS, limpar, bloquear/desbloquear, scroll)

Como definir um atalho:
1) Clique no campo do atalho
2) Pressione a combinação desejada (ex.: Ctrl+K)
3) Clique em Salvar

---

## 🎮 Como Usar

### Primeira vez
1. Inicie o AstralMeter
2. Posicione a janela (começa desbloqueada)
3. A posição é salva automaticamente
4. Abra o jogo e os dados aparecerão ao entrar em combate

### No dia a dia
1. Abra o AstralMeter (a janela abre na posição salva)
2. A janela inicia bloqueada (click-through ativo)
3. Use Ctrl+Home para bloquear/desbloquear quando necessário
4. Use os atalhos para alternar modos e navegar

---

## 🔧 Tecnologias
- Electron (app desktop)
- Node.js
- Npcap (captura de pacotes)
- Protocol Buffers (decodificação)
- Zstd (descompressão)

---

## 📝 Licença

AGPL-3.0 — veja o arquivo LICENSE para mais detalhes.

---

## 🆘 Suporte
- Abra uma Issue para reportar bugs ou sugerir melhorias
- Dúvidas e feedbacks são bem-vindos

---

## 🙌 Contribuidores

Obrigado às pessoas que contribuem para este projeto:

- [Spyu](https://github.com/Spyu-dev)
- [DoufaDev](https://github.com/DoufaDev)

