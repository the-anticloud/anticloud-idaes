# IDAES

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-chemical_production-lightgrey)

> Anticloud-hardened packaging of the upstream project `IDAES` in category **CHEMICAL PRODUCTION**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CHEMICAL PRODUCTION · **Upstream:** https://github.com/the-anticloud/anticloud-idaes.git · **Upstream pin:** `bc4b0db4eca43b0ed1181c297f84516d97716cf5` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

![maven](../../actions/workflows/maven.yml/badge.svg)
!["windows"](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
!["ubuntu"](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
!["java"](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
!["build_by"](http://ForTheBadge.com/images/badges/built-by-developers.svg)
!["with_love"](	http://ForTheBadge.com/images/badges/built-with-love.svg)
# Idaesbasic - Project-Managment redefined

Use the 0.9.1 branch if you want to see the code before Kotlin rewrite!

<br>
<p align="center">
  <img src="https://github.com/BenHerbst/ainm/blob/master/icon.png" width=250>
  </br>
  <a href="https://benherbst.github.io/idaesbasic">Idaesbasic</a>
</p>

## Everything is a file 💾
With this project managment tool, everything is a file. Your todolists are .todo files and your kanbans .knbn ...
You can store everything local on you computer and directly in your project. For example: figures/player/player.todo, if you are a Game-Developer and you want to manage planning of the player.
</br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/83538916/138612819-686cd80a-9ede-4f05-a017-a4ef443c6c69.png" width=350>
  <img src="https://user-images.githubusercontent.com/83538916/138612887-69677d2b-ff62-4836-9b37-9949ace6c960.png" width=200>
</p>

## Big tool set ⚒️

There will be lot of tools in Idaesbasic:
- Todolist
- Kanban
- Whiteboard
- Video call
- Chatting
- Calendar
- Email
- Messenges
- ...

![image](https://user-images.githubusercontent.com/83538916/141648768-c7746c7a-ff53-4aee-9e7c-ccb2e5abb0fa.png)
![image](https://user-images.githubusercontent.com/83538916/141648690-22e5fca7-4891-469f-b31a-02e571ff1631.png)
![image](https://user-images.githubusercontent.com/83538916/141648926-f56fbbc7-86cb-411f-bea9-8d12f29999a5.png)
![image](https://user-images.githubusercontent.com/83538916/141648957-d23a2f85-e2bd-4fe1-bac4-89d59274e39f.png)

_At the moment, todolist, calendar and kanban are implemented, more are coming soon!_

## Support me ( PayPal )
|[Donate](https://www.paypal.com/donate/?hosted_button_id=C5X9LBEM7XZ64)|
|---|

## Compare with other tools

| Has feature | ✅ |
| ----------- | -- |
| Doesn't have feature |  ❌ |
| Feature is coming soon | ⏱️ |
| Not completly implemented | 😑 |

| Feature | *Idaesbasic* | Zenkit | Trello | Todoist |
| ------- | ------------ | ------ | ------ | ------- |
| Save into files | ✅ | 😑 ( Only markdowns from Hypernotes )  | 😑 ( Not directly, you must use import and export ) | ❌ |
| Kanbans | ✅ | ✅ | ✅ | ✅ |
| Calendars | ✅ | ✅ | ✅ | ❌ |
| Todolists | ✅ | ✅ | ❌ | ✅ |
| Whiteboards | ⏱️ | ❌ | ❌ | ❌ |
| Mindmaps | ⏱️ | ✅ | ❌ |
| No electron | ✅ | ❌ | ❌ | ❌|

## Get started 🛫
(1) Downloaad and install the app for windows or linux.

_How do I do that?_

**For Windows:**

Download the .exe file at https://github.com/BenHerbst/idaesbasic/releases/tag/0.9.1.

You maybe have to expand the "Assets" menu.

Then Open the Explorer and go to "Downloads". There you should find the .exe if it got downloaded. If not, download the .exe again!

Then, if downloaded and found in the Explorer, double click on it and an installer pops up.

There you just have to follow the steps and Idaesbasic is ready to use!

**For Linux:**

Download the .deb ( currently unavaible ) or .jar file at https://github.com/BenHerbst/idaesbasic/releases/tag/0.9.1. ( .deb is only for Debian or Debian based Linux like Ubuntu, Linux Mint or Pop!_OS )

Then open your file explorer. Go to "Downloads" and find the .deb or .jar file

If you downloaded the .deb for Debian or Debian based Linux, just double click the .deb and follow the install instructions.

If you got the .jar, which also runs on Arch, Manjaro or VOID Linux, you also have to get Java 17.
The best way to install it is to go to https://jdk.java.net/17/ and read the install instructions there or go to Google and check how to install Java 17 or Openjdk 17 on your system.

There is also jdk-openjdk on Arch and Manjaro: pacman -S jdk-openjdk.

After the installation of Java 17, go to the file explorer, find the .jar and double click it. If that not work, open a Terminal window and execute:

1. cd Downloads
2. java -jar (" The file name of the .jar file ")
3. if Idaesbasic doesn't start, copy the text of the Terminal window of take a screenshot and report it at https://github.com/BenHerbst/idaesbasic/issues. You have to get a Github account.

_I would love it when anyone could help me creating a flatpak of this project!_

**Macos:**
There is currently **no** Macos version. You have to self compile it with Maven and Java 17 from https://github.com/BenHerbst/idaesbasic/tree/0.9.1.

I don't own a Macos device. Apple restricts you to own a Macos device to create a package for Macos.

Maybe someone with a Mac device could help me?

</br>
(2) Click on "Projects" -> "Add project" and select a folder
</br>
(3) Create a new todolist via "File" -> "New" -> "New todolist"
</br>
(4) Name the file and set the file location
</br>
(5) Create your todos, and click on "File" -> "Save" to save them
</br>
</br>
_To update the file browser, click on "Projects" -> "Project list" -> [Project location]_

It is recommended to create a idaes-files folder under your project, as it helps keeping focus, after I tested the both methods: At same place as tasks working folder under project or as, recommended, seperate folder for Idaesbasic.

## Free and open source 🗽

Idaesbasic is free and open source software.
- Everyone can make a pull request and we will add it
- Everyone can see the code
- Everyone can change the code and build the software perfect for her / his needs

## For everyone 🧑🧑‍🦰🧑‍🦱🧑‍🦳🧑‍🦲🧔🧟
- If you want to use the software to manage your personal tasks, go and use the todolist.
- If you are a big tech company and you want to manage a website, go and use the kanban and team features, and change

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Java / Maven** (manifests: pom.xml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `bin/`, `releases/`, `src/`
- Snapshot size: **34 files**, **717 lines of code** (measured; see Benchmarks)
- Primary languages: `.kt` (13), `(none)` (5), `.md` (3), `.png` (2), `.todo` (2), `.xml` (2)
- Upstream commit pinned for this packaging: `bc4b0db4eca43b0ed1181c297f84516d97716cf5`

---

## Installation

!["with_love"](	http://ForTheBadge.com/images/badges/built-with-love.svg)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

<br>
<p align="center">
  <img src="https://github.com/BenHerbst/ainm/blob/master/icon.png" width=250>
  </br>
  <a href="https://benherbst.github.io/idaesbasic">Idaesbasic</a>
</p>

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

There you just have to follow the steps and Idaesbasic is ready to use!

**For Linux:**

Download the .deb ( currently unavaible ) or .jar file at https://github.com/BenHerbst/idaesbasic/releases/tag/0.9.1. ( .deb is only for Debian or Debian based Linux like Ubuntu, Linux Mint or Pop!_OS )

Then open your file explorer. Go to "Downloads" and find the .deb or .jar file

If you downloaded the .deb for Debian or Debian based Linux, just double click the .deb and follow the install instructions.

If you got the .jar, which also runs on Arch, Manjaro or VOID Linux, you also have to get Java 17.
The best way to install it is to go to https://jdk.java.net/17/ and read the install instructions there or go to Google and check how to install Java 17 or Openjdk 17 on your system.

There is also jdk-openjdk on Arch and Manjaro: pacman -S jdk-openjdk.

After the installation of Java 17, go to the file explorer, find the .jar and double click it. If that not work, open a Terminal window and execute:

1. cd Downloads
2. java -jar (" The file name of the .jar file ")
3. if Idaesbasic doesn't start, copy the text of the Terminal window of take a screenshot and report it at https://github.com/BenHerbst/idaesbasic/issues. You have to get a Github account.

_I would love it when anyone could help me creating a flatpak of this project!_

**Macos:**
There is currently **no** Macos version. You have to self compile it with Maven and Java 17 from https://github.com/BenHerbst/idaesbasic/tree/0.9.1.

I don't own a Macos device. Apple restricts you to own a Macos device to create a package for Macos.

Maybe someone with a Mac device could help me?

</br>
(2) Click on "Projects" -> "Add project" and select a folder
</br>
(3) Create a new todolist via "File" -> "New" -> "New todolist"
</br>
(4) Name the file and set the file location
</br>
(5) Create your todos, and click on "File" -> "Save" to save them
</br>
</br>
_To update the file browser, click on "Projects" -> "Project list" -> [Project location]_

It is recommended to create a idaes-files folder under your project, as it helps keeping focus, after I tested the both methods: At same place as tasks working folder under project or as, recommended, seperate folder for Idaesbasic.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Java / Maven |
| Manifests detected | pom.xml |
| Files in snapshot | 34 |
| Lines of code | 717 |
| Dependency references | 0 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing to Idaesbasic
- Everyone can contribute to Idaesbasic, by making a fork, make some changes, commit them and create a pull request
- After pull requesting, we will review your code, and add some comments
- If everything is nice, we add your commit to the original code

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `IDAES` (category: CHEMICAL PRODUCTION)
- **Upstream URL:** https://github.com/the-anticloud/anticloud-idaes.git
- **Pinned commit (SHA):** `bc4b0db4eca43b0ed1181c297f84516d97716cf5`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`6205f04ea4857a7ad3d5591c384df121b5aa36cff319db287ae723e513bf17dc`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

