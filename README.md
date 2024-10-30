# ADS_03754
Gestão de horários do ISCTE

Neste projeto o grupo deverá desenvolver uma Aplicação Web que suporte as seguintes funcionalidades: 
1) Carregue horários a partir de ficheiros csv, com estrutura similar à dos ficheiros de exemplo disponibilizados; 
 
2) Permita filtrar as instancias (v.g. aulas) que contribuem negativamente para a qualidade do horário (v.g aulas em sobrelotação);
 
3) Permita calcular e visualizar a qualidade (os múltiplos critérios de qualidade) do horário carregado; 
 
4) Permita carregar cumulativamente mais horários, calcular e visualizar de forma textual/numérica e de forma gráfica a qualidade dos horários;
 
5) Permita que o utilizador avalie a qualidade dos horários de forma conjunta (textualmente/numericamente) e graficamente, ou seja, possam ser visualizados simultaneamente a qualidade de múltiplos horários; 
 
6) Permita que o utilizador faça mudanças adhoc num horário e seja possível avaliar o impacto específico de cada uma das mudanças na qualidade do horário (v.g. sobreposição de aulas do mesmo turno causadas por essa mudança, incumprimento com as manchas horárias, etc.);
 
7) Permita carregar horários incompletos (por exemplo, com aulas sem sala atribuída e/ou sem data atribuída e/ou sem hora atribuída) e a aplicação faça sugestões de atribuição de sala às aulas sem sala, atribuição de data às aulas sem data e atribuição de hora às aulas sem hora atribuída. A aplicação deverá sugerir várias possibilidades de atribuição de salas (datas, horas) e permitir ao utilizador visualizar o efeito de cada uma das alternativas sugeridas, do ponto de vista dos critérios de avaliação da qualidade dos horários. A aplicação deverá permitir ao utilizador gerir o conjunto de restrições (regras) a ser aplicadas ao horário;
 
8) No desenvolvimento da aplicação, deve ter-se em consideração as restrições (regras) e práticas do ISCTE (de conhecimento generalizado na comunidade ISCTE) relativamente aos horários. Por exemplo, não devem ser escalonadas mais de 3 horas consecutivas de aulas da mesma UC, mesmo que sejam de tipo diferente (Teóricas/Teórico-Práticas), existem manchas horárias reservadas para os diferentes anos dos cursos (v.g. o 1º ano do regime diurno tem aulas da parte da tarde, o 2º ano tem aulas da parte da manhã, o 3º ano tem aulas da parte da tarde, etc. De igual forma, devem ser considerados os critérios de qualidade dos horários bem conhecidos na comunidade ISCTE, por exemplo, não é desejável que o horário tenha aulas em sobrelotação, aulas em salas desadequadas, aulas às 8h00 da manhã ao sábado, etc.
