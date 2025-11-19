# FIX Trading Simulator
Integração FIX / Sistema Financeiro Simulado

Objetivo

Simular envio de ordens financeiras via FIX protocol (QuickFIX/J) integrando com REST APIs, com foco em baixa latência.

Tecnologias

Java 17+, Spring Boot

QuickFIX/J

REST API para criação de ordens

ExecutorService / CompletableFuture para processamento assíncrono

Docker

Funcionalidades

Endpoint REST para criar ordens de compra/venda

Envio de ordens para servidor FIX (simulado)

Recebimento de respostas das ordens

Métricas de tempo de envio (latência)

Como rodar

Configurar o arquivo quickfix.cfg com sessão FIX

Rodar a aplicação:

mvn spring-boot:run

Enviar requisições via Postman/cURL para /api/send-orders
