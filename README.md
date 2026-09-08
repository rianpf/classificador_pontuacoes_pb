# Classificador de Pontuações para o Português Brasileiro (PB)

Modelo de aprendizado de máquina desenvolvido para a inserção automática de pontuação (ponto final `.`, ponto de interrogação `?` e ponto de exclamação `!`) em transcrições do Reconhecimento Automático de Fala (ASR) no português brasileiro, utilizando informações prosódicas.

## 📌 Sobre o Projeto

Este repositório contém os artefatos da pesquisa de mestrado desenvolvida na **Universidade de São Paulo (USP)**. O sistema visa classificar sentenças entre exclamativas, interrogativas ou declarativas.

## 📁 Conteúdo do Repositório

* `modelo_completo_prosodia.pt`: Modelo treinado em PyTorch contendo os pesos para classificação das pontuações.
* `audios_mupe_900.zip`: Conjunto de dados com 900 arquivos de áudio em formato `.wav` (gerenciado via Git LFS).
* `.gitattributes`: Configuração do Git LFS para rastreamento de arquivos grandes.

## 📖 Citação Acadêmica / Citation

Se você utilizar este modelo ou conjunto de dados em sua pesquisa, por favor cite:

```text
FERNANDES, Rian Pereira. Processamento de sentenças exclamativas e interrogativas para o Reconhecimento Automático de Fala no português brasileiro. 2026. 92 f. Dissertação (Mestrado) – Faculdade de Filosofia, Letras e Ciências Humanas, Universidade de São Paulo, São Paulo, 2026.
