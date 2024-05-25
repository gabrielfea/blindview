# Blindview

## Introdução

O Blindview é um projeto desenvolvido para melhorar a acessibilidade de pessoas com deficiência visual. Utilizando técnicas de deep learning e processamento de imagens, o Blindview converte imagens capturadas em descrições de áudio, permitindo uma interpretação auditiva do ambiente ao redor.

## Objetivo

O objetivo do Blindview é fornecer uma ferramenta que transforma a percepção visual em auditiva, auxiliando pessoas com deficiência visual a navegar e entender melhor seu entorno.

## Funcionalidades

- **Captura de Imagens**: Utilização de câmeras para capturar imagens em tempo real.
- **Processamento de Imagens**: Modelos de deep learning são aplicados para análise e interpretação das imagens.
- **Geração de Áudio**: As interpretações visuais são convertidas em descrições de áudio detalhadas.

## Tecnologias Utilizadas

- **Python**: Linguagem principal utilizada no desenvolvimento.
- **Twilio**: Faz a ligação do WhatsApp com a api que roda no COLAB.
- **NGROK**: Deixa disponível a api através de tunel criado, para ela aparecer com link virtual, mesmo estando em um servidor do COLAB.
- **GEMINI**: I.A. Generativa da Google que analisa a imagem e faz a descrição em texto.
- **GTTs**: Google Text-to-Speech API para geração das descrições de áudio.

## Estrutura do Projeto

```plaintext
├── BlindView.ipynb
├── README.md
├── imagem1.jpg
├── imagem1.mp3
├── imagem2.jpg
├── imagem2.mp3
├── imagem3.png
├── imagem3.mp3
├── imagem4.jpg
├── imagem4.mp3
├── imagem5.jpg
├── imagem5.mp3
├── imagem6.jpg
├── imagem6.mp3
├── imagem7.jpg
├── imagem7.mp3
