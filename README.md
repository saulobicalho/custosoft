Proposta de uma Aplicação Web para Sistema de Custo com Custeio Direto
para Microempreendedores Individuais- MEI

1 Introdução

Este trabalho busca elaborar um prótótipo para um sistema Web para a simulação 
de um sistema de custos para Microempreendedores Individuais.
O nome do sistema é MeuCusto, e seu público alvo é aquele que se enquadra na 
condição de Microempreendedores Individuais, dentro do território brasileiro, e 
sob sua legislação. Ainda, o público-alvo é aquele que possui acesso a algum 
meio digital, com acesso a Internet.

Embora a informatização dos processos financeiros, administrativos e contábeis
seja um tema largamente debatido ao longo das últimas décadas, tem-se visto 
recentemente um aumento considerável na velocidade e complexidade das 
iniciativas de proposição de sistemas que, muitas vezes, suplantam a capacidade 
manual do homem para a contabilização de cálculos, e formulação de análises 
diante dos dados.

Ainda assim, o presente sistema pretende-se novo, por não se haver encontrado
até esta data nenhum aplicativo semelhante, com a característica de ser dirigido
ao Microempreendedor Individual, bem como de ser baseado na análise por Custeio 
Direto. Em sua maioria, as propostas existentes e disponibilizadas online, para 
uso gratuito ou pago, se dirigem à gestão de custos de atividades Industrial e 
Comercial, o que se justifica pelo fluxo de investimentos existentes na área, e 
pela relevância da otimização dessa gestão, para fins de produção/
comercialização dos produtos.

A escolha do tema deste trabalho se justifica, dessa forma, pelo caráter inovador
da proposta, bem como pela relevância que poderá vir a ter para a prestação dos
serviços dos Microempreendedores Individuais. O custeio direto, embora não seja
aceito como documento para fins fiscais, permite um amplo espectro de análises 
de cunho gerencial, priorizando o conhecimento de tais prestadores acerca dos 
diferentes serviços que prestam, e suas respectivas participações na amortização
dos custos fixos. A preocupação com o aspecto gerencial do negócio é uma 
tendência crescente dentro da comunidade empreendedora, que ainda carece de 
informações téoricas acerca desta matéria, bem como instrumentos de aplicação 
sobre os dados gerados acerca de seu negócio.

2 Revisão da Literatura

As informações contidas em MARTINS[1] foram importantes para definir a
estrutura do sistema.
Em especial, usou-se as informações pertinentes à divisão dos custos em fixos e
variáveis. Uma informação usada, por exemplo, foi a colocação dos custos/despesas de
energia elétrica, água e telefone como de caráter fixo, ainda que variem periodicamente,
mês a mês.
Ainda, usou-se tal obra para conhecer as métricas possíveis para análises
gerenciais, a partir do custeio direto, a saber: Margem de Contribuição, Ponto de
Equilíbrio e Margem de Segurança.
IIgualmente importante foi o portal do MEI[2], de onde se aproveitou em especial
informações quanto aos gastos mensais, limites de valores, informações cadastradas
do MEI e ocupações permitidas. Ainda, foi utilizado o modelo do Relatório Mensal de
Receitas Brutas.

3 Desenvolvimento

O objetivo do sistema pode ser descrito como aquele de permitir, mediante
acesso a uma aplicação baseada em web, o cadastro de um Microempreeendedor,
a configuração das características de seu negócio, o armazenamento de dados da
prestação de serviços, e o cálculo de informações relativas ao resultado obtido, a partir
dos custos fixos e variáveis do negócio, em seus diferentes serviços, e ao longo dos
meses.
As linguagens de programação utilizadas para configuração do sistema na web,
e para uma posterior versão de aplicativo mobile, serão Java e C#.
O método que servirá de base para o cálculo dos custos será o Custeio Direto,
ou Variável, pelas razões apresentadas anteriormente: permissão de variados cálculos
gerenciais e indisponibilidade no momento atual de tal ferramenta, para o público em
questão.
Existirão alguns tipos diferentes de relatórios a serem gerados pelo usuário. O
primeiro deles, o Relatório Mensal de Receitas Brutas, é um documento requerido pela
legislação do MEI, e é importante para que o prestador de serviços tenha um controle
de seu faturamento, a cada período. Tal relatório poderá ser gerado, no sistema, a
partir da funcionalidade Agenda, local do sistema em que o usuário pode consultar e
manipular a prestação de serviços de cada mês. Haverá ainda a possibilidade adicional
de impressão de uma versão do relatório em PDF.
Outros relatórios importantes para o usuário serão a DRE (Demonstração do
Resultado do Exercício), e as métricas possíveis a partir dos dados do custeio direto,
conforme anteriormente mecionados, e que estarão disponíveis, no sistema, mediante a funcionalidade Panorama, tambémcom a possibilidade adicional de impressão
de versão em PDF.
O layout pode ser dividido em quatro partes:
1 - A seção MeuPerfil, com o layout em formato de Pasta, em que o usuário
gerenciará informações pertinentes a seus dados gerais, aos dados do negócio, ao
portfólio de serviços, e a seus gastos fixos mensais.
2 - A seção Fixos, com o layout em formato de Livro, em que são o usuário pode
visualizar a relação de seus custos e despesas fixos, mês a mês.
3 - A seção Agenda, com o layout em formato de Agenda Impressa, em que
o usuário pode gerenciar os serviços à medida que os executa, ou planejá-los com
antecedência.
4 - A seção Panorama, em que o usuário pode ver o resultado das análises do
custeio direto, com as opções: DRE, Margem de Contribuição, Ponto de Equilíbrio e
Margem de Segurança.
O protótipo em pdf, em anexo a este trabalho, permite a navegação conforme
uma página da internet, de modo interativo sobre os componentes (menus, botões,
etc).

4 Resultados e Discussão

Como resultado observou-se que o protótipo sugere uma utilização satisfatória
das funcionalidades propostas. São pontos positivos a facilidade de uso, a organização
intuitiva das seções, simulando ambientes manuais habituais a qualquer trabalhador, e
a versatilidade na apresentação das diferentes métricas decorrentes do custeio direto,
com tabelas e gráficos, quando possível.
Um ponto negativo é a restrição do escopo do sistema ao método de custeio
direto, sem possibilidade de uso para fins fiscais.

5 Conclusão

Conclui-se que a disponibilização final de um sistema com as características
pretendidas será uma tarefa gradual e progressiva, envolvendo diferentes etapas
até que todos os requisitos deste tipo de usuário, o MEI, sejam satisfatoriamente
preenchidos, bem como um tempo adicional para que o mesmo se habitue ao uso do
sistema, migrando hábitos da gestão de seu negócio para o ambiente digital do sistema
proposto, uma vez que este propicie os níveis desejados de conforto, praticidade e
credibilidade

6 Referências Bibliográficas

[1]Martins, Eliseu, 1945. Contabilidade de custos / Martins, Eliseu. - 9. ed. - São
Paulo : Atlas,
2003.
[2]Portal do Empreededor. Seção de dúvidas frequentes. Disponível em http://w
ww.portaldoempreendedor.gov.br/. Acesso em: 22jun. 2018.


