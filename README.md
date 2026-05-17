# Bootcamp-
Entrega Intermediaria

Caro professor, este trabalho estou desenvolvendo desde o inicio do mes 4; na materia de introdução a computação, o nome deste projeto é PROJETO CONTENÇÃO!

Espero que goste!

Quando terminar de fazer a avaliação, peço que me diga sua opinião sincera no que posso melhorar neste projeto!

Objetivo: Medir os afluentes do rio principal (RS)

Porque? 

Bacias Hidrográficas: Muitos rios do estado (como Taquari, Caí, Sinos, Gravataí e Jacuí) convergem para o Delta do Jacuí e, em seguida, para o Lago Guaíba, em Porto Alegre. Quando todos os afluentes transbordam ao mesmo tempo, cria-se um "efeito funil" na capital e região metropolitana, elevando o nível do Guaíba a marcas históricas.
Para que serve: Evitar perdas humanas e econômicas, segurando a inflação nas cidades.
Evitar perdas humanas: O desastre de 2024 passa a contabilizar nos danos humanos 185 óbitos e 23 pessoas desaparecidas.
Dados do Atlas de Desastres apontam 4.079 mortes e 10,5 milhões de desalojados entre 1991 e 2024 (Brasil).
Por ano mortes: 123
Por ano desalojados: 303,030 mil
Historicamente, o investimento em prevenção é quase invisível no PIB nacional.
Média Histórica (2010-2022): O governo gastou entre R$ 1 bilhão e R$ 2,5 bilhões por ano.Em termos de PIB, isso representa apenas 0,01% a 0,02%.
Novo PAC (Previsão 2025): Com o aumento das verbas para R$ 11,7 bilhões em drenagem e contenção.Equivale a aproximadamente 0,1% do PIB.
Comparação: O Brasil gasta cerca de 1% do orçamento total da União com clima, mas apenas uma fração disso vai para obras físicas de prevenção.
Aqui os números saltam drasticamente, especialmente em anos de catástrofes severas.
Pacote RS (2024-2025): O montante total anunciado de R$ 111,6 bilhões. Isso equivale a cerca de 1,0% do PIB nacional destinado a um único evento em um único estado.
Auxílio Reconstrução (PIX de R$ 5.100): Os R$ 2,2 bilhões pagos. Representam 0,02% do PIB.
Este é o dado mais alarmante para o seu trabalho: quanto o Brasil perde por não ter sistemas inteligentes como o seu.
Perda Anual por Desastres: Estudos de 2026 indicam que o Brasil perde cerca de R$ 110 bilhões por ano devido a eventos climáticos (secas e enchentes).Isso significa que o país "rasga" 1,0% do seu PIB todo ano por falta de adaptação climática.
Proporção: O Brasil perde 10x mais em PIB do que investe em prevenção.
Conclusão Inicial
Se um sistema inteligente de baixo custo puder reduzir as perdas em apenas 5%, ele estaria economizando para o país cerca de R$ 5,5 bilhões por ano (ou 0,05% do PIB), o que é mais do que o dobro de todo o orçamento anual de prevenção do governo (Federal) em anos normais.
Prejuízos Financeiros Anuais: Estudos da Confederação Nacional de Municípios (CNM) e do agronegócio indicam que o setor perde, em média, entre R$ 10 bilhões e R$ 15 bilhões por ano diretamente devido a desastres hidrológicos (enchentes, enxurradas e excesso de chuva).
Anos de El Niño: Em anos com esse fenômeno (como 2023/2024), os prejuízos podem triplicar. Apenas no evento do Rio Grande do Sul em 2024, as perdas estimadas para o agro (incluindo infraestrutura e produção) ultrapassaram R$ 15 bilhões (só no Rio Grande do Sul) em um único estado.
O prejuízo não é apenas a planta que morre na água, ele é dividido em três camadas!
Sufocamento Radicular: O solo encharcado expulsa o oxigênio, matando as raízes de culturas como soja, milho e arroz.
Impossibilidade de Colheita: Máquinas não conseguem entrar em campos alagados. Se a soja fica madura na chuva sem ser colhida, o grão apodrece ou brota na vagem.
Quebra de Qualidade: Mesmo que o grão seja colhido, o excesso de umidade reduz o valor de mercado (desconto por umidade/avaria).
Morte de Animais: Afogamento direto de gado, suínos e aves em enchentes repentinas.
Estresse e Doenças: O excesso de lama e água favorece doenças de casco e infecções, reduzindo o ganho de peso e a produção de leite.
Perda de Pastagem: A inundação degrada o pasto, obrigando o produtor a gastar com ração extra ou vender o rebanho às pressas.
Solo: A enxurrada causa erosão severa, levando embora a camada fértil do solo e os fertilizantes aplicados (lixiviação).
Armazenagem: Inundação de silos e armazéns destrói estoques que já estavam colhidos.
Logística: Destruição de estradas rurais e pontes impede que a produção saia da fazenda, causando perda de cargas perecíveis (como o leite).
O agronegócio representa cerca de 24% do PIB brasileiro. Quando ocorre uma enchente de grande porte:
Redução do PIB Setorial: A quebra da safra diminui a oferta de produtos para exportação, afetando a balança comercial.
Inflação de Alimentos: Como a oferta diminui, o preço de itens básicos (como arroz, feijão e hortaliças) sobe rapidamente para o consumidor final.
Inadimplência: O produtor, sem safra para vender, não consegue pagar os financiamentos bancários, gerando uma crise de crédito no setor.
Materiais a serem utilizados: Cérebro do Sistema (Processamento)
ESP32: É a melhor escolha custo-benefício. Já possui Wi-Fi e Bluetooth integrados, permitindo que o sistema envie dados para a nuvem (IoT).
Arduino (Uno ou Nano): Ótimo para protótipos offline, mas precisaria de módulos extras para conectividade. (aumentaria o custo do projeto)
Raspberry Pi: Recomendado se você for usar visão computacional (câmeras) para analisar o nível da água. (perco precisão e aumenta o custo inicial e de manutenção da parte em campo)
Sensor Ultrassônico (HC-SR04): Mede a distância entre o sensor e a superfície da água. É o mais comum para medir o nível de rios ou bueiros sem contato direto.
Sensor de Nível de Água (Chave Boia): Funciona como um interruptor físico. Quando a água sobe, a boia levanta e fecha o circuito. É muito confiável.
Sensor de Chuva: Detecta as primeiras gotas, permitindo que o sistema entre em "estado de alerta" antes mesmo do nível subir.
Sensor de Fluxo de Água: Útil para medir a vazão em canos ou galerias pluviais.
Módulo Relé: Essencial para ligar dispositivos de alta potência, como uma motobomba para drenagem.
Buzzer Ativo: Para emitir um sinal sonoro de alerta local.
Display LCD ou OLED: Para exibir em tempo real o nível da água (ex: "Nível Crítico: 85%").
LEDs (Verde, Amarelo, Vermelho): Para um feedback visual rápido do status de risco.
Dashboard IoT (Blynk, TagoIO ou ThingsBoard): Para visualizar os gráficos de subida da água pelo celular.
Notificações: Configurar o sistema para enviar um Telegram, E-mail ou SMS quando o nível atingir a zona de risco
Atenção: aqui o sistema de alerta por e-mail ou internet é muito ineficiente, já que recorrentemente a energia cai, vou substituir esse sistema por um de alerta (como um alarme de ataque aéreo, parecido com o de Israel) (sirenes).
Atenção 02: O sistema central e de medição vai ter gerador próprio, contornando o problema da energia. (Claro o sistema de alerta também)
1- A parte em campo
2- A parte do sistema central
3- A parte do alarme
01: Sensores de medição do nível da agua nos rios afluentes e principal, adiciona-se medidores climáticos para criação de parâmetros e um histórico robusto.
02: Composição do sistema central: Um servidor que armazena dados, períodos de chuvas e histórico de enchentes, referencia de clima com base em dados coletados de outras agencias e dos sensores de campo.
03: Alerta antecipado, com a medição dos sensores em campo, esses dados passam pelo sistema central, o mesmo manda uma mensagem para o Alerta que emite o som.
Custo de Implantação e Infraestrutura (RS)
Instalação (Mão de Obra): R$ 300,00 por ponto.
Conectividade (Assinatura de Dados/Satélite/LoRaWAN): R$ 20,00/mês por ponto (R$ 240,00/ano).
Servidores e Nuvem (Cloud): Estimativa de R$ 500.000,00/ano para gerenciar os dados de 5.000 pontos.
Cálculo do Investimento Total (CapEx) (RS)
Para instalar 5.000 unidades
Hardware: 5.000 x R$ 400 = R$ 2.000.000,00
Instalação: 5.000 x R$ 300 = R$ 1.500.000,00
Desenvolvimento do Software/Dashboards: R$ 1.000.000,00 (Custo fixo inicial).
SUBTOTAL DE IMPLEMENTAÇÃO: R$ 4,5 Milhões
Custo de Manutenção Anual (OpEx) (RS)
Conectividade: 5.000 x R$ 240 = R$ 1.200.000,00
Manutenção Técnica (Troca de baterias/limpeza): R$ 800.000,00
Hospedagem de Dados (Cloud): R$ 500.000,00
TOTAL MANUTENÇÃO ANUAL: R$ 2,5 Milhões
Comparativo Final: Custo vs. Benefício (RS)
Custo de Implementação: R$ 4,5 Milhões.
Custo de Manutenção (10 anos): R$ 25 Milhões.
Soma (Investimento Total em 10 anos): R$ 29,5 Milhões.
O contraste
Lembra que o gasto federal e estadual com a enchente de 2024 foi de R$ 120,9 Bilhões? O custo de monitorar o estado inteiro por 10 anos com tecnologia inteligente representa apenas 0,02% do que foi gasto para remediar uma única grande enchente.
Este cálculo mostra que o hardware é a parte mais barata. O valor real do sistema está na inteligência dos dados (conseguir prever onde a água vai chegar e avisar a população a tempo), transformando um gasto de milhões em uma economia de bilhões!
Tempo total de evacuação
(Tempo de Detecção): Quanto tempo seu sensor leva para confirmar que o nível é crítico. (Ex: 1 a 5 minutos para evitar alarmes falsos).
(Tempo de Notificação): O tempo para o sinal sair do ESP32, chegar à nuvem e disparar o SMS/Sirene. (Ex: 30 segundos a 2 minutos).
(Tempo de Preparação): O fator humano. É o tempo que as pessoas levam para acreditar no alerta, pegar documentos e sair de casa. Em enchentes noturnas, isso é muito alto.
(Tempo de Movimentação): O tempo físico de deslocamento da área de risco até o ponto seguro.
Formula simples: Tempo de evacuação = Tempo de detecção + Tempo de notificação + Tempo de preparação + Tempo de movimentação.
Cálculo da Velocidade de Movimentação
A velocidade de uma pessoa caminhando em terreno seco é de aprox. 1,2 m/s. No entanto, se a água já atingiu a canela, essa velocidade cai drasticamente. Existe uma fórmula de engenharia de segurança para isso: V(h) = V0 x (1 – h/hmax)
V0: é a velocidade em terreno seco.
h: é a altura da água.
hmax: é a altura onde o movimento se torna impossível (aprox. 0,7m a 1m devido à força da correnteza).

