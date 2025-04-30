# 🧩 github-actions-dotnet-webapp

[![.NET](https://img.shields.io/badge/.NET-8.0-purple)](https://dotnet.microsoft.com/en-us/)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-blue)](https://docs.github.com/actions)

Este repositório faz parte da atividade do **Módulo 4** do programa **GitHub4Women**. O objetivo principal é explorar e praticar o uso de **GitHub Actions** em aplicações web desenvolvidas com **.NET**, promovendo o aprendizado contínuo e a troca de conhecimento entre mulheres da área de tecnologia. 💜

---

## 🌐 Sobre o Projeto

Este projeto contém uma aplicação web desenvolvida com **.NET 8** e um pipeline de **Integração Contínua e Entrega Contínua (CI/CD)** automatizado com **GitHub Actions**.

A automação contempla:

🔧 **Build automático da aplicação**  
🧪 **Execução de testes unitários**  
🚀 **Publicação ou preparação para deploy da aplicação**

---

## ⚙️ GitHub Actions em uso

📁 Os workflows estão localizados em:

.github/workflows/

---

## 🔁 Fluxo de CI/CD
           ┌──────────────────────┐
           │ Push / Pull Request  │
           └──────────┬───────────┘
                      │
                      ▼
           ┌──────────────────────┐
           │  GitHub Actions CI   │
           └──────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │      dotnet build     │
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │      dotnet test      │
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │  dotnet publish / CI  │
          └───────────────────────┘
---

## 🎯 Objetivos do Projeto
✨ Aprender na prática como usar o GitHub Actions com aplicações .NET

🔁 Automatizar processos como build, testes e deploy

🚀 Promover boas práticas de CI/CD em projetos modernos

🤝 Compartilhar conhecimento e incentivar a colaboração entre mulheres da tecnologia

🛠️ Fortalecer habilidades em DevOps e automação de pipelines Objetivos do Projeto

---

## 🤝 Contribuição
Sinta-se à vontade para abrir issues, sugerir melhorias ou enviar pull requests!
Este projeto é um espaço de aprendizado e crescimento colaborativo. 💪✨
