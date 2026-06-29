<div align="center">

# Hey, I'm Davi de Jesus 🇧🇷

**Python Developer building open-source tools for the Bitcoin ecosystem.**

[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/0xdavidejesus)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/devdavidejesus)
[![Proton Mail](https://img.shields.io/badge/Proton_Mail-6D4AFF?style=flat-square&logo=protonmail&logoColor=white)](mailto:davidejesus.log@proton.me)

</div>

<br>

### Featured project — btc-toolkit

[![Tests](https://github.com/devdavidejesus/btc-toolkit/actions/workflows/tests.yml/badge.svg)](https://github.com/devdavidejesus/btc-toolkit/actions/workflows/tests.yml)

A Bitcoin tooling project built around two principles: **zero external dependencies** (Python standard library only) and **no Bitcoin Core required** (powered by public Bitcoin APIs).

**Phase 1 — OP_RETURN Reader CLI** (shipped)
- Python 3.10–3.13 support
- 18 unit tests
- GitHub Actions CI
- Decodes OP_RETURN messages from any Bitcoin transaction
- Powered by the Mempool.space public API

```text
$ op-return-reader 3ef1d49a3146bc30368de0d17c182c78497e61398572d86f5fbd7806ca47332e

  btc-toolkit v0.1.0 · Mempool.space API

  ✓ Found 1 OP_RETURN output(s):

  Output #1
  ├─ Size:     32 bytes
  ├─ Hex:      ff7f818a8090f0d3b682808884b0b08bc02eff7fd184dad7ef94a4e0a1f98f01
  └─ Message:  (binary data — not UTF-8 text)
```

**Roadmap**
- Phase 2 — Address Balance Checker · inspect balances for Legacy, SegWit, and Taproot addresses
- Phase 3 — Fee Estimator · estimate optimal fees from mempool conditions
- Phase 4 — Block Info Explorer · retrieve block metadata and transaction summaries
- Phase 5 — UTXO Set Inspector · inspect spendable outputs for any address

→ [github.com/devdavidejesus/btc-toolkit](https://github.com/devdavidejesus/btc-toolkit)

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
