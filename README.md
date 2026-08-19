### Noor Muhammad

Associate Frontend Developer at Mubasher Information Group, building market data platforms and stock exchange infrastructure for the MENA region. Angular and TypeScript on the front, Java and Spring Boot behind it.

**What I work on**
echo ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat&logo=reactivex&logoColor=white) ![Ember](https://img.shields.io/badge/Ember.js-E04E39?style=flat&logo=emberdotjs&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

Live market data platforms, embeddable investor relations widgets that deliver real time data into the websites of financial institutions, and the website of a national stock exchange. Regulated data, real money, real consequences when it is wrong.

**What I care about**

Fixing causes instead of symptoms. My favourite piece of work is not a feature, it is a pair of concurrency bugs on a side project: transactions deadlocking against each other while the connection pool starved. The tempting fixes were a bigger pool, longer timeouts and a retry loop. Instead every transaction now acquires pessimistic row locks in one consistent order, which makes a lock cycle impossible, and requests are batched behind an RxJS debounce so the flood never reaches the pool. One invariant, one source fix, no patches.

**Projects**

[Rhova](https://rhova.work) is a productivity workspace I built end to end with Angular Signals, Spring Boot and PostgreSQL, including bi directional Google Calendar OAuth sync.

I also built an AI engine over the Pakistan Stock Exchange: scrapers, financial document chunking into pgvector for semantic search, and a RAG layer on Spring Boot. I rebuilt the core after realising the model could justify any outcome after the fact, so it now commits to forecasts with confidence scores and invalidation triggers, and deterministic Java grades every prediction.

**Stack**

TypeScript, Angular, RxJS, Ember, Java, Spring Boot, PostgreSQL, Python

**Elsewhere**

[LinkedIn](https://www.linkedin.com/in/noor-muhammad-b58443247/) | noorszps@gmail.com
