# claude-skills-collection

Coleção de 18 repositórios de skills/plugins para Claude Code, agregados como **submódulos git** apontando para os projetos originais (atribuição e licença de cada autor preservadas — nada é rehospedado).

## Clonar com submódulos

```bash
git clone --recurse-submodules https://github.com/iancom/claude-skills-collection.git
# ou, se já clonou:
git submodule update --init --recursive
```

## Repositórios

| Pasta | Origem | Descrição |
|-------|--------|-----------|
| `superpowers` | [obra/superpowers](https://github.com/obra/superpowers) | Framework de workflow agêntico com subagentes e orquestração |
| `skills` | [anthropics/skills](https://github.com/anthropics/skills) | Skills oficiais Anthropic (frontend-design, artifacts-builder, etc.) |
| `gstack` | [garrytan/gstack](https://github.com/garrytan/gstack) | Code review, marketing e toolkit de PR |
| `Anthropic-Cybersecurity-Skills` | [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) | 754 skills de cibersegurança (MITRE ATT&CK, NIST, ATLAS, D3FEND) |
| `claude-mem` | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | Memória persistente entre sessões com compressão por IA |
| `rtk` | [rtk-ai/rtk](https://github.com/rtk-ai/rtk) | Rust Token Killer — proxy CLI que corta 60–90% dos tokens |
| `snip` | [edouard-claude/snip](https://github.com/edouard-claude/snip) | Proxy CLI em Go com filtros YAML declarativos |
| `firecrawl` | [mendableai/firecrawl](https://github.com/mendableai/firecrawl) | Scraping/crawl para agentes via CLI |
| `remotion-skills` | [remotion-dev/skills](https://github.com/remotion-dev/skills) | Skills oficiais Remotion — vídeo em React (28 regras) |
| `agent-browser` | [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) | Automação de browser para agentes de IA |
| `vercel-agent-skills` | [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | Skills Vercel: React, web design, performance |
| `MoneyPrinterTurbo` | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | Geração de vídeos curtos com IA (standalone, não-skill) |
| `Understand-Anything` | [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything) | Pipeline multi-agente + knowledge graph do projeto |
| `coroboros-agent-skills` | [coroboros/agent-skills](https://github.com/coroboros/agent-skills) | Skill `markitdown` (PDF/DOCX/PPTX/XLSX/HTML/etc.) |
| `stop-slop` | [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) | Detecta e remove padrões de escrita de IA |
| `taste-skill` | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Frontend design taste — UI premium, GSAP motion |
| `antigravity-awesome-skills` | [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | Coletânea de skills (marketing, core, etc.) |
| `agent-skills-for-context-engineering` | [muratcankoylan/agent-skills-for-context-engineering](https://github.com/muratcankoylan/agent-skills-for-context-engineering) | Skills para context engineering e multi-agente |

## Não incluídos

- **God Mode** — só link mcpmarket, sem repo GitHub oficial.
- **Ghost** — repo não localizado.
- Duplicatas que apontam para o mesmo repo (Frontend Design / artifacts-builder / "claude blog" → `anthropics/skills`; Code Review / Marketing → `gstack` + `antigravity-awesome-skills`).

## Licenças

Cada submódulo mantém a licença do projeto original. Consulte o `LICENSE` de cada pasta antes de usar/redistribuir.
