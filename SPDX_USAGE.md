# 🏷️ SPDX Usage – Preponderous Non-Commercial License (Preponderous-NC)

This document explains how to correctly apply the **SPDX identifier** for the Preponderous Non-Commercial License (Preponderous-NC) in source files, documentation, and build tooling.

---

## 📜 SPDX Identifier

The official SPDX identifier for this license is:

LicenseRef-Preponderous-NC

> **Disclaimer:** *Preponderous Software is not a legal entity.*  
> All rights to works published under this license are reserved by the copyright holder, **Daniel McCoy Stephenson**.

---

## ✅ When to Use

Use this SPDX identifier **only** for works that:

1. Are explicitly licensed under the **Preponderous Non-Commercial License (Preponderous-NC)**  
2. Include the full license text in a `LICENSE.md` file within the same repository  
3. Are owned by **Daniel McCoy Stephenson**, even if developed under the Preponderous Software GitHub organization

---

## 📂 Example: Source File Header

For a source file (e.g., `.java`, `.py`, `.js`), place the SPDX identifier at the top, along with a copyright notice:

// SPDX-License-Identifier: LicenseRef-Preponderous-NC  
// Copyright (c) 2022–2025 Daniel McCoy Stephenson. All rights reserved.

---

## 📄 Example: Documentation File Header

For Markdown or text-based documentation files:

SPDX-License-Identifier: LicenseRef-Preponderous-NC  
Copyright (c) 2022–2025 Daniel McCoy Stephenson. All rights reserved.

---

## ⚠️ Common Mistakes to Avoid

- ❌ **Do not** use `LicenseRef-Preponderous-NC` for projects under other licenses  
- ❌ **Do not** replace the SPDX identifier with `CC-BY-NC` or `BSL` — these are only *inspirations*, not the actual license used  
- ❌ **Do not** omit the copyright notice — it must always name **Daniel McCoy Stephenson**

---

## 🔍 Automated Compliance

Tools like [FOSSology](https://www.fossology.org/), [ScanCode](https://github.com/nexB/scancode-toolkit), and GitHub’s [license scanning](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) can detect the `LicenseRef-Preponderous-NC` tag.

This helps ensure that:

- License usage is correctly tracked  
- Non-commercial restrictions are respected  
- Commercial violations can be identified quickly

---

## 📚 References

- [README.md](./README.md) – Overview and purpose  
- [LICENSE.md](./LICENSE.md) – Full license text  
- [FAQ.md](./FAQ.md) – Common questions and clarifications  

---
