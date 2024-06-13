# Filtro de Kalman

#### Em estatística, o filtro de Kalman é um método matemático criado por Rudolf Kalman. Seu propósito é utilizar medições de grandezas realizadas ao longo do tempo (contaminadas com ruído e outras incertezas) e gerar resultados que tendam a se aproximar dos valores reais das grandezas medidas e valores associados. 

# Objetivos

#### Entender a matemática do modelamento do Filtro de Kalman (KF) :x:
#### Modelar sistemas não lineares com o Filtro de Kalman :x:
#### Entender como aplicar o filtro de kalman em um sistema linear :white_check_mark:
#### Discutir áreas da engenharia em que o KF é aplicado :white_check_mark:


# Aplicações

#### ***Navegação***	: O filtro de Kalman é comumente usado em sistemas de navegação inercial para estimar a posição, velocidade e orientação de veículos, como aeronaves, navios e veículos espaciais.

#### ***Processamento de sinais***: É aplicado em várias áreas de processamento de sinais, como comunicações sem fio, radar e sonar, para estimar e filtrar sinais ruidosos.

#### ***Visão Computacional e Rastreamento de Objetos***:: Utilizado em sistemas de visão computacional e rastreamento de objetos para prever a posição futura de objetos em movimento e reduzir o ruído nas estimativas de localização.

#### ***Robótica***:: No controle de robôs móveis e manipuladores, o filtro de Kalman é usado para estimar a pose do robô, localização em ambientes desconhecidos e localização de objetos.

#### ***Previsão Meteorológica***:: O filtro de Kalman é aplicado em modelos meteorológicos para combinar dados de várias fontes, como satélites, radares e estações meteorológicas, para fazer previsões mais precisas.

#### ***Engenharia de Controle***:: É usado em sistemas de controle para estimar o estado de um sistema dinâmico a partir de observações indiretas, permitindo o controle do sistema com base nessas estimativas.

#### ***Estimativa de Estado em Economia e Finanças***:: Em finanças, é usado para estimar a evolução de preços de ativos financeiros e outras variáveis econômicas, ajudando na previsão e tomada de decisões de investimento.

#### ***Processamento de Imagens Médicas***: Aplicado em diversas técnicas de processamento de imagens médicas, como ressonância magnética, tomografia computadorizada e ultrassom, para melhorar a qualidade das imagens e extrair informações relevantes.

# Formulação do Problema

### Monitorar a localização de um trem em movimento ao longo de uma via férrea utilizando um radar e um modelo de sua trajetória para determinar sua posição.
