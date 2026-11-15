<div align="center">

<a href="mailto:jainujjwal1609@gmail.com"><picture><source media="(prefers-color-scheme: light)" srcset="./assets/open-pill-light.svg" /><img src="./assets/open-pill.svg" width="340" alt="Open to internships and roles. Click to email." /></picture></a>

<picture><source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg" /><img src="./assets/hero.svg" width="100%" alt="Ujjwal Jain: backend, databases, GenAI. 15 merged PRs upstream across Apache Superset, Kubernetes, Vitest and Appwrite." /></picture>

<a href="https://www.ujjwaljain16.me/"><img src="https://img.shields.io/badge/Portfolio-121936?style=for-the-badge&logo=safari&logoColor=FFB454" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/ujjwal-jain-306b60323/"><img src="https://img.shields.io/badge/LinkedIn-121936?style=for-the-badge&logo=linkedin&logoColor=5B8CFF" alt="LinkedIn" /></a>
<a href="mailto:jainujjwal1609@gmail.com"><img src="https://img.shields.io/badge/Email-121936?style=for-the-badge&logo=gmail&logoColor=FFB454" alt="Email" /></a>

<picture><source media="(prefers-color-scheme: light)" srcset="./assets/terminal-light.svg" /><img src="./assets/terminal.svg" width="100%" alt="Terminal session. whoami: Ujjwal Jain, CS undergrad at BITS Pilani. Focus: backend, database internals, distributed systems, GenAI. Exploring: Go distributed systems, storage engines, RAG retrieval. Philosophy: build it from scratch, measure it, publish the number you got." /></picture>

<h3>measured, not claimed</h3>

<a href="https://www.ujjwaljain16.me/"><picture><source media="(prefers-color-scheme: light)" srcset="./assets/receipts-light.svg" /><img src="./assets/receipts.svg" width="100%" alt="Benchmarks. CampusSlot overlap query at 200,000 bookings: 2,469 pages read before, 30 after a GiST index. Fuze semantic search p50 latency: 3,026 ms to 1,661 ms at best run, 45 percent faster, about 900 ms still unexplained. CampusSlot bad-release drill: automatic rollback at 62 s, 0 of 4,800 user requests failed." /></picture></a>

<p><picture><source media="(prefers-color-scheme: light)" srcset="./assets/trace-light.svg" /><img src="./assets/trace.svg" width="100%" alt="Where one Fuze semantic search spends its time: Postgres executes the query in 2 ms of a 1,686 ms request; about 900 ms of the database call is not yet explained." /></picture></p>

<h3>upstream: 15 merged PRs</h3>

<a href="https://github.com/pulls?q=is%3Apr+is%3Amerged+author%3AUjjwaljain16+-user%3AUjjwaljain16"><picture><source media="(prefers-color-scheme: light)" srcset="./assets/upstream-light.svg" /><img src="./assets/upstream.svg" width="100%" alt="15 merged pull requests upstream. apache/superset: 9, RLS cache isolation, permission migration, key rotation. kubernetes-sigs/gateway-api: 2, conformance suite fixes. vitest-dev/vitest: 2. appwrite/appwrite: 1, MFA recovery-code validation. metacoglabs/hypergraph: 1, WAL recovery." /></picture></a>

<h3>field notes</h3>

<div align="left">

<p>
<a href="https://github.com/Ujjwaljain16/fuze/blob/main/docs/perf/README.md#where-the-time-goes"><b>The query takes 2 ms. The call takes 1,138.</b></a> <sub>· Fuze</sub><br/>
<sub>Profiling a live semantic search: what I ruled out, what is left, and the fix I would ship next.</sub>
</p>

<p>
<a href="https://github.com/Ujjwaljain16/campusslot/blob/main/docs/engineering/bad-release-drill.md"><b>Breaking a release on purpose</b></a> <sub>· CampusSlot</sub><br/>
<sub>Helm rolled back at 62 s and 0 of 4,800 user requests failed; without --atomic, a human had to step in.</sub>
</p>

