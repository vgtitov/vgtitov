### Vyacheslav Titov

Solutions architect. I design and build enterprise systems and AI agents, and measure what they change.

I work on ERP and CRM systems, integrations, and coding agents for day-to-day development. These two open-source toolkits grew out of that work. Both are MIT-licensed. Claude Code is the reference setup, with adapters for Codex, Gemini CLI, Cursor and other agents.

**Open toolkits**

- [**bsl-ai-toolkit**](https://github.com/vgtitov/bsl-ai-toolkit) gives an AI agent access to the actual 1C:Enterprise (BSL) configuration instead of relying on model memory. Rules, skills and MCP servers for code search, linting and read-only data access, plus an engine that edits forms and metadata and verifies those changes in a test database.
- [**bitrix-ai-toolkit**](https://github.com/vgtitov/bitrix-ai-toolkit) applies the same approach to 1C-Bitrix (PHP). The agent works against the installed core, PHPStan and PHP-CS-Fixer run after edits, and separate checks catch N+1 queries and core-version incompatibilities.

The principle behind both is to ground the agent in the actual code and use tools to verify its output. Documentation is in Russian.

**Contact**

[LinkedIn](https://www.linkedin.com/in/vgtitov) · [Instagram](https://www.instagram.com/vgtitov)

<details>
<summary>По-русски</summary>

Архитектор систем. Проектирую и строю ПО и ИИ-агентов для бизнеса и считаю, что это дало.

Здесь два открытых набора для работы ИИ-агентов с 1С и 1С-Битрикс. Агент работает по реальному коду и проверяет себя инструментами, а не пишет по памяти. Лицензия MIT, документация на русском. Вопросы и предложения оставляйте в issues репозиториев или пишите в LinkedIn.

</details>
