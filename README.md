# Ghost Share

**Ghost Share** é uma API backend em Java que permite o envio e compartilhamento de arquivos com **links temporários**, inspirada em serviços como WeTransfer.

## Funcionalidades

- Upload de arquivos com tempo de expiração (TTL)
- Links com senha opcional
- Rastreio de downloads (IP, horário, agente)
- Armazenamento em MinIO com fallback local
- Cache de metadados e controle de acesso
- Observabilidade com métricas e logs

Ideal para pequenos serviços de compartilhamento seguro, com foco em **resiliência, desempenho e rastreabilidade**.

## Tecnologias

- Java 17, Spring Boot 3
- PostgreSQL, Redis, MinIO
- Resilience4j, Micrometer, Swagger
