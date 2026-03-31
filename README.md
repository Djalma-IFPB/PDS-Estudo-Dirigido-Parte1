PDS-Estudo-Dirigido-Parte1
Estudo Dirigido — Parte 1: Modelagem de Sinais e Sistemas Discretos

Disciplina: Processamento Digital de Sinais  
Instituição: Instituto Federal da Paraíba — IFPB  
Curso: Telemática
Aluno: Djalma L da Silva Jr

Descrição:

Estudo Dirigido — Parte 1 da disciplina de Processamento Digital de Sinais, abordando os fundamentos matemáticos da representação e 
análise de sinais discretos, bem como a modelagem e classificação de sistemas digitais.


* Estrutura do Repositório:

README.md                       # Este arquivo

> teoria:

resumo_teorico.pdf              # Resumo teórico fundamentado
discussao_tecnica.pdf           # Discussão técnica (teoria × prática)


> Simulacoes:

01 Sequencias elementares.py     # Sequências: impulso, degrau, rampa, exponencial, senoide
02 Operações com sinais.py       # Operações: deslocamento, inversão, escalonamento, soma
03 Energia e potência.py         # Energia e potência de sinais discretos
04 Classificação de sistemas.py  # Classificação de 6 sistemas (linearidade, causalidade, etc.)
05 Sensor real pbl.py            # Problema PBL: modelagem de sensor de vibração

> Resultados:

01 sequencias elementares.png  # Gráficos das sequências elementares
02 operacoes sinais.png        # Gráficos das operações com sinais
03 energia potencia.png        # Gráficos de energia e potência
04 classificacao sistemas.png  # Classificação de sistemas
05 Sensor real pbl.png         # Testes sensor de vibração, filtro e falhas pbl
 
* Conteúdos Abordados:

Resumo Teórico:

1. Sinais contínuos e discretos — definições, processo de amostragem, Teorema de Nyquist-Shannon
2. Sequências elementares — impulso unitário, degrau, rampa, exponencial real, exponencial complexa, senoide discreta
3. Operações com sinais — deslocamento, inversão temporal, escalonamento, soma e multiplicação
4. Energia e potência — definições, classificação (sinais de energia, de potência, e nem energia nem potência)
5. Classificação de sistemas — memória, linearidade, invariância no tempo, causalidade, estabilidade BIBO, invertibilidade
6. Sistemas LTI — convolução discreta e resposta ao impulso

Simulações Computacionais:

01 sequencias elementares.py - Geração e plotagem de 6 sequências elementares
02 operacoes sinais.py - Demonstração de deslocamento, inversão, decimação, soma e multiplicação
03 energia potencia.py - Cálculo de energia e potência de 4 tipos de sinais com energia acumulada
04 classificacao sistemas.py - Teste numérico de linearidade e invariância + classificação de 6 sistemas
05 sensor real pbl.py - Modelagem de sensor de vibração (1800 RPM) com filtragem e análise energética


> Como Executar (Esses códigos foram testados no google colab)

Requisitos:

- Python 3.8+
- NumPy
- Matplotlib


* Execução

Abrir os arquivos em um notebook do google colab ou em algum de sua preferência

01 sequencias elementares.py
02 operacoes sinais.py
03 energia potencia.py
04 classificacao sistemas.py
05 sensor real pbl.py


Os gráficos mostrados estão na pasta "resultados"


* Discussão Técnica

A discussão completa, incluindo a resposta ao problema norteador (PBL), está na pasta "teoria"

Em resumo, a modelagem de sinais de sensores reais envolve:
- Amostragem adequada do sinal contínuo (respeitando Nyquist);
- Decomposição em componentes (fundamental, harmônicas, transitórias, ruído);
- Análise energética para distinguir sinais transitórios de permanentes;
- Projeto de sistemas que sejam causais, estáveis (BIBO), lineares e invariantes no tempo.



* Referências Bibliográficas

- OPPENHEIM, A. V.; SCHAFER, R. W. **Discrete-Time Signal Processing**. 3ª ed. Pearson, 2010.
- LATHI, B. P. **Linear Systems and Signals**. 2ª ed. Oxford University Press, 2005.
- PROAKIS, J. G.; MANOLAKIS, D. G. **Digital Signal Processing: Principles, Algorithms, and Applications**. 4ª ed. Pearson, 2007.
