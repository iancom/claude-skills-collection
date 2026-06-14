# claude-skills-collection

Coleção de 34 repositórios de skills/plugins para Claude Code, agregados como **submódulos git** apontando para os projetos originais (atribuição e licença de cada autor preservadas — nada é rehospedado).

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
| `marketingskills` | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | Skills de marketing |
| `awesome-claude-code-subagents` | [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | Coletânea de subagentes para Claude Code |
| `claude-skills` | [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | Coletânea de skills para Claude |
| `awesome-claude-plugins` | [quemsah/awesome-claude-plugins](https://github.com/quemsah/awesome-claude-plugins) | Lista curada de plugins Claude |
| `payload` | [payloadcms/payload](https://github.com/payloadcms/payload) | Headless CMS TypeScript/Next.js (standalone, não-skill) |
| `impeccable` | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | Skill de design/frontend impecável |
| `ECC` | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Enterprise Claude Config — agents, skills e commands |
| `ui-ux-pro-max-skill` | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | Skill de inteligência de design UI/UX |
| `caveman` | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | Plugin caveman mode — respostas terse |
| `ruflo` | [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | Framework de orquestração/agentes (ruflo) |
| `remotion` | [remotion-dev/remotion](https://github.com/remotion-dev/remotion) | Criação de vídeo em React (lib standalone, não-skill) |
| `frontend-slides` | [zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides) | Skill de slides frontend |
| `gsap-skills` | [greensock/gsap-skills](https://github.com/greensock/gsap-skills) | Skills oficiais GSAP (animação) |
| `visual-explainer` | [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer) | Skill de explicações visuais |
| `claude-seo` | [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | Skill de SEO |
| `harness` | [revfactory/harness](https://github.com/revfactory/harness) | Harness de agentes |

## Não incluídos

- **God Mode** — só link mcpmarket, sem repo GitHub oficial.
- **Ghost** — repo não localizado.
- Duplicatas que apontam para o mesmo repo (Frontend Design / artifacts-builder / "claude blog" → `anthropics/skills`; Code Review / Marketing → `gstack` + `antigravity-awesome-skills`).
- `garrytan/gstack` — reenviado no 2º lote, já presente desde o 1º (submódulo único).

## Licenças

Cada submódulo mantém a licença do projeto original. Consulte o `LICENSE` de cada pasta antes de usar/redistribuir.
