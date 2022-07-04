# BCC-Artigo-Compiladores
Códigos e demais artefatos utilizados para a produção do Artigo 'Análise do impacto no tempo de compilação e execução causado pelo processo de otimização de um compilador em algorítimos de ordenação' - usado como instrumento avaliativo pelo Docente responsável pela disciplina

## Arquvios Disponibilizados

### Pastas

- **Algoritmos:** Contém os algorimos de ordenação implementados em C. Utilizados para realizar as medições e análises;

- **Arrays:** Contém o conjunto de Arrays utilizados em conjunto do algorimtos de ordenação para produção e análise de resultados. Além disso, está disonibilizado um código em C que foi usado para gerar Arrays aleatórios, bem com um script shell utilizado para automatizar a geração do conjunto de dados de entrada;

- **Scripts:** Contém os scripts shell utilizados para a produção dos dados que são analisados pelo artigo. Os scripts em questão retornam informações como tempo de compilação e tempo de execução dos programas de ordenação - considerando diferente níveis de otimização suportados pela ferramenta GCC (Mais detalhes no artigo);

- **Sort:** Programas de ordenação que utilizam os algoritmos implementados (disponíveis na pasta Algoritmos) para ordenar arrays criados a partir de arquivos texto (disponíveis na pasta Arrays);

### Arquivos Isolados

- **scriptTempoCompilacao.sh:** Script utilizado para executar os testes de compilação e armazenar o tempo em uma pasta chamada Medições (Para conferir os resultados obtidos, sugere-se ler o artigo);
- 
- **scriptTempoExecucao.sh:** Similar ao arquivo citado anteriormente, porém com propósito de mensurar os tempos de execução;

- **valores.txt:** Arquivo contendo os tamanhos dos arrays usados durante os programas de ordenação. Esse arquivo serve como elemento auxiliar para a execução dos scripts citados anteriormente; 
