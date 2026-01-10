# Elunix – Landing Page

Este repositório contém a landing page oficial da **Elunix**.

O projeto é desenvolvido inicialmente em **HTML, CSS e JavaScript puro**, com foco em:
- Performance
- Simplicidade
- Facilidade de manutenção
- Escalabilidade futura (migração para frameworks quando necessário)

---

## Estrutura do Projeto

- `index.html` → arquivo principal
- `components/` → seções da landing page (header, hero, benefits, etc.)
- `styles/` → estilos globais
- `js/` → scripts globais e carregador de componentes
- `assets/` → imagens, ícones e arquivos estáticos

Cada seção da landing é tratada como um **componente isolado**, facilitando evolução e manutenção.

---

## Workflow Git (Regra Simples)

Utilizamos **apenas duas branches** no momento:

### `main`
- Branch de **produção**
- Representa a versão estável do site
- Não deve receber commits diretos

### `dev`
- Branch de **desenvolvimento**
- Todo desenvolvimento acontece aqui
- É a base para testes e novas funcionalidades

---

## Regras Básicas

- ❌ Não commitar diretamente na `main`
- ✅ Desenvolver sempre na `dev`
- ✅ Atualizações na `main` devem vir da `dev`
- ✅ Commits claros e objetivos