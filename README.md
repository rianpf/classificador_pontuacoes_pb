# Classificador de Pontuações para o Português Brasileiro (PB)

Modelo de aprendizado de máquina desenvolvido para a inserção automática de pontuação (ponto final `.`, ponto de interrogação `?` e ponto de exclamação `!`) em transcrições do Reconhecimento Automático de Fala (ASR) no português brasileiro, utilizando informações prosódicas.

## 📌 Sobre o Projeto

Este repositório contém os artefatos da pesquisa de mestrado desenvolvida na **Universidade de São Paulo (USP)**. O sistema visa estruturar e melhorar a legibilidade de textos gerados por sistemas de ASR no PB através da identificação de contornos intonacionais e prosódicos.

## 📁 Conteúdo do Repositório

* `modelo_completo_prosodia.pt`: Modelo treinado em PyTorch contendo os pesos para classificação das pontuações.
* `audios_mupe_900.zip`: Conjunto de dados com 900 arquivos de áudio em formato `.wav` (gerenciado via Git LFS).
* `.gitattributes`: Configuração do Git LFS para rastreamento de arquivos grandes.
