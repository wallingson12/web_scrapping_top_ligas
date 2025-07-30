# Estatísticas de Futebol - Dashboard de Gols e Assistências

Este projeto em Python coleta dados estatísticos de futebol (artilharia e assistências) de várias competições através do site ESPN Brasil, processa e agrega os dados, e gera gráficos visuais interativos e dashboards para análise dos melhores jogadores, incluindo um dashboard focado nas estatísticas de Erling Haaland.

---

## Funcionalidades

- Coleta automática dos dados de gols e assistências das principais ligas e competições:
  - Premier League
  - FA Cup
  - La Liga
  - Copa del Rey
  - Serie A
  - Coppa Italia
  - Ligue 1
  - Coupe de France
  - Champions League
  - Europa League
- Agregação e soma dos dados de gols e assistências por jogador, combinando todas as competições.
- Geração de gráficos de barras horizontais para os Top 10 jogadores em:
  - Assistências
  - Artilharia (gols)
  - Participações totais (gols + assistências)
- Dashboard personalizado com Matplotlib focado nas estatísticas de Erling Haaland por competição, mostrando gols e assistências lado a lado.

---

## Requisitos

- Python 3.7+
- Bibliotecas Python:
  - pandas
  - requests
  - beautifulsoup4
  - plotly
  - matplotlib
  - numpy

Instale as dependências com:

```bash
pip install pandas requests beautifulsoup4 plotly matplotlib numpy
