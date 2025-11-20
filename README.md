# 🔥 Algoritmo de Fogo do Doom

> *Uma implementação interativa do clássico algoritmo de propagação de fogo do DOOM com recursos aprimorados e controles em tempo real*

**Teste o projeto ao vivo: [https://caio-p-b.github.io/Doom-Fire-Algorithm/](https://caio-p-b.github.io/Doom-Fire-Algorithm/)**

<p align="center">
  <img src="https://github.com/Caio-P-B/Doom-Fire-Algorithm/blob/main/images/img4.png" alt="Demonstração do Algoritmo de Fogo do Doom" width="600">
</p>

## ✨ Características

| Funcionalidade | Descrição |
|----------------|-----------|
| 🎨 **8 Paletas de Cores** | Clássico, Vermelho, Azul, Verde, Rosa, Doces, Escala de Cinza, Arco-íris |
| 🌪️ **Controle de Direção do Vento** | Esquerda, Centro, Direita - Manipulação em tempo real das chamas |
| 🔥 **Intensidade Dinâmica do Fogo** | Ajuste a força e altura das chamas instantaneamente |
| 🔍 **Modo Debug Interativo** | Visualize a matriz de fogo com dados numéricos |
| ⚡ **JavaScript Puro** | Implementação vanilla sem dependências |

## 🧠 Como Funciona

### 1. Estrutura de Dados
A base utiliza um **array unidimensional** onde cada elemento representa a intensidade do fogo de um pixel (0-36). Este array mapeia eficientemente para uma grade 2D para representação visual mantendo performance ideal.

![Estrutura de Dados](https://github.com/Caio-P-B/Doom-Fire-Algorithm/blob/main/images/img3.png)

### 2. Algoritmo de Propagação do Fogo  
O algoritmo processa o fogo de **baixo para cima**, aplicando decaimento e efeitos de direção do vento. A intensidade de cada pixel é calculada baseada no pixel abaixo dele com decaimento aleatório e influência direcional, criando movimento realista das chamas.

![Algoritmo de Propagação do Fogo](https://github.com/Caio-P-B/Doom-Fire-Algorithm/blob/main/images/img2.png)

### 3. Sistema de Renderização
A visualização utiliza **tabelas HTML** com paletas de cores dinâmicas. O sistema suporta tanto visualização normal quanto modo debug, que exibe valores numéricos e índices para fins educacionais e de desenvolvimento.

![Sistema de Renderização](https://github.com/Caio-P-B/Doom-Fire-Algorithm/blob/main/images/img1.png)

## 🛠 Tecnologias

- **HTML5** - Sistema de renderização baseado em tabelas
- **CSS3** - Design e estilo responsivo  
- **JavaScript** - Algoritmo de fogo e features interativas
- **Sem Dependências** - Implementação vanilla pura

## 🙏 Créditos

Inspirado no **efeito de fogo original do DOOM** e na implementação educacional de **Filipe Deschamps**.

**Licença**: MIT © [Caio-P-B](https://github.com/Caio-P-B)

---

*Experimente o algoritmo clássico de fogo com interatividade moderna!* 🚀
