# Miniprojeto_AbilioAlfredoFrancisco_Analise_de_Dados_T1
Análise Exploratória de Dados (AED) aplicada ao varejo para aprender como transformar dados brutos em informações úteis. O objetivo é preparar uma base para análises mais avançadas, para alimentar um dashboard: entender os dados, limpá-los, extrair estatísticas descritivas e comunicar os principais insights de forma objetiva.

Tratamento de colunas vazias
Durante a inspeção inicial da base de dados, foram identificadas quatro colunas totalmente vazias, sem valores registados. Essas colunas foram removidas com o método dropna(axis=1, how="all"), pois não forneciam informação útil para a análise. A operação foi realizada apenas nas colunas em que todos os valores estavam ausentes, preservando as restantes variáveis e os registos disponíveis.
