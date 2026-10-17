<div align="center">

# Hey, I'm Davi de Jesus 

**Python Developer building open-source tools for the Bitcoin ecosystem.**

[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/devdavidejesus)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/devdavidejesus)
[![Proton Mail](https://img.shields.io/badge/Proton_Mail-6D4AFF?style=flat-square&logo=protonmail&logoColor=white)](mailto:davidejesus.log@proton.me)
[![Donate Bitcoin](https://img.shields.io/badge/Donate-F7931A?style=flat-square&logo=bitcoin&logoColor=white)](https://github.com/devdavidejesus/btc-toolkit#support)

</div>
<br>

### Featured project — btc-toolkit

<a href="https://github.com/devdavidejesus/btc-toolkit">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/devdavidejesus/btc-toolkit/main/assets/logo-dark.svg"/>
    <img src="https://raw.githubusercontent.com/devdavidejesus/btc-toolkit/main/assets/logo.svg" alt="btc-toolkit" width="360"/>
  </picture>
</a>

[![PyPI](https://img.shields.io/pypi/v/btc-toolkit?label=PyPI&color=F7931A&logo=pypi&logoColor=white)](https://pypi.org/project/btc-toolkit/)
[![Tests](https://github.com/devdavidejesus/btc-toolkit/actions/workflows/tests.yml/badge.svg)](https://github.com/devdavidejesus/btc-toolkit/actions/workflows/tests.yml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/devdavidejesus/btc-toolkit/badge)](https://scorecard.dev/viewer/?uri=github.com/devdavidejesus/btc-toolkit)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/14966/badge)](https://www.bestpractices.dev/projects/14966)

**Read and verify Bitcoin from your terminal.** Zero dependencies (Python standard library only), no Bitcoin Core required. It reads the chain through the Mempool.space public API, or your own Mempool instance via `--api-url`, and checks what it can by computation: address checksums offline, and a transaction against its block's Merkle proof and proof of work. Scriptable end to end: stdin, batch files, JSON Lines.

```bash
pipx install btc-toolkit
# or: pip install btc-toolkit · uv tool install btc-toolkit
# or, on macOS and Linux: brew install devdavidejesus/tap/btc-toolkit
```

**Read**

| Command | What it does |
|---|---|
| `btc-toolkit opreturn <txid>` | Decode OP_RETURN messages from any transaction |
| `btc-toolkit inscription <txid>` | Ordinals inscription envelopes: content type, size, SHA-256, text |
| `btc-toolkit tx <txid>` | Transaction details: status, fees, size, RBF, and every input and output |
| `btc-toolkit address <address>` | Aggregated overview: type, balance, lifetime totals |
| `btc-toolkit balance <address>` | Confirmed + unconfirmed balance of any address |
| `btc-toolkit utxo <address>` | Unspent outputs of any address |
| `btc-toolkit block <height\|hash\|latest>` | Block metadata, from genesis to chain tip |
| `btc-toolkit fees` | Recommended fee rates + mempool backlog |

**Verify**

| Command | What it does |
|---|---|
| `btc-toolkit verify <txid>` | Check a transaction is in a block **by computation**: its Merkle proof and the header's proof of work |
| `btc-toolkit decode <rawtx>` | Decode a raw transaction **offline** |
| `btc-toolkit validate <address>` | Check an address **offline**: checksum, network, type, and nothing is sent |

Python 3.11+ · 90% test coverage floor · fuzzed · CI on Linux, macOS and Windows · releases signed with Sigstore, with PEP 740 provenance

```text
$ btc-toolkit validate 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa

  ✓ Valid mainnet address — checksum verified, nothing sent anywhere

  ├─ Type:     P2PKH
  └─ Hash160:  62e907b15cbf27d5425399ebf6f0fb50ebb88f18
```

Listed among the [developer tools](https://www.lopp.net/bitcoin-information/developer-tools.html) in Jameson Lopp's Bitcoin resources.

→ [github.com/devdavidejesus/btc-toolkit](https://github.com/devdavidejesus/btc-toolkit) · [pypi.org/project/btc-toolkit](https://pypi.org/project/btc-toolkit/)

<br>

### Writing

**[49 Messages to a Thief](https://dev.to/devdavidejesus/49-messages-to-a-thief-what-people-wrote-to-the-coldcard-hackers-bitcoin-wallet-l1n)** — the Coldcard hacker's wallet holds 562 BTC and has received 49 on-chain messages, from pleas to a 2,857-byte essay. Every quote checked against the chain with btc-toolkit, with the script to reproduce it.

**[I Read a $320M Ransom Negotiation From My Terminal](https://dev.to/devdavidejesus/i-read-a-320m-ransom-negotiation-from-my-terminal-1159)** — the Liquid Network drain was negotiated on-chain via OP_RETURN. Every message decoded with btc-toolkit, every transaction ID included, so you can verify each word yourself.

<br>

### Open-source contributions

**[bitcoin.org](https://github.com/bitcoin-dot-org/Bitcoin.org)** — Collaborator with merge access helping maintain bitcoin.org, the Bitcoin reference website online since 2008 — auditing wallet and exchange listings, modernizing core content, and correcting whitepaper translations, each change verified against primary sources.<br>
[All pull requests](https://github.com/bitcoin-dot-org/Bitcoin.org/pulls?q=is%3Apr+author%3Adevdavidejesus) · [All issues](https://github.com/bitcoin-dot-org/Bitcoin.org/issues?q=is%3Aissue+author%3Adevdavidejesus)

**[Electrum](https://github.com/spesmilo/electrum)** — Fixes and new features merged into the Electrum wallet: a `dscancel` command, clear errors for malformed CLI arguments, tests for CLI commands, and crash fixes in the Android (QML) app.<br>
[Merged pull requests](https://github.com/spesmilo/electrum/pulls?q=is%3Apr+author%3Adevdavidejesus+is%3Amerged)

**[Armory](https://github.com/goatpig/BitcoinArmory)** — Working with the maintainer on the 0.97 release: macOS build and GUI fixes, concurrency fixes in the database server, and bug reports on memory safety and offline signing.<br>
[All pull requests](https://github.com/goatpig/BitcoinArmory/pulls?q=is%3Apr+author%3Adevdavidejesus) · [All issues](https://github.com/goatpig/BitcoinArmory/issues?q=is%3Aissue+author%3Adevdavidejesus)

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
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Jekyll](https://img.shields.io/badge/Jekyll-CC0000?style=flat-square&logo=jekyll&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=flat-square&logo=bitcoin&logoColor=white)

<br>

---

<div align="center">

![Snake animation](https://raw.githubusercontent.com/devdavidejesus/devdavidejesus/output/github-snake-dark.svg)

*If my open-source work is useful to you, you can [support btc-toolkit](https://github.com/devdavidejesus/btc-toolkit#support).*

*"Don't Trust, Verify."*

[![Bitcoin block height](https://img.shields.io/badge/dynamic/json?url=https://mempool.space/api/blocks/tip/height&query=$&label=%E2%82%BF%20block%20height&color=F7931A&style=flat-square&logo=bitcoin&logoColor=white)](https://mempool.space)

</div>
