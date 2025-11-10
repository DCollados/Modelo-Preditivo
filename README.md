Modelo-Preditivo de Atividade Estudantil 

Projeto integrador FIC – SENAI: análise da atividade estudantil com Python e Machine Learning

Fluxo de Trabalho: Bronze, Prata e Ouro (arquitetura medalhão)

Bronze (Dados Brutos):
Os dados originais são carregados e armazenados sem alterações

Prata (Limpeza e Transformação):
Corrigir tipos de dados e tratar valores nulos.
Criar novas features que possam ajudar na análise ou no modelo preditivo.

Ouro (Dados Analíticos):
Criar conjuntos de dados finais com agregações relevantes.
Exemplo: soma de cliques por semana, categorização de notas finais (Aprovado/Distinção vs. Reprovado/Desistência).

Análise e Modelagem

Representação dos dados como um tensor 3D (aluno × semana × cliques) usando NumPy, permitindo analisar a atividade semanal de cada aluno.
EDA (Exploração de Dados) com Pandas e Seaborn para:
Ver distribuições de notas e atividades.
Comparar padrões de alunos que tiveram sucesso vs. não sucesso.
Identificar correlações entre cliques/engajamento e desempenho final.

Machine Learning:
Treinamento de um modelo RandomForest para prever o sucesso do aluno (Aprovado/Distinção) versus não sucesso (Reprovado/Desistência).
Avaliação com métricas de performance e análise de importância das features.

Interatividade
Funções interativas permitem que o usuário:
Aplique filtros e limites em colunas específicas (ex.: número mínimo de cliques).
Gere análises e relatórios personalizados.
