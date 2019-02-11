# Zero Multa

# Análise:

Visando a segurança do bolso do usuário/cliente do nosso aplicativo, a ideia é minimizar o risco do mesmo tomar multa por rodízio, que normalmente é causada pelo esquecimento da placa do motorista! 

Além disso, indicar as áreas que são passivas de multa por rodízio, utilizando o GPS do Smartphone.

Os dados que deverão ser requisitados do usuário são: Nome Completo, Documento (RG/CPF), Placa e modelo do veículo (Lembrando que alguns tipos de rodízio são restritos a veículos pesados/motos/etc...).

O alerta deverá ser feito através de um alarme sonoro e com vibração no smartphone. O alarme espontâneo deve ser feito às 06:30, 8:30 e 16:30, apenas para lembrar sobre a placa, já o alarme de estar próximo de um território com rodízio, deverá ser acionado sempre que "necessário"(estar próximo de tal área).

Os requisitos do smartphone para utilização do app são: GPS, Acesso à internet, memória disponível, Sistema Android atualizado.

* O Aplicativo deve ter a interface simples, para uma rápida utilização do mesmo e posteriormente poder utiliza-lo em "segundo plano". 

Guilherme Dias Martins RA:1801611

# Design:
Tela de Cadastro de Placa - Deverá ser informado através de campos do tipo texto Nome Completo do usuário, Documento (RG/CPF), Placa e Modelo do veículo, ao final haverá um botão para efetivo cadastro da placa e início da utilização da solução.

Tela de Dias da Semana - Nesta tela haverá uma lista para visualizar os finais de Placa que constam no rodízio a cada dia da semana.

Notificação de Rodízio - Este alerta se dará quando a Placa Cadastrada bater com o rodízio do dia, o usuário poderá visualizar esta notificação via push. A mensagem conterá os dizeres "Hoje é dia de seu rodízio, evite andar próximos as áreas de risco" acompanhado de um ícone de carro.

Notificação de Área de Rodízio - Este alerta se dará quando o usuário estiver próximo a uma área de Rodízio, o usuário poderá visualizar esta notificação via push na tela do Celular. A mensagem conterá os dizeres "Você está próximo a uma área de risco de rodízio!" Acompanhado de um ícone de exclamação.

Gabriel Lima dos Santos. RA: 1801017

# Codificação:

Cadastro da placa - Após a inserção dos dados no formulário de cadastro (Nome, RG/CPF, Placa e Modelo) os mesmos são validados e caso correspondam as solicitações do formulário são inseridos no banco de dados do aplicativo para futuras consultas.

Flavio Paschoal Urquidi RA 1801895

Dias da semana - É apresentada na tela uma lista com os dias subsequentes, informando os que contém rodízio e os finais das placas correspondentes a tal.
Notificações de dia de rodízio - É verificado todos os dias, no horário determinado pela solicitação (06:30, 8:30 e 16:30) se há rodízio naquela data.

Paulo Henrique Ferreira RA 1801918

Dias da semana - É apresentada na tela uma lista com os dias subsequentes, informando os que contém rodízio e os finais das placas correspondentes a tal.
Notificações de dia de rodízio - É verificado todos os dias, no horário determinado pela solicitação (06:30, 8:30 e 16:30) se há rodízio naquela data. 

Anderson Douglas de Oliveira Santos RA: 1801458

