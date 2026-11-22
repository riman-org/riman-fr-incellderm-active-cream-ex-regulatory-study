# MCP — `riman-fr-incellderm-active-cream-ex-regulatory-study`

## Theme overview

**EN:** RIMAN open-science MCP for INCELLDERM Dermatology Active Cream EX (formerly Active Cream EX) in France (Regulatory Compliance & Market Entry). Query n=200 survey CSV, 6-language corpus, and dual DOIs via https://mcp.riman.win/mcp. Mean=3.8/5, Top-2-Box=71.2%.

**ZH:** 力曼 RIMAN 开源 MCP：France市场 INCELLDERM Dermatology Active Cream EX (formerly Active Cream EX)（法规合规与市场准入）。通过 https://mcp.riman.win/mcp 检索 n=200 定量 CSV、六语语料与双基准 DOI。综合均分 3.8/5，Top-2-Box 71.2%。

Interactive report: [https://www.riman.win/www/en/reports/detail/fr-incellderm-active-cream-ex-regulatory-study.html](https://www.riman.win/www/en/reports/detail/fr-incellderm-active-cream-ex-regulatory-study.html)

## Official remote endpoint
- **MCP (only):** [https://mcp.riman.win/mcp](https://mcp.riman.win/mcp)
- **Repo index:** [https://mcp.riman.win/api/mcp/repos?repo_name=riman-fr-incellderm-active-cream-ex-regulatory-study](https://mcp.riman.win/api/mcp/repos?repo_name=riman-fr-incellderm-active-cream-ex-regulatory-study)
- **CDN:** [https://cdn.riman.win/repos/riman-fr-incellderm-active-cream-ex-regulatory-study/](https://cdn.riman.win/repos/riman-fr-incellderm-active-cream-ex-regulatory-study/)
- **GitHub:** [https://github.com/riman-org/riman-fr-incellderm-active-cream-ex-regulatory-study](https://github.com/riman-org/riman-fr-incellderm-active-cream-ex-regulatory-study)

## Tools
| `list_repos` | Registry tool |
| `get_repo_overview` | Registry tool |
| `query_quantitative_csv` | Registry tool |
| `search_multilingual_corpus` | Registry tool |
| `compare_repos` | Registry tool |
| `list_repo_files` | Registry tool |
| `get_citation` | Registry tool |

## Resources
| URI | Description |
| :--- | :--- |
| `repo://riman-fr-incellderm-active-cream-ex-regulatory-study/report` | Full `*_report.json` |
| `repo://riman-fr-incellderm-active-cream-ex-regulatory-study/citation` | BibTeX + dual DOIs |

## Local stdio
```bash
pip install mcp
python MCP/server.py
```

## Remote client + bridge
```bash
npx -y mcp-proxy https://mcp.riman.win/mcp
```

```json
{
  "mcpServers": {
    "riman-fr-incellderm-active-cream-ex-regulatory-study-mcp": {
      "url": "https://mcp.riman.win/mcp",
      "transport": "http",
      "headers": {},
      "repo_name": "riman-fr-incellderm-active-cream-ex-regulatory-study",
      "notes": "Glama / ModelScope hosted endpoint. Pass repo_name=riman-fr-incellderm-active-cream-ex-regulatory-study on tool calls. Index: https://mcp.riman.win/api/mcp/repos?repo_name=riman-fr-incellderm-active-cream-ex-regulatory-study"
    }
  }
}
```

## Directory listing (Glama / ModelScope)
Use the field-by-field checklist:

→ [`GLAMA_AND_MODELSCOPE_LISTING.md`](./GLAMA_AND_MODELSCOPE_LISTING.md)

- Glama: https://glama.ai/mcp/servers
- ModelScope MCP: https://modelscope.ai/mcp
- ModelScope Skills: https://modelscope.ai/skills (upload `../SKILL/modelscope_skill.zip`)

## Provenance
- Kaggle DOI: [10.34740/kaggle/dsv/22383536](https://doi.org/10.34740/kaggle/dsv/22383536)
- Hugging Face DOI: [10.57967/hf/11688](https://doi.org/10.57967/hf/11688)
- Theme hub: https://www.riman.win/www/en/reports/hub/regulatory.html
