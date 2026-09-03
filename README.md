<div align="center">

# Hey, I'm Davi de Jesus 🇧🇷

**Python Developer building open-source tools for the Bitcoin ecosystem.**

[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/devdavidejesus)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/devdavidejesus)
[![Proton Mail](https://img.shields.io/badge/Proton_Mail-6D4AFF?style=flat-square&logo=protonmail&logoColor=white)](mailto:davidejesus.log@proton.me)

</div>
<br>

### Featured project — btc-toolkit

[![PyPI](https://img.shields.io/pypi/v/btc-toolkit?label=PyPI&color=F7931A&logo=pypi&logoColor=white)](https://pypi.org/project/btc-toolkit/)
[![Tests](https://github.com/devdavidejesus/btc-toolkit/actions/workflows/tests.yml/badge.svg)](https://github.com/devdavidejesus/btc-toolkit/actions/workflows/tests.yml)

A unified Bitcoin CLI, **full roadmap shipped — and growing**. Built on two principles: **zero external dependencies** (Python standard library only) and **no Bitcoin Core required** (powered by the Mempool.space public API).

```bash
pip install btc-toolkit
```

| Command | What it does |
|---|---|
| `btc-toolkit opreturn <txid>` | Decode OP_RETURN messages from any transaction |
| `btc-toolkit tx <txid>` | Full transaction details: status, fees, size, I/O, RBF |
| `btc-toolkit balance <address>` | Confirmed + unconfirmed balance, all address types |
| `btc-toolkit fees` | Live fee tiers (sat/vB) + mempool backlog |
| `btc-toolkit block <height\|hash\|latest>` | Block metadata, from genesis to chain tip |
| `btc-toolkit utxo <address>` | Unspent outputs sorted by value, with filters |
| `btc-toolkit address <address>` | Aggregated overview: type, balance, lifetime totals |
| `btc-toolkit address <address>` | Aggregated overview: type, balance, lifetime totals |

87 unit tests · CI across Python 3.10–3.13 · every claim verifiable on-chain

```text
$ btc-toolkit block 0

  btc-toolkit v1.0.0 · block · Mempool.space API

  Block #0

  ├─ Hash:        000000000019d668...0a8ce26f
  ├─ Mined:       2009-01-03 18:15:05 UTC
  ├─ Txs:         1
  ├─ Difficulty:  1
  ├─ Nonce:       2083236893
  └─ Previous:    (none — genesis block)
```

→ [github.com/devdavidejesus/btc-toolkit](https://github.com/devdavidejesus/btc-toolkit) · [pypi.org/project/btc-toolkit](https://pypi.org/project/btc-toolkit/)

<br>

### Open-source contributions — bitcoin.org

Collaborator helping maintain one of the Bitcoin ecosystem's most visited reference websites — auditing wallet and exchange listings, modernizing core content, and correcting whitepaper translations, each change verified against primary sources.

[All pull requests](https://github.com/bitcoin-dot-org/Bitcoin.org/pulls?q=is%3Apr+author%3Adevdavidejesus) · [All issues](https://github.com/bitcoin-dot-org/Bitcoin.org/issues?q=is%3Aissue+author%3Adevdavidejesus)

<br>

### Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=flat-square&logo=bitcoin&logoColor=white)

<br>

---

<div align="center">

![Snake animation](https://raw.githubusercontent.com/devdavidejesus/devdavidejesus/output/github-snake-dark.svg)

*"Don't Trust, Verify."*

[![Bitcoin block height](https://img.shields.io/badge/dynamic/json?url=https://mempool.space/api/blocks/tip/height&query=$&label=%E2%82%BF%20block%20height&color=F7931A&style=flat-square&logo=bitcoin&logoColor=white)](https://mempool.space)

</div>
