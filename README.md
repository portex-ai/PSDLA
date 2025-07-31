# Portex Standard Data License Agreement (PSDLA)

Welcome to the **PSDLA** repository — your single source for well-defined, plug-and-play data-licensing agreements.

Inspired by Creative Commons’ “pick-a-badge” simplicity, PSDLA lets buyers and sellers choose a license that matches their commercial goals **without re-drafting a full contract each time**.


## Why use PSDLA?

- **Purpose-built for data & AI** – Clauses cover model-training rights, derivative-model IP, output indemnification, and more.
- **Modular** – All versions share a common template covering ethical, practical, and transaction considerations, but feature already-built clauses for common permutations that users can easily select (e.g. exclusive vs. non-exclusive data sales).
- **Human-readable & machine-readable** – Each license file ships as Markdown **and** JSON for easy UI integration and API or MCP access.
- **Versioned** – versioning based on SemVer, e.g. `v1.0`, `v1.1`, `v2.0`, to account for improvements.


## PSDLA Overview (v1.0)


| Code                                              | Exclusivity                                                                  | Commercial Scope & Output Rights                                                                         | Extra Limitations / Options                                                 | Typical Use-Case                                                              |
| --------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **PSDLA-NE**<br>*“Non-Exclusive”*               | ❌ Seller may re-sell at any time                                            | ✔ Unlimited commercial use of internal insights & model outputs; ✔ May deploy models in production     | 🔸 Standard AI use-case provisions                                          | Datasets that can be sold to many buyers                                      |
| **PSDLA-EX**<br>*“Exclusive”*                   | ✔ Sole buyer for the**Exclusivity Term**; right of first refusal afterwards | ✔ Same commercial freedoms as PSDLA-NE                                                                  | 🔸 Standard AI use-case provisions                                          | Buyer pays premium for a head-start in the market                             |
| **PSDLA-NE-L**<br>*“Non-Exclusive Limited”*     | ❌ Seller may re-sell at any time under specified limitations                | ✔ Commercial use, but with limitations imposed by sellers                                               | 🔸 Seller specifies limitations to how the data can be used                 | Seller imposes restrictions on usage based on ethical or commercial framework |
| **PSDLA-EX-L**<br>*“Exclusive + Field-Limited”* | ✔ Same exclusivity as**PSDLA-EX** but under specified limitations           | ✔ Commercial use, but with limitations imposed by sellers                                               | 🔸 Seller specifies limitations to how the data can be usedDuration selecto | Seller grants exclusivity in one vertical while retaining other markets       |
| **PSDLA-RS**<br>*“Revenue-Share”*               | Specified by the seller                                                      | ✔ Commercial use allowed,**but buyer remits *Y %* of gross revenue from products trained on the data** | 🔸 Audit & reporting clause; 🔸 Duration selector                           | Sellers seeking recurring upside from high-value or niche datasets            |


## Contributing

Pull requests welcome. We want to build the future of the data economy together. Please open an issue first to discuss major changes or new license permutations. When contributing a new version:

1. Copy an existing license file.
2. Bump the minor or major version as appropriate (`v1.1`, `v2.0`, …).
3. Update the change-log in the file header.
4. Submit a PR with a clear description of *why* the change is required.

All contributions are released under the repository-wide SPDX license below.

---

## Repository License

The **license texts themselves are public-domain (CC0-1.0)** so they can be adopted freely.All *ancillary* code, scripts and documentation in this repo are released under the MIT License — see [`LICENSE`](LICENSE).
