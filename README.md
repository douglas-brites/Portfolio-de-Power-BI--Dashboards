Bem-vindos ao meu repositório de projetos desenvolvidos em Power BI

Neste compilado, deixo à disposição pública alguns projetos desenvolvidos de forma end-to-end, passando por projetos de curto, médio
e longo prazo de desenvolvimento, privilegiando arquiteturas desde as mais minimalistas até trabalhos mais complexos, compostos por
 maior volume gráfico e de tabelas.

Essas aplicações são oriundas de testes de trabalho, protótipos de projetos e de soluções empiricamente aplicadas em alguns ambientes
profissionais nos quais atuei. Desde já, esclareço que, embora alguns dos modelos advenham de aplicações reais, 
os dados usados para popular as arquiteturas são fictícios, a fim de garantir a segurança das informações e- ao mesmo tempo- manter a
estrutura proposta em funcionamento para testes e apresentações.

----

## 📂 Estrutura das Subpastas e Conteúdos

### 01 - Clientes-and-Sales

Nesta aplicação, usada como solução real e empírica para resolução de problemas de negócios de uma empresa cujo ramo de atividade
é o de posicionamento estratégico de produtos em pontos de venda, me foi solicitado o desenvolvimento de uma automação que atingisse múltiplos
objetivos de interesse, passando por acompanhamento de KPIs estratégicos, visualização gráfica de informações estratégica e tabelas 
de acompanhamento e auxílio para o cliente externo.
No projeto, desenvolvido de ponta a ponta por mim, de acordo com solicitações do cliente, foram privilegiadas as seguintes diretrizes:
 - Apresentação de KPIs em cards, com estrutura de agrupamento macro, privilegiando uma leitura rápida;
 - Gráfico de série temporal para mensuração de presença e ruptura de produtos, em âmbito global;
 - Tabelas com informações, a nível de rede, para presença e ruptura de produtos;
 - Gráfico de barras horizontais com as 10 principais redes com maior métrica para ambos os indicadores de interesse citados;
 - Gráficos abaixo, em série de tempo, para 10 principais empresas com maiores números em ambos os indicadores.
 - Modelagem de dado star schema, com dados a serem excluídos ainda  em algumas tabelas, sob caráter de teste (até maturação total,
   com diretrizes finais do cliente externo); e
 - Separação de medidas DAX por meio de agrupamento por posicionamento de página (agilidade para criação e manutenção de medidas em nível de visualização).
