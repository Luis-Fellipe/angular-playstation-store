# Projeto Angular - PlayStation Store 🎮🛒

## 📌 Sobre o Projeto

Este projeto consiste em uma interface front-end inspirada na PlayStation Store, desenvolvida com Angular 18. A proposta foi recriar uma vitrine digital de jogos utilizando boas práticas de componentização, design modular e foco em atomicidade.  
Além disso, a aplicação é inteiramente construída com **Standalone Components**, seguindo as tendências mais recentes do Angular.

---

## 🔗 Acesse o Projeto Online

Acesse a aplicação hospedada via **GitHub Pages** no seguinte link:  
👉 [Clique aqui para abrir no navegador](https://luis-fellipe.github.io/angular-playstation-store/)

> ⚠️ Pode demorar alguns segundos para carregar devido ao tempo de inicialização do GitHub Pages com projetos Angular.

---

## 🖼️ Prévia do Projeto

> *Imagem ilustrativa da tela inicial do projeto.*

<p align="center">
  <img src="/public/preview.png" alt="Preview do projeto PlayStation Store" width="700"/>
</p>

---

## 🚀 Tecnologias Utilizadas

- Angular 18 (Standalone Components)
- TypeScript
- HTML5 e CSS3
- Data Binding (Interpolação)
- Estrutura atômica de componentes

---

## 💡 Destaques Técnicos

✔️ **Atomic Design com Angular**:  
O projeto adota uma arquitetura baseada em atomicidade, com componentes pequenos e reutilizáveis, como:

- `CardLabelComponent`: exibe selos como *DIGITAL*, *EXCLUSIVE*, *NEW*.
- `CardPricingComponent`: mostra o preço, tipo e console disponível do jogo.

✔️ **Standalone Components**:  
Todos os componentes do projeto são independentes (`standalone: true`), dispensando a necessidade de declarações em módulos.

✔️ **Data Binding**:  
A comunicação entre o componente pai (`home.component.html`) e os componentes filhos (`app-card`) é feita via **Property Binding**, passando dados como `gamePrice`, `gameType`, `gameLabel` e `gamePhoto`.

```html
<app-card
  gamePhoto="ac-cover.jpg"
  gamePrice="146,99"
  gameLabel="DIGITAL"
  gameType="DIGITAL | PS4"
></app-card>
```

✔️ **HTML Semântico e Organização Visual**:  
Estrutura limpa, intuitiva e responsiva, com foco na experiência visual e clareza do código.

---

## ▶️ Como Executar Localmente

1. Certifique-se de ter o **Node.js** e o **Angular CLI** instalados.
2. Clone o repositório e navegue até a pasta do projeto.
3. Execute os seguintes comandos no terminal:

```bash
npm install
ng serve
```

4. Acesse `http://localhost:4200` no seu navegador.

---

## 🔗 Links Úteis

- [Angular Documentation](https://angular.io/docs)
- [LinkedIn - Luís Fellipe](https://www.linkedin.com/in/lu%C3%ADs-fellipe-8885a1289/)
- [Mais Projetos no GitHub](https://github.com/Luis-Fellipe?tab=repositories)

---

## 📁 Status do Projeto

✅ Finalizado – Projeto de vitrine digital concluído com foco em componentização, organização atômica e uso de recursos modernos do Angular.