<p>
<a href="https://github.com/Ujjwaljain16/campusslot/blob/main/docs/engineering/data-scale.md"><b>Does it stay fast when the table grows?</b></a> <sub>· CampusSlot</sub><br/>
<sub>2,469 pages read per overlap query at 200K rows, down to 30 with a range type and a GiST index.</sub>
</p>

<p>
<a href="https://github.com/Ujjwaljain16/campusslot/blob/main/docs/engineering/performance.md"><b>What limits one backend pod</b></a> <sub>· CampusSlot</sub><br/>
<sub>Throttled 96 to 100% at 500m CPU; 1000m made it 2.2x faster, and a second worker made it worse.</sub>
</p>

<p>
<a href="https://github.com/apache/superset/pull/44142"><b>Deleting 39 permissions without breaking anyone's roles</b></a> <sub>· Apache Superset</sub><br/>
<sub>29 remapped, 10 deleted, 4 of them because a remap would have silently granted write access.</sub>
</p>

<p>
<a href="https://github.com/Ujjwaljain16/MiniDB/blob/main/MiniDB_Projects/Team_ARIES_Recovery/docs/Architecture.md"><b>A relational database from scratch</b></a> <sub>· MiniDB, 2-person capstone</sub><br/>
<sub>ARIES recovery, strict 2PL, B+ trees and vectorized execution, and the tradeoffs between them.</sub>
</p>

</div>

<h3>stack</h3>

<p>
<sub><b>LANGUAGES</b></sub><br/>
<picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=py,ts,js,java,go&theme=light" /><img src="https://skillicons.dev/icons?i=py,ts,js,java,go&theme=dark" height="40" alt="Python, TypeScript, JavaScript, Java, Go" /></picture>
</p>

<p>
<sub><b>BACKEND &amp; WEB</b></sub><br/>
<picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=fastapi,flask,nodejs,express,nextjs,react,tailwind,spring&theme=light" /><img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,express,nextjs,react,tailwind,spring&theme=dark" height="40" alt="FastAPI, Flask, Node.js, Express, Next.js, React, Tailwind, Spring" /></picture>
</p>

<p>
<sub><b>DATABASES</b></sub><br/>
<picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,redis,supabase&theme=light" /><img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,redis,supabase&theme=dark" height="40" alt="PostgreSQL, MySQL, SQLite, MongoDB, Redis, Supabase" /></picture>
</p>

<p>
<sub><b>AI &amp; RETRIEVAL</b></sub><br/>
<img src="https://img.shields.io/badge/LangChain-121936?style=for-the-badge" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-121936?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/MCP-121936?style=for-the-badge" alt="MCP" />
<img src="https://img.shields.io/badge/pgvector-121936?style=for-the-badge" alt="pgvector" />
<img src="https://img.shields.io/badge/Embeddings-121936?style=for-the-badge" alt="Embeddings" />
<img src="https://img.shields.io/badge/LLM%20APIs-121936?style=for-the-badge" alt="LLM APIs" />
</p>

<p>
<sub><b>DEVOPS &amp; CLOUD</b></sub><br/>
<picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=docker,kubernetes,terraform,aws,githubactions,linux,git&theme=light" /><img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,aws,githubactions,linux,git&theme=dark" height="40" alt="Docker, Kubernetes, Terraform, AWS, GitHub Actions, Linux, Git" /></picture>
</p>

<p>
<sub><b>TESTING &amp; OBSERVABILITY</b></sub><br/>
<picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=vitest,jest,postman,prometheus,grafana&theme=light" /><img src="https://skillicons.dev/icons?i=vitest,jest,postman,prometheus,grafana&theme=dark" height="40" alt="Vitest, Jest, Postman, Prometheus, Grafana" /></picture>
</p>

<br/><br/>

<picture><source media="(prefers-color-scheme: light)" srcset="./assets/footer-light.svg" /><img src="./assets/footer.svg" width="100%" alt="still learning, still building" /></picture>

</div>
