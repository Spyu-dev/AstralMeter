# AstralMeter ⚡

<p align="right">
  <a href="README.md">English</a> · <strong>Português</strong> · <a href="README.es-ES.md">Español</a>
</p>

<div align="center">
[![GitHub](https://img.shields.io/github/downloads/Spyu-dev/AstralMeter/total?style=for-the-badge&color=%23280137)](https://github.com/spyu-dev/AstralMeter/releases/latest)

![Versão](https://img.shields.io/badge/version-1.0.1-purple)
![Licença](https://img.shields.io/badge/license-AGPL--3.0-blue)
![Plataforma](https://img.shields.io/badge/platform-Windows-brightgreen)

[<img src="static/kofi.png" alt="Ko-fi" width="230"/>](https://ko-fi.com/spyudev)

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png)](https://www.buymeacoffee.com/spyu)

**Overlay de DPS/HPS profissional para Star Resonance**

Monitore suas estatísticas de combate em tempo real com uma interface moderna e personalizável.

[📥 Instalação](#-instalação) • [✨ Recursos](#-recursos) • [⚙️ Configurações](#-configurações) • [🎮 Como Usar](#-como-usar)

</div>

---

## 📋 Pré-requisitos

> ⚠️ IMPORTANTE: Instale o Npcap antes de executar o AstralMeter.

### Instalação do Npcap

O AstralMeter depende do Npcap para capturar os pacotes de rede do jogo.

- Download oficial: https://npcap.com/#download
- Execute o instalador como Administrador
- Marque "Install Npcap in WinPcap API-compatible Mode"
- Conclua a instalação e reinicie o Windows

---

<p align="center">
  <a href="https://github.com/Spyu-dev/AstralMeter/releases/tag/1.0.1"><strong>[CLIQUE AQUI PARA BAIXAR O MEDIDOR DE DPS]</strong></a>
</p>

## 🚀 Instalação

1. Confirme o Npcap instalado (veja acima)
2. Baixe a versão mais recente do AstralMeter no botão das Notas da Versão
3. Extraia o `.zip` na pasta de sua preferência
4. Execute `AstralMeter.exe`

---

## ✨ Recursos

### 🎯 Monitoramento em Tempo Real
- DPS (Damage Per Second)
- HPS (Healing Per Second)
- Estatísticas totais e ranking de jogadores
- Atualização rápida (intervalos de ~100 ms)

### 🎨 Interface Moderna
- Glassmorphism com identidade roxa
- Transparência ajustável (opacidade)
- Layout compacto com rolagem suave

### 🎨 Temas e Cores
- Seletor de tema direto na tela de Configurações
- Temas disponíveis: Purple, Blue, Red, Orange, Cyan, Gray e Rainbow
- No tema Rainbow, as barras recebem cores por subclasse automaticamente

### 🎭 Ícones de Classe
- Ícones dedicados para cada especialização (subclasse)
- Identificação visual rápida integrada ao tema ativo

### ⚡ Modos de Visualização
- Modo Dano (DPS)
- Modo Cura (HPS)
- Alternância rápida via atalho ou toggle na interface

### 🧩 Modo Compacto
- Reduz altura das barras, margens e espessura da barra de rolagem
- Atalho rápido: `Ctrl + M` (também disponível em Configurações)
- Ideal para raids com muitos jogadores visíveis

### 🌐 Idiomas
- Idiomas suportados: Português (pt), Inglês (en) e Espanhol (es)
- Alteração instantânea nas Configurações

### 🎛️ Configurações
- Controle de opacidade da janela
- Mostrar porcentagem de contribuição
- Limpar ao trocar de servidor
- Atalhos de teclado personalizáveis

### ⌨️ Atalhos Padrão
- `Ctrl + ←` — Modo Dano (DPS)
- `Ctrl + →` — Modo Cura (HPS)
- `Ctrl + End` — Limpar estatísticas
- `Alt` — Interagir (ativar/desativar click-through)
- `Ctrl + ↑` — Rolar lista para cima
- `Ctrl + ↓` — Rolar lista para baixo
- `Ctrl + M` — Alternar modo compacto

Todos os atalhos podem ser personalizados na tela de Configurações.

---

## ⚙️ Configurações

Abra a tela de Configurações pelo ícone de engrenagem (⚙️) no canto superior direito.

### Aparência
- Opacidade da janela de 30% a 100%
- Temas: Purple, Blue, Red, Orange, Cyan, Gray, Rainbow
- Habilitar ou desabilitar o Modo Compacto

### Comportamento
- Limpar ao trocar de servidor
- Mostrar porcentagem de contribuição

### Idioma
- Selecione entre pt, en, es (aplicação imediata)

### Atalhos de Teclado
- Defina combinações personalizadas para cada ação (DPS, HPS, limpar, click-through, rolagem)

Como redefinir um atalho:
1. Clique no campo do atalho
2. Pressione a combinação desejada (ex.: `Ctrl + K`)
3. Clique em Salvar

---

## 🎮 Como Usar

### Primeira vez
1. Inicie o AstralMeter
2. Posicione a janela (click-through inicia desativado)
3. A posição é salva automaticamente
4. Entre em combate no jogo para popular o medidor

### No dia a dia
1. Abra o AstralMeter (a janela carrega na posição salva)
2. Use `Alt` para alternar o click-through quando precisar interagir
3. Utilize os atalhos para trocar modos e navegar na lista

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
- [Doufa](https://github.com/DoufaDev)
