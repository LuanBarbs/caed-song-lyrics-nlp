# Análise de Letras de Músicas - Prova CAEd 2025

Este repositório contém a solução desenvolvida para a prova prática do processo seletivo CAEd 2025 (Edital 015/2025), voltada à área de desenvolvimento de tecnologia com foco em **Processamento de Linguagem Natural (NLP)**.

---

## Sobre o Projeto

A prova consistia em analisar uma base de dados textual contendo letras de músicas (com alguns poemas e livros), utilizando técnicas de ciência de dados e NLP. As tarefas envolvem:

- **Tarefa (a)**: Análise de polaridade emocional nas letras ao longo do tempo
- **Tarefa (b)**: Predição do gênero musical a partir do conteúdo textual
- **Tarefa (c)**: Geração de novas letras com modelos sequenciais (LSTM)
- **Tarefa (d)**: Construção de um grafo de colaboração entre artistas

---

## Organização dos Notebooks

| Notebook | Descrição |
|----------|-----------|
| `song_lyrics_analysis.ipynb` | Análise exploratória inicial da base |
| `song_lyrics_a.ipynb` | Tarefa (a) – Análise de polaridade |
| `song_lyrics_b.ipynb` | Tarefa (b) – Predição de gênero musical |
| `song_lyrics_c.ipynb` | Tarefa (c) – Geração de letras (requer GPU) |
| `song_lyrics_d.ipynb` | Tarefa (d) – Grafo de colaboração entre artistas |

---

## Executar no Google Colab

Você pode abrir os notebooks diretamente no Google Colab:

- [Análise Exploratória](https://colab.research.google.com/drive/1961vO-DtAAxpDf8PJhgXuL5xpvdYaWVd?usp=sharing)
- [Polaridade (Tarefa a)](https://colab.research.google.com/drive/19WmB-LuogBEHwWEpi2TVitHSLWByuQnK?usp=sharing)
- [Predição de Gênero (Tarefa b)](https://colab.research.google.com/drive/1QId-avHAS0L596hQ8sTo_8cgSsY6vlxs?usp=sharing)
- [Geração de Letras (Tarefa c)](https://colab.research.google.com/drive/1-diiaubxSM_9ht2XHdkUUaGW0SM_6v2r?usp=sharing)
- [Rede de Colaboração (Tarefa d)](https://colab.research.google.com/drive/1Zu-Tt3Ch_uXdFmauTIuMaYOBidax6ADj?usp=sharing)

---

## Dataset

O dataset utilizado na prova foi fornecido pelo CAEd.

---

## Relatório

A descrição completa do processo e dos resultados obtidos está disponível no relatório em PDF.

---

## Observações

- O modelo da Tarefa (c) requer execução em ambiente com GPU no Colab.
- Algumas tarefas utilizaram apenas uma amostra dos dados devido ao tamanho do dataset (~8.4 GB).