Resultado esperado: Menor quantidade de baixas humanas e menores perdas econômicas.

Conclusão Final: em apenas 5 anos de implementação do sistema mais de 25 bilhões de reais são economnizados e o mais importante, 615 vidas são poupados. Mais de  1.5 milhões de famílias não são desalojadas (se o dinheiro poupado for devidamente alocado em infraestrutura urbana).

                                                      Codigo usado no esp32 

// Definições de Pinos
const int TRIG_PIN = 5;
const int ECHO_PIN = 18;
const int LED_VERMELHO = 2;
const int BUZZER = 4;

void setup() {
  Serial.begin(115200);
  pinMode(TRIG_PIN, OUTPUT);
  pinMode(ECHO_PIN, INPUT);
  pinMode(LED_VERMELHO, OUTPUT);
  pinMode(BUZZER, OUTPUT);
}

void loop() {
  // Dispara o sensor ultrassônico
  digitalWrite(TRIG_PIN, LOW);
  delayMicroseconds(2);
  digitalWrite(TRIG_PIN, HIGH);
  delayMicroseconds(10);
  digitalWrite(TRIG_PIN, LOW);

  long duracao = pulseIn(ECHO_PIN, HIGH);
  int distancia = duracao * 0.034 / 2; // Converte para cm

  Serial.print("Distância da água: ");
  Serial.println(distancia);

  // Lógica de Alerta (Exemplo: Alerta se água estiver a menos de 50cm do sensor)
  if (distancia < 50) {
    digitalWrite(LED_VERMELHO, HIGH);
    tone(BUZZER, 1000); // Toca o alarme
    Serial.println("ALERTA: CRÍTICO!");
  } else {
    digitalWrite(LED_VERMELHO, LOW);
    noTone(BUZZER);
  }
  
  delay(500);
}

















