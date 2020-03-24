# Micro-serviços com Node.js

- Utilizando Kafka;
- Utilizando Node;

# Aplicacões

- API Principal (Station);
- Geração de Certificado;

# Fluxo

- API principal envia  uma mensagem para o serviço de certificado para gerar o certificado;
- Micro-serviço de certificado devolve uma resposta (síncrino/assíncrona);

Se  conseguir síncrona/assíncrona:

- Receber uma resposta assíncrona de quando o e-mail com o certificado foi enviado;

# O que sabemos?

- REST (latência);
- Redis / RabbitMQ / **Kafka**;

- Nubank, Uber, PayPal, Netflix;