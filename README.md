# Ramires Matias

Desenvolvedor full stack. Uso código para resolver problemas e hoje estudo arquitetura de software: como um sistema se divide, se comunica e aguenta carga.

No dia a dia: TypeScript, React, Next.js, Vue, Nuxt, Node.js, PostgreSQL e Prisma.

## Estudos de arquitetura

Cada estudo é um projeto pequeno, com um problema definido e uma medição no fim.

| Projeto | Problema | O que pratiquei |
|---|---|---|
| Chat escalável | Manter latência baixa com 5.000 usuários simultâneos | WebSocket, Redis pub/sub, broadcast em lote, teste de carga |
| Encurtador de URL | Redirecionar rápido sem sobrecarregar o banco | Cache de leitura com Redis, SQLite como fonte de verdade |
| Leilão | Aceitar lances concorrentes sem esperar o disco | Space-Based Architecture, script Lua atômico, persistência assíncrona |
| Livraria com microsserviços | Separar catálogo e pedidos sem banco compartilhado | RabbitMQ, eventos entre serviços, cache local |
| Livraria orientada a eventos | Processar pedido, pagamento e estoque sem acoplamento | Consumers, idempotência, testes e2e |
| Biblioteca | Manter a regra de negócio longe do framework e do banco | DDD, arquitetura hexagonal, domain events, NestJS |
| Fila resiliente | Não perder mensagem quando o processamento falha | Retry, dead letter queue, replay |

Resultado do chat escalável: o p99 caiu de 744 ms para 28 ms depois de serializar com `Buffer` e enviar o broadcast em lote.

## Projetos

- [NossaComuna](https://github.com/RamiresMatias/NossaComuna): rede de posts com curtidas, comentários e perfis. Nuxt 3, Tailwind CSS e Tiptap. [Demo](https://nossacomuna.netlify.app/)

## Contato

- [LinkedIn](https://www.linkedin.com/in/ramires-matias-311aa9191/)
- ramiresmatias20000@gmail.com
