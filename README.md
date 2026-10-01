<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img src="./assets/banner-light.svg" width="100%" alt="Ramires Matias, desenvolvedor full stack. TypeScript do front ao back.">
</picture>

Desenvolvedor full stack. Trabalho com TypeScript do front ao back e hoje estudo arquitetura de software: como um sistema se divide, se comunica e aguenta carga.

Este perfil está documentado como um sistema.

## Diagrama

```mermaid
flowchart LR
  subgraph front["Front-end"]
    direction TB
    react["React · Next.js"]
    vue["Vue · Nuxt"]
    tw["Tailwind CSS"]
  end
  subgraph back["Back-end"]
    direction TB
    nodejs["Node.js"]
    nest["NestJS · Fastify"]
  end
  front -- HTTP --> back
  back -- eventos --> mq[("RabbitMQ")]
  back -- Prisma --> pg[("PostgreSQL")]
  back -- cache --> redis[("Redis")]
```

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,vue,nuxtjs,tailwind,nodejs,nestjs,prisma,postgres,redis,rabbitmq,docker,git" alt="TypeScript, JavaScript, React, Next.js, Vue, Nuxt, Tailwind CSS, Node.js, NestJS, Prisma, PostgreSQL, Redis, RabbitMQ, Docker, Git" />
</p>

## Decisões

| ADR | Decisão | Status |
|---|---|---|
| 001 | Usar TypeScript do front ao back. Uma linguagem e os mesmos tipos em todas as camadas. | `aceita` |
| 002 | Estudar arquitetura de software: microsserviços, arquitetura orientada a eventos, DDD e arquitetura hexagonal. | `em andamento` |
| 003 | Aprender inglês. | `em andamento` |

## Observabilidade

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=RamiresMatias&amp;hide_border=true&amp;background=00000000&amp;locale=pt_BR&amp;ring=3FB5CF&amp;fire=E3A33B&amp;currStreakLabel=3FB5CF&amp;currStreakNum=E6EDF3&amp;sideNums=E6EDF3&amp;sideLabels=8B949E&amp;dates=8B949E&amp;stroke=30363D">
  <img src="https://streak-stats.demolab.com?user=RamiresMatias&amp;hide_border=true&amp;background=00000000&amp;locale=pt_BR&amp;ring=1B7F99&amp;fire=B26B00&amp;currStreakLabel=1B7F99&amp;currStreakNum=1F2328&amp;sideNums=1F2328&amp;sideLabels=59636E&amp;dates=59636E&amp;stroke=D1D9E0" alt="Sequência de contribuições no GitHub">
</picture>

## Endpoints

| Método | Rota | Destino |
|---|---|---|
| `GET` | `/linkedin` | [linkedin.com/in/ramires-matias-311aa9191](https://www.linkedin.com/in/ramires-matias-311aa9191/) |
| `POST` | `/email` | [ramiresmatias20000@gmail.com](mailto:ramiresmatias20000@gmail.com) |

<sub>`200 OK`</sub>
