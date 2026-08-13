I like knowing what happens underneath. That is why I wrote a shell instead of
only using one, a raycaster instead of importing an engine, and an IRC server
instead of reading about sockets.

The other half of the work is shipping things people can actually open: a task
manager that runs on three platforms from one codebase, an offline-first Android
client with its own backend on Azure, a tool that scores how much an article can
be trusted.

## Where I work in the stack

| Layer | What I have built there |
| --- | --- |
| Network | routing, switching, subnetting, VLANs |
| Systems | A bash-like shell, a raycasting engine, an epoll-driven IRC server, threaded synchronisation without deadlock |
| Services | Event-driven microservices over RabbitMQ, an ASP.NET Core API on Azure, a FastAPI simulation backend |
| Infrastructure | Docker and Compose built from base images, NGINX with TLS, HashiCorp Vault, Cloud Build |
| Product | Flutter across Android, iOS and web; Kotlin with Jetpack Compose; Next.js with LLMs |

## Featured

| Project | What it is |
| --- | --- |
| **[Quanta](https://github.com/abouguri/Quanta)** · [live](https://factnews-six.vercel.app) | Four independent LLM checks score an article 0 to 100: fact risk, bias, sensationalism, red flags. Keeping them separate stops one bad signal dragging the whole verdict down. |
| **[TaskFlow](https://github.com/abouguri/TaskFlow-AI)** · [live](https://task-flow-ai-blush.vercel.app) | A task manager where rows stay one line and opening a task expands it in place. One Flutter codebase for Android, iOS and web. SQLite through eight migrations, 40 tests against an in-memory store. |
| **[Enterprise Task Manager](https://github.com/abouguri/enterprise-task-manager)** + **[API](https://github.com/abouguri/enterprise-task-manager-api)** | Offline-first Android in Kotlin and Compose: writes land locally, a WorkManager queue drains them later. The ASP.NET Core backend on Azure settles conflicts itself, rejecting stale writes with a 409 and its own row. |
| **[cub3D](https://github.com/abouguri/cub3d)** | A Wolfenstein-style raycasting engine in C. Textured walls, enemy AI, a health system, a minimap, 60+ FPS at 720p, valgrind-clean. |
| **[minishell](https://github.com/abouguri/minishell)** *(team)* | A bash-like shell in C. Parsing builds a tree where siblings chain a pipeline and children hold arguments and redirections, so one traversal executes every form. |
| **[Transcendence](https://github.com/NourMellal/transcendence)** *(team)* | Real-time multiplayer Pong as five services over RabbitMQ, behind a ModSecurity WAF with secrets in Vault. Under 30 seconds from page load to a live match. |
| **[macOS Portfolio](https://github.com/abouguri/macOS-portfolio)** | My portfolio, built as a working desktop: draggable icons, real cosine dock magnification, stacking windows, ⌘K search over the stack tags. No build step, no dependencies. |

## Also here

- **[Inception](https://github.com/abouguri/Inception)** — five containers (NGINX with TLS, WordPress, MariaDB, Adminer, a static site) built from Debian, no pre-built images, no `latest` tags
- **[NEO Risk Visualizer](https://github.com/abouguri/neo-risk-visualizer)** *(team)* — asteroid impact and deflection modelling with Monte Carlo uncertainty, for NASA Space Apps 2025
- **[IRC Server](https://github.com/yabdoul/IRC_server)** *(team)* — a C++ server on a single-threaded epoll Reactor, tested against irssi, weechat and HexChat
- **[GEObrief](https://github.com/abouguri/GEObrief)** — turning a point on a map into a readable brief without leaving the map
- **[mysql-bigquery-etl](https://github.com/abouguri/mysql-bigquery-etl)** — incremental MySQL to BigQuery, where the tables and their transforms are configuration rather than code
- **[Philosophers](https://github.com/abouguri/Philosophers)** — threads, mutexes, and no deadlock
- Plus the C and C++ groundwork underneath all of it: [Libft](https://github.com/abouguri/Libft), [Get_Next_Line](https://github.com/abouguri/Get_Next_Line), [ft_printf](https://github.com/abouguri/FT_PRINTF), [Push_swap](https://github.com/abouguri/Push_swap), and a [C++ module series](https://github.com/abouguri/cpp_pool)

## Tools I reach for

**Languages** — C, C++, TypeScript, Dart, Kotlin, C#, Python, Java, SQL

**Frameworks** — Next.js, Flutter, Jetpack Compose, ASP.NET Core, Fastify, FastAPI

**Data** — PostgreSQL, MariaDB, SQLite, Redis, BigQuery

**Infrastructure** — Docker, NGINX, RabbitMQ, HashiCorp Vault, Azure, Google Cloud, Linux
