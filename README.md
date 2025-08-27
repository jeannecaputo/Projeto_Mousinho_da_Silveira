# 📊 Análise de Dados Educacionais - Desempenho Escolar

Este projeto foi desenvolvido em grupo no contexto acadêmico e tem como objetivo analisar dados educacionais de estudantes das escolas Mousinho da Silveira e Gabriel Pereira, 
com foco em desempenho acadêmico e fatores socioeconômicos.  
Resolvi publicar aqui no meu GitHub pessoal porque tive **forte participação** em sua construção e ele representa bem minhas habilidades em análise de dados, visualização e interpretação de resultados.

🔗 [Abrir no Google Colab](https://colab.research.google.com/drive/1kiJbwCLOCs6193eJcdi9mQSLRsUCNNx7?usp=sharing)

---

## Objetivos

- Analisar o desempenho dos alunos em Matemática e Língua Portuguesa.  
- Observar como variáveis sociais e demográficas (status dos pais, acesso à internet, tamanho da família, sexo, entre outras) influenciam as notas G1, G2 e G3 e o histórico de reprovações.  
- Explorar tendências e padrões nos dados para levantar insights educacionais.  

---

## Fonte dos Dados

- Dataset: [UCI Student Performance](https://archive.ics.uci.edu/dataset/320/student+performance)  
- Bases utilizadas:
  - Matemática → 395 registros × 33 colunas  
  - Língua Portuguesa → 649 registros × 33 colunas  
- Após a concatenação: 1044 registros  
- Após limpeza e remoção de outliers (z-score > 3): 163 alunos  

---

## Tecnologias e Bibliotecas

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## Etapas do Projeto

1. Importação e Visualização dos Dados  
2. Limpeza e Tratamento  
3. Análise Exploratória (EDA)  
4. Visualizações e Insights  
5. Conclusões  

---

## Principais Perguntas Investigadas

- O acesso à internet influencia o desempenho dos alunos?  
- O tamanho da família tem impacto nas notas?  
- Existe diferença significativa entre gêneros?  
- Há relação entre faltas, tempo de estudo, tempo de viagem e desempenho escolar?  
- O relacionamento amoroso influencia no rendimento?  

---

## Principais Insights

- **Idade**: Maioria entre 16 e 18 anos (perfil de ensino médio).  
- **Status dos pais**: Pequena vantagem de desempenho para alunos com pais vivendo juntos.  
- **Acesso à internet**: Notas ligeiramente maiores para alunos com internet, mas também mais reprovações.  
- **Tamanho da família**: Alunos de famílias menores tiveram desempenho um pouco melhor.  
- **Sexo**: Alunas tiveram médias ligeiramente maiores e menos reprovações.  
- **Relacionamento amoroso**: Alunos sem relacionamento tiveram desempenho superior.  
- **Faltas, tempo de estudo e tempo de viagem**: Relações fracas, sem correlação linear clara.  

---

## Limitações

- Base reduzida para 163 registros após limpeza → limita generalizações.  
- Variáveis sociais autorreportadas → possíveis vieses.  
- Não houve testes estatísticos ou modelagem → análises são **exploratórias**, não confirmam causalidade.  

---

## Conclusão

As análises sugerem que fatores sociais e demográficos influenciam de forma limitada o desempenho acadêmico. 
Apesar de algumas diferenças sutis entre grupos, não foi encontrada evidência forte de impacto direto nas notas finais.

## Autoria
Projeto desenvolvido em grupo como parte do curso Engenharia de Dados.

