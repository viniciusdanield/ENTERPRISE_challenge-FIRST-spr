ENTERPRISE CHALLENGE 2026 — GOODWE + FIAP

Modelo de Rateio: 
C t = custo total de energia consumida no período (R$) 
kWh i = consumo do usuário i 
kWh total = consumo total de todos os usuários 
F = taxa fixa de infraestrutura (manutenção, rede, hardware) 
n = número de usuários ativos 

Fórmula do rateio: 

Rateio i​=(kWh/total​kWhi​​)⋅Ct​+F/n​

Garante proporcionalidade ao uso real (kWh). Evita injustiça em divisão 
igualitária, inclui custo fixo da infraestrutura (justo para todos os usuários), permite
escalabilidade para grandes condomínios ou empresas.  

A IA contribui diretamente para o rateio ao: prever consumo futuro por usuário
identificar anomalias que poderiam distorcer a cobrança ajustar médias de consumo para períodos futuros.  

Plano para Sprint 2:
Na Sprint 2 planejamos: 
Plano Para a Spint 2 

Intregas planejadas: 

Backend da plataforma; Criação de API REST; Registro de sessões de recarga; Armazenamento de consumo por usuário. 

Integração com carregador GoodWe: 

Simulação de dados do carregador HCA G2  

Recebimento de: potência instantânea, status do carregador, energia consumida; 

Pipeline de dados: 

Processamento de sessões,  estruturação para IA futura, preparação de dataset histórico; 

Dashboard inicial: 

Consumo por usuário Sessões ativas, total de kWh consumido. 

Base para IA 

 Estruturação dos dados para: regressão linear, detecção de anomalias. 

Ordem de execução: Backend + banco de dados; Integração simulada do carregador; Pipeline de dados; Dashboard básico(Em análise); Preparação IA. 

Integrantes:
Nome: ANA CAROLINA FREIRE MAFRA – rm573650
Nome: Daniel Guimarães Barreto – rm573425
Nome: Paulo Henrique da Silva Gola – rm572992
Nome: Vinicius Daniel de Borba – rm572091
Nome: Vitor de Araujo Ferreira – rm572838

Fontes consultadas:   
ANEEL 
Resolução 1000 da ANEEL, seus direitos sobre energia elétrica, agora num só lugar! (2022) — Agência Nacional de Energia Elétrica 
Resolução Normativa ANEEL Nº 1000 DE 07/12/2021 - Federal - LegisWeb 

GOODWE 
https://semsportal.com/  
https://semsplus.goodwe.com/ 

APIs COMPLEMENTARES 
Open Charge Map 
https://openchargemap.org/site/develop 

Google Places API 
https://developers.google.com/maps/documentation/places 

ANEEL Open Data 
https://dadosabertos.aneel.gov.br/ 

Fonte: Site de imóveis OMA. (https://oma.com.br/2025/03/28/carros-eletricos-em-condominios-tudo-o-que-precisa-saber-em-2025/) 
Fonte: ABVE. (https://abve.org.br/vendas-de-eletrificados-seguem-em-ritmo-intenso-e-atingem-16-de-participacao-de-mercado-em-abril/) 
Fontes ePowerBay, via eixos. (https://eixos.com.br/transicao-energetica/pontos-de-recarga-para-veiculos-eletricos-ultrapassam-marca-de-25-mil-no-brasil/) 

Scikit-learn — Machine Learning em Python — https://scikit-learn.org/ 

Pandas — Análise e manipulação de dados — https://pandas.pydata.org/ 

NumPy — Computação científica em Python — https://numpy.org/ 
