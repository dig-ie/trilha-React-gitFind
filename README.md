# 🧭 GitFind

> Projeto desenvolvido intencionalmente com **padrões antigos do React (Era CRA – 2016 ~ 2021)**, explorando práticas e estruturas hoje consideradas **datadas**, mas que marcaram a evolução do ecossistema.

---

## 🎯 Propósito

Este projeto foi criado **por curiosidade técnica e estudo histórico** — com o objetivo de **entender como eram organizadas aplicações React nas primeiras gerações**, especialmente durante a era do **Create React App (CRA)**.

Na prática, o código adota padrões **anteriores à popularização de Hooks, TypeScript e CSS-in-JS**, como:

- Estrutura baseada em **arquivos `.js` e `.css` separados**
- Componentes funcionais simples (sem Hooks modernos)
- Estilos **globais** e importações diretas (`import './App.css'`)
- Nenhum uso de TypeScript (`.tsx`) ou Tailwind/styled-components
- Build configurado via **Create React App (CRA)**

> 💡 O objetivo foi entender o fluxo e as limitações dessas abordagens, comparando com os **patterns modernos** (Next.js, Vite, Hooks, CSS Modules, Tailwind etc.).

---

## 🖼️ Telas

### Tela inicial

![image](/public/gitfolio_home_screen.png)

---

### Busca de usuário e seus repositórios

O app consome a **API pública do GitHub**, listando o usuário e seus repositórios com base no username informado.

![GITFIND_SEARCH](https://github.com/dig-ie/trilha-react-gitFind/assets/101150281/be806670-2346-4831-b086-ada931ec0d2d)

---

### Registro histórico (versão antiga da UI)

![image](https://github.com/dig-ie/trilha-react-gitFind/assets/101150281/3c69754e-bde8-4f87-be83-2c0e030155ca)

---

## ⚙️ Tecnologias usadas

- **React 17 (CRA)**
- **JavaScript (.js)**
- **CSS tradicional (.css)**
- **API pública do GitHub**

---

## 🧩 Objetivo educacional

> “Entender o passado do React é essencial para dominar o presente.”

Este repositório funciona como uma **pequena cápsula do tempo** dentro do ecossistema React — útil para quem quer compreender como surgiram conceitos que hoje damos como padrão:

- Modularização de componentes
- Importação de estilos locais
- Estrutura de build do CRA
- Evolução até o uso de Hooks, TS e Vite/Next

---

## 🚀 Próximos passos

- Reescrever o mesmo app usando **React moderno (Vite + TS + Tailwind)**
- Comparar tamanho do bundle, legibilidade e performance
- Criar artigo/README comparando as versões
