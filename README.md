# Casaro v3.1.1 — Versão Web

Versão **web** do Casaro, assistente de IA com personalidade sarcástica e bem-humorada, que roda inteiramente no navegador em um único arquivo `index.html`.

## ✨ Funcionalidades

- 💬 Chat com IA via **Groq** (Llama 3.3 70B, com fallback para modelo menor)
- 🎙️ **Reconhecimento de voz** (Web Speech API)
- 🔊 **Voz sintetizada** (Speech Synthesis do navegador)
- 🎨 **Geração de imagens** por texto (Pollinations/Flux)
- 🌌 Fundo animado em `canvas`

## 🚀 Como usar

Abra o `index.html` em um navegador moderno (recomendado: Chrome/Edge, por causa da API de voz) e permita o uso do microfone.

Para funcionar, é preciso informar uma **chave de API da Groq**. Como é uma página estática, qualquer chave embutida no HTML fica visível a todos — prefira uma função serverless (ex.: Netlify Functions) que guarde a chave no servidor.

## 🛠️ Tecnologias

HTML · CSS · JavaScript · Groq API · Web Speech API

## 🔗 Relacionados

[Casaro (desktop)](https://github.com/MarcoJunior1/Casaro) · [Casaro Pocket (hardware)](https://github.com/MarcoJunior1/CasaroPockect)

## 📝 Autor

[Marco Júnior](https://github.com/MarcoJunior1)

