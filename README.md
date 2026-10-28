# FSAE Rules 2027 — Markdown Edition

All of the Formula SAE 2027 rules and supplementary documents converted to Markdown (`.md`), faithful to the originals, so that AIs, search tools and programs can read them easily.

> **Unofficial repository.** The content belongs to SAE International. The official documents prevail; always check the current version at <https://www.fsaeonline.com/cdsweb/gen/documentresources.aspx>.

## Document versions

Read from the documents themselves:

| Document | Version |
|---|---|
| Formula SAE® Rules 2027 | Version 1.0, 1 Sept 2026 |
| Formula SAE® Driverless Supplement 2027 | Version 1.0, 7 Oct 2026 |
| Formula SAE Driverless Implementation Roadmap | Revised August 5, 2026 (file name `rev8.5.2026`; the cover-page footer of the PDF says "Dec 3, 2024") |

## Purpose

The PDFs, Word documents and spreadsheets published for Formula SAE are hard for AIs and programs to read reliably: tables break, text is split across columns and figures interrupt the text. This repository provides the same content as clean Markdown:

- **Text is verbatim.** Every word was extracted by code from the original files and verified against them. Nothing was retyped, summarised, corrected or translated, and original typos are kept.
- **Structure is preserved.** Rule numbers are headings or bold, tables are Markdown/HTML tables, and formulas are code blocks.
- **Figures are kept.** They are images in `assets/` folders, placed where they occur in the text.

## How to use

### Pointing an AI at the right file

Each rule prefix lives in one file. To look up a rule, open the file for its prefix. For example, **EV.4.1** → `FSAE_Rules_2027_V1/EV - Electric Vehicles.md`, and **DT.3.1.2** → `FSAE_Driverless_2027_V1/DT - Driverless Technical.md`.

| Prefix | Section | File |
|---|---|---|
| `GR` | General Regulations | [`FSAE_Rules_2027_V1/GR - General Regulations.md`](FSAE_Rules_2027_V1/GR%20-%20General%20Regulations.md) |
| `AD` | Administrative Regulations | [`FSAE_Rules_2027_V1/AD - Administrative Regulations.md`](FSAE_Rules_2027_V1/AD%20-%20Administrative%20Regulations.md) |
| `PS` | Pre-Competition Submissions | [`FSAE_Rules_2027_V1/PS - Pre-Competition Submissions.md`](FSAE_Rules_2027_V1/PS%20-%20Pre-Competition%20Submissions.md) |
| `V` | Vehicle Requirements | [`FSAE_Rules_2027_V1/V - Vehicle Requirements.md`](FSAE_Rules_2027_V1/V%20-%20Vehicle%20Requirements.md) |
| `F` | Chassis and Structural | [`FSAE_Rules_2027_V1/F - Chassis and Structural.md`](FSAE_Rules_2027_V1/F%20-%20Chassis%20and%20Structural.md) |
| `T` | Technical Aspects | [`FSAE_Rules_2027_V1/T - Technical Aspects.md`](FSAE_Rules_2027_V1/T%20-%20Technical%20Aspects.md) |
| `VE` | Vehicle and Driver Equipment | [`FSAE_Rules_2027_V1/VE - Vehicle and Driver Equipment.md`](FSAE_Rules_2027_V1/VE%20-%20Vehicle%20and%20Driver%20Equipment.md) |
| `IC` | Internal Combustion Engine Vehicles | [`FSAE_Rules_2027_V1/IC - Internal Combustion Engine Vehicles.md`](FSAE_Rules_2027_V1/IC%20-%20Internal%20Combustion%20Engine%20Vehicles.md) |
| `EV` | Electric Vehicles | [`FSAE_Rules_2027_V1/EV - Electric Vehicles.md`](FSAE_Rules_2027_V1/EV%20-%20Electric%20Vehicles.md) |
| `IN` | Technical Inspection | [`FSAE_Rules_2027_V1/IN - Technical Inspection.md`](FSAE_Rules_2027_V1/IN%20-%20Technical%20Inspection.md) |
| `S` | Static Events | [`FSAE_Rules_2027_V1/S - Static Events.md`](FSAE_Rules_2027_V1/S%20-%20Static%20Events.md) |
| `D` | Dynamic Events | [`FSAE_Rules_2027_V1/D - Dynamic Events.md`](FSAE_Rules_2027_V1/D%20-%20Dynamic%20Events.md) |
| `DA` | Driverless Administrative | [`FSAE_Driverless_2027_V1/DA - Driverless Administrative.md`](FSAE_Driverless_2027_V1/DA%20-%20Driverless%20Administrative.md) |
| `DT` | Driverless Technical | [`FSAE_Driverless_2027_V1/DT - Driverless Technical.md`](FSAE_Driverless_2027_V1/DT%20-%20Driverless%20Technical.md) |
| `DO` | Driverless Operations | [`FSAE_Driverless_2027_V1/DO - Driverless Operations.md`](FSAE_Driverless_2027_V1/DO%20-%20Driverless%20Operations.md) |
| `DI` | Driverless Inspection | [`FSAE_Driverless_2027_V1/DI - Driverless Inspection.md`](FSAE_Driverless_2027_V1/DI%20-%20Driverless%20Inspection.md) |
| `DS` | Driverless Static | [`FSAE_Driverless_2027_V1/DS - Driverless Static.md`](FSAE_Driverless_2027_V1/DS%20-%20Driverless%20Static.md) |
| `DD` | Driverless Dynamic | [`FSAE_Driverless_2027_V1/DD - Driverless Dynamic.md`](FSAE_Driverless_2027_V1/DD%20-%20Driverless%20Dynamic.md) |

The cover, table of contents and revision information of each document are in `00 - Front Matter.md` in the same folder.

Example instructions for an AI: *"Read `FSAE_Rules_2027_V1/EV - Electric Vehicles.md` and tell me what EV.5.7.3 requires. Quote the rule number."*

### Citing rules

Cite the rule number exactly as it appears (e.g. `EV.5.7.3`), and the document and version when it matters, e.g. *Formula SAE Rules 2027 V1.0, EV.5.7.3*. Inside the files:

- section titles are `#` headings (`# EV - ELECTRIC VEHICLES`);
- numbered rule titles are `##`/`###`/`####` headings by depth (`## EV.5`, `### EV.5.7`);
- rules with text start with the number in bold (`**EV.5.7.3** …`).

Searching for the bold number finds the rule.

### Driverless Supplement

The Driverless Supplement is **Incorporated by Reference** into the Rules. Its front matter states: "Per Formula SAE Rules GR.4.2.3, this Supplement is Incorporated by Reference into the Formula SAE…". GR.4.2.3 gives incorporated documents the same validity as the Formula SAE Rules. Driverless questions therefore need both folders.

## Repository structure

Every `.md` file has the same base name as its original. Files marked *[original file, kept untouched]* are templates, forms, CAD models and technical drawings; they are included exactly as published and are not transcribed.

```
FSAE_RULES_2027/
├── Cost Event Resources/  # Cost and Manufacturing Event: Cost Supplement, module guide, catalog changelog, Q&A
│   ├── Templates/  # Cost report templates (original files)
│   │   ├── Cost Addendum Template_v.2.xlsx  [original file, kept untouched]
│   │   └── FSAE_Cost_eBOM_Template.xls  [original file, kept untouched]
│   ├── 2022_FSAE_Cost_Module_Guide_.md
│   ├── 2026_FSAE_Integrated_Presentation_Concept_and_Cost_Scenario_Virtual_Mtg_Q&A_12.3.25.md
│   ├── Check_Cost_Report_Tool.md
│   ├── Cost Catalog Changelog.md
│   └── FSAE_Cost_Supplement_V4.md
├── Design Events Resources/  # Design Event resources
│   ├── EV - Electric Vehicle/  # EV and Driverless design score sheets
│   │   ├── FSAE Design Score Sheet_EV.md
│   │   └── FSAE_Driverless_Design_ScoreSheet_v1.md
│   ├── IC - Internal Combustion Vehicle/  # IC design score sheet
│   │   └── FSAE Design Score Sheet_IC.md
│   └── Reference Documents/  # Design reference papers (anthropometrics, cockpit forces, fasteners, three-view drawings)
│       ├── Anthropometric Reference Data.md
│       ├── Carroll Smith FSAE Design Paper.md
│       ├── Cockpit Control Forces.md
│       ├── Formula SAE Design Overview Presentation.md
│       ├── Threaded Fasteners for FSAE.md
│       └── Three View Drawing Excellence Criteria.md
├── FSAE_Driverless_2027_V1/  # Formula SAE Driverless Supplement 2027, split by section
│   ├── 00 - Front Matter.md
│   ├── DA - Driverless Administrative.md
│   ├── DD - Driverless Dynamic.md
│   ├── DI - Driverless Inspection.md
│   ├── DO - Driverless Operations.md
│   ├── DS - Driverless Static.md
│   ├── DT - Driverless Technical.md
│   └── Formula_SAE_Driverless_Implementation_Roadmap_rev8.5.2026.md
├── FSAE_Rules_2027_V1/  # Formula SAE Rules 2027, split by section
│   ├── 00 - Front Matter.md
│   ├── AD - Administrative Regulations.md
│   ├── D - Dynamic Events.md
│   ├── EV - Electric Vehicles.md
│   ├── F - Chassis and Structural.md
│   ├── GR - General Regulations.md
│   ├── IC - Internal Combustion Engine Vehicles.md
│   ├── IN - Technical Inspection.md
│   ├── PS - Pre-Competition Submissions.md
│   ├── S - Static Events.md
│   ├── T - Technical Aspects.md
│   ├── V - Vehicle Requirements.md
│   └── VE - Vehicle and Driver Equipment.md
├── Presentation Event Resources/  # Presentation Event concept, FAQ and meeting recording link
│   ├── 2027 Formula SAE - Presentation Concept.md
│   ├── Integrated Concept & Cost Team Guidance FAQ from Nov-24-2025.md
│   └── Integrated Presentation Concept and Cost Scenario Virtual Meeting Recording Nov-24-2025.md
├── Rules References/  # Documents referenced by the Rules (CDS standards, transponders, QuickJack, fuels, noise test speeds)
│   ├── CDS_standards_as_of_2.2024_published_online_(1).md
│   ├── FSAE_Transponder_Approved_List_V2.md
│   ├── fsaequickjack.md
│   ├── Fuels_2020.md
│   └── Noise Test Speeds 2015.md
├── Technical Inspection Resources/  # Technical Inspection resources
│   ├── Driverless Resources and Templates/  # Driverless forms (original files)
│   │   ├── Driverless Notice of Intent.docx  [original file, kept untouched]
│   │   └── Driverless System Office (DSO) Form.docx  [original file, kept untouched]
│   ├── EV - Electric Vehicle/  # Electric vehicle inspection resources
│   │   ├── Energy Meter Resources/  # Energy Meter manual and receptacle ordering
│   │   │   ├── EM_User_Manual_2026.md
│   │   │   └── Ordering an Energy Meter Receptacle.md
│   │   ├── EV Templates/  # EV forms and templates (original files)
│   │   │   ├── 2027 Electric Systems Form template.xlsx  [original file, kept untouched]
│   │   │   ├── Electrical_System_Advisor_and_Electrical_System_Officer_Form.docx  [original file, kept untouched]
│   │   │   └── Team Built RTM Testing Results Submission Template.xlsx  [original file, kept untouched]
│   │   ├── Onsite Resources/  # Charging and PACCAR discharge requirements
│   │   │   ├── EV_Charging_Requirements.md
│   │   │   ├── PACCAR Battery Discharge Harness.md
│   │   │   └── PACCAR Discharge Station Requirements.md
│   │   ├── Reference Files/  # EV safety resources, accumulator video, fusible link testing, rain test drawing
│   │   │   ├── Electric Vehicle Safety Resources.md
│   │   │   ├── FSAE Electric Pre-Competition Accumulator Video Example.md
│   │   │   ├── Fusible Link Testing Guidelines.md
│   │   │   └── Rain Test Drawing.pdf  [original file, kept untouched]
│   │   ├── Republic Services/  # Battery waste disposal (Republic Services / US Ecology) documents
│   │   │   ├── Republic Services - Customer On-boarding form.md
│   │   │   ├── Republic Services - Emergency Response Solutions.md
│   │   │   ├── Republic Services - Environmental Service Agreement.md
│   │   │   ├── Republic Services - Waste Material Profile form.md
│   │   │   └── Republic Services.md
│   │   └── Submission Guidelines for Use of Team Built Ready to Move (RTM) Indicator.md
│   ├── IC - Internal Combustion Vehicle/  # IC forms and templates (original files)
│   │   ├── FSAE Electronic Throttle Control - Notice of Intent.docx  [original file, kept untouched]
│   │   └── Fuel Order Template.xlsx  [original file, kept untouched]
│   ├── SES Templates/  # Structural Equivalency Spreadsheets (original files)
│   │   ├── 2027 FSAE Structural Equivalency Spreadsheet_Steel-Tube.xlsx  [original file, kept untouched]
│   │   └── 2027 FSAE-Structural-Equivalency_Monocoque-Hybrid-Aluminum.xlsx  [original file, kept untouched]
│   └── Tech Insp References/  # RFID tag mounting, honeycomb impact attenuator data, standard IA drawings and CAD
│       ├── How to Mount RFID Tags.md
│       ├── Plascore for the honeycomb IA construction.md
│       ├── Standard Foam Impact Attenuator 2D CAD File.pdf  [original file, kept untouched]
│       ├── Standard Foam Impact Attenuator 3D CAD File.x_t  [original file, kept untouched]
│       └── Standard Honeycomb Impact Attenuator 2D Drawing.pdf  [original file, kept untouched]
├── Unofficial Resources/  # Third-party material (not published by SAE International)
│   ├── FSAE_Recommended_Books.md
│   ├── Organizing a Formula SAE by Alan Gruner.md
│   └── SAE Student Management by Richard G. Golembiewski.md
└── README.md
```

Figures are in an `assets/` folder next to each document, in `assets/<document name>/`:

- `Cost Event Resources/assets/` — 25 images
- `Design Events Resources/EV - Electric Vehicle/assets/` — 2 images
- `Design Events Resources/IC - Internal Combustion Vehicle/assets/` — 1 images
- `Design Events Resources/Reference Documents/assets/` — 54 images
- `FSAE_Driverless_2027_V1/assets/` — 7 images
- `FSAE_Rules_2027_V1/assets/` — 42 images
- `Presentation Event Resources/assets/` — 2 images
- `Rules References/assets/` — 8 images
- `Technical Inspection Resources/EV - Electric Vehicle/assets/` — 4 images
- `Technical Inspection Resources/EV - Electric Vehicle/Energy Meter Resources/assets/` — 18 images
- `Technical Inspection Resources/EV - Electric Vehicle/Onsite Resources/assets/` — 2 images
- `Technical Inspection Resources/EV - Electric Vehicle/Reference Files/assets/` — 1 images
- `Technical Inspection Resources/EV - Electric Vehicle/Republic Services/assets/` — 24 images
- `Technical Inspection Resources/Tech Insp References/assets/` — 10 images

## Conversion notes

### Method

| Source type | Extraction |
|---|---|
| PDF | Text from the PDF text layer with PyMuPDF, cross-checked against `pdftotext` (poppler) |
| Formula layouts | `pdftotext -layout`, placed in fenced code blocks |
| DOCX | Read from the document XML with python-docx |
| DOC | Converted to DOCX with LibreOffice (headless), then read the same way |
| XLSX | openpyxl; values as displayed (number formats, cached formula results) |
| TXT | Copied verbatim |

The conversion scripts only *structure* the extracted text. The only changes made to the text are:

- removal of running headers, footers and page numbers;
- rejoining of lines wrapped inside paragraphs and of words hyphenated across lines;
- Markdown syntax, with escaping so that the rendered text equals the source;
- ligature glyphs (ﬁ, ﬂ, broken "ti"/"tt" ligatures) written as plain letters.

### Headers, footers and decorations removed

- **Rules:**
  - footers "Formula SAE® Rules 2027 © 2026 SAE International Page X of 147" and "Version 1.0 1 Sept 2026"
  - the SAE International logo at the top of every page
- **Driverless Supplement:**
  - header "Formula SAE® Driverless Supplement 2027"
  - footer "Version 1.0 7 Oct 2026 © 2026 SAE International Page X of 19"
  - the SAE logo at the top right of every page
- **Roadmap:**
  - cover footer "Dec 3, 2024 … Page 1 of 8"
  - footer "Formula SAE Driverless Roadmap – revised August 5, 2026 … Page X of 8"
- **Cost Supplement:**
  - header "Formula SAE® Cost Event Supplement"
  - footer "Version 4.0 15 Mar 2026 © 2026 SAE International Page X of 19"
  - SAE logo
- **Cost Q&A, and the identical Presentation FAQ:** footer "Revision Dec 3, 2025 SAE International Page X of 19"
- **Cost Module Guide:**
  - "SAE INTERNATIONAL" logo text
  - copyright line on every slide
  - slide numbers
- **Design score sheets:** "Page X of 10" (EV and IC); "Page X of 8" (Driverless)
- **Cockpit Control Forces:** page numbers
- **Threaded Fasteners:** "Threaded Fastener Chapter" and "Michael Black – September 21, 2018"
- **Presentation Concept:** "Formula SAE 2027 © 2026 SAE International Page X|8"
- **QuickJack:** print header "Macintosh HD:FILES:PHOTOGRAPHS:motor sport:" and "Page X"
- **EM User Manual:** "…Formula SAE Electric – Energy Meter Student Manual Page X of 17"
- **Environmental Service Agreement:** header "Version 2024.1 03-01-24 USE" and page numbers
- **EV_Charging_Requirements:** header "EV Charging Requirements at Formula SAE Competitions" and "Page 1 of 1"
- **Waste Material Profile form:** "Revision Date: … pg. X"
- **SAE Student Management:** page numbers
- **Emergency Response Solutions** (brochure): text drawn twice at the same position (outline/shadow effect) is transcribed once

### Figures

- Raster images and vector drawings are cropped from the page and saved as PNG.
- Captions are kept as text and also used as the image's alt text. Figures without a caption are labelled "Figure on page N".
- Small labels inside diagrams (for example the shutdown circuit on Rules page 106) exist only in the image, because the PDFs' own text for them is corrupted ("Bu ons", "Insula on").
- Text of normal size printed over images is kept as text.

### Verification

Every file was checked by script:

1. The rendered Markdown's words were compared with the source's words: sequence and multiset. Files split from one PDF were also checked to be exact consecutive slices that together reproduce the whole document.
2. Rule IDs were compared in order with the source. The only extra source matches are cross-references that happen to start a printed line.
3. Word totals were checked: the 13 Rules files sum to the PDF total.
4. A second extractor was compared: `pdftotext`, or LibreOffice for Word files.
5. Pages, especially table-heavy ones, were rendered and compared visually.
6. Every image link was checked to resolve.

**Result:** most files reproduce the source word sequence exactly. The remaining files contain exactly the same words in a different order, or differ by a single explained token:

- **Order differs because of layout:**
  - **2-D formula layout** (formulas in code blocks): `D - Dynamic Events.md`, `FSAE_Cost_Supplement_V4.md`.
  - **The PDF stores text in a non-reading order** (columns, text boxes, diagrams): `Noise Test Speeds 2015.md`, `Fuels_2020.md`, `Threaded Fasteners for FSAE.md`, `Anthropometric Reference Data.md`, `EM_User_Manual_2026.md`, `PACCAR Battery Discharge Harness.md`, `Republic Services - Waste Material Profile form.md`, `Republic Services - Customer On-boarding form.md`.
- **Single tokens differ:**
  - `2027 Formula SAE - Presentation Concept.md`: "ROUND 2" (confirmed by `pdftotext`).
  - `PACCAR Discharge Station Requirements.md`: a symbol-font arrow (U+F0E0), kept verbatim before "Pin".
  - `Plascore for the honeycomb IA construction.md`: footnote marker "Stroke²".
  - `D - Dynamic Events.md`: Skidpad "²" split by the layout extraction.
  - `Republic Services - Emergency Response Solutions.md`: fragments of the duplicated outline text.
- **Ligature repairs:** in `Check_Cost_Report_Tool.md`, "Ɵ" → "ti" and "buton" → "button". The PDF text layer is broken there, and the page shows "Activity"/"button".

### Other notes

- **Identical files:** `Cost Event Resources/2026_FSAE_Integrated_Presentation_Concept_and_Cost_Scenario_Virtual_Mtg_Q&A_12.3.25.pdf` and `Presentation Event Resources/Integrated Concept & Cost Team Guidance FAQ from Nov-24-2025.pdf` are byte-identical. Both are converted.
- **Original numbering is kept**, including oddities; for example, the Driverless Supplement numbers two rules under DS.1.2 as "DI.1.2.1" and "DI.1.2.2".
- **Formatting not reproduced:**
  - Font colour in `Cost Catalog Changelog.md` cannot be shown in Markdown (red = change, green = add); strikethrough (remove) is kept as `<del>`.
  - Interactive form fields are not reproduced; values printed on the forms are transcribed.
- **Split documents:** the Rules sections each start on a new page. The Driverless sections start mid-page and were split exactly at the section headings.

## Disclaimer

This is an **unofficial** repository and is not affiliated with or endorsed by SAE International. All Formula SAE documents are the property of SAE International; the official source prevails and must be checked for the current version: <https://www.fsaeonline.com/cdsweb/gen/documentresources.aspx>. The **Unofficial Resources** folder contains third-party material that is not published by SAE International.

## Credits

- **Pedro Paulo Nogueira Mendonça** — Author. LinkedIn: <https://www.linkedin.com/in/pedro-paulo-nogueira-mendon%C3%A7a-866821219/>
- **Enrique Gil Borges** — Development support and contributor. LinkedIn: <https://www.linkedin.com/in/enrique-gil-borges-1b884a37a/>
- **Tadarida Electric Racing Team, Laboratório de Mobilidade Automobilística e Urbana (LAMAU)** (Automotive and Urban Mobility Laboratory) — Instagram: [@lamau.ufu](https://www.instagram.com/lamau.ufu/)

## Português (PT-BR)

### Objetivo

Este repositório reúne todas as regras da Formula SAE 2027 e os documentos complementares convertidos para Markdown (`.md`), fiéis aos originais, para facilitar o uso por IAs, ferramentas de busca e programas.

- **O texto é transcrito palavra por palavra.** Ele foi extraído por código dos arquivos originais e verificado contra eles. Nada foi redigitado, resumido, corrigido ou traduzido, e os erros de digitação originais foram mantidos.
- **A estrutura foi preservada.** Os números das regras são títulos ou negrito, as tabelas são tabelas Markdown/HTML e as fórmulas estão em blocos de código.
- **As figuras foram mantidas.** Ficam como imagens nas pastas `assets/`, no ponto em que aparecem no texto.

### Como usar

Cada prefixo de regra fica em um arquivo; use a tabela de prefixos acima. Por exemplo, **EV.4.1** → `FSAE_Rules_2027_V1/EV - Electric Vehicles.md` e **DT.3.1.2** → `FSAE_Driverless_2027_V1/DT - Driverless Technical.md`. Capa, sumário e informações de revisão ficam em `00 - Front Matter.md`.

Ao pedir algo a uma IA, indique o arquivo, por exemplo: *"Leia `FSAE_Rules_2027_V1/EV - Electric Vehicles.md` e diga o que a EV.5.7.3 exige, citando o número da regra."*

Para citar, use o número exatamente como aparece (por exemplo, *Formula SAE Rules 2027 V1.0, EV.5.7.3*). Nos arquivos, as regras com texto começam com o número em negrito (`**EV.5.7.3**`).

O Driverless Supplement é **incorporado por referência** às regras ("Per Formula SAE Rules GR.4.2.3, this Supplement is Incorporated by Reference…"), com a mesma validade das Formula SAE Rules. Para equipes driverless, as duas pastas valem.

### Estrutura

| Pasta | Conteúdo |
|---|---|
| `FSAE_Rules_2027_V1/` | Regras 2027 (V1.0, 1 Sept 2026) divididas por seção |
| `FSAE_Driverless_2027_V1/` | Driverless Supplement (V1.0, 7 Oct 2026) dividido por seção |
| `Formula_SAE_Driverless_Implementation_Roadmap_rev8.5.2026.md` | Roadmap do driverless (revisado em 5 de agosto de 2026) |
| `Cost Event Resources/` | Evento de Custo |
| `Design Events Resources/` | Evento de Design |
| `Presentation Event Resources/` | Evento de Apresentação |
| `Rules References/` | Documentos referenciados pelas regras |
| `Technical Inspection Resources/` | Inspeção técnica (EV, IC, driverless, SES, referências) |
| `Unofficial Resources/` | Material de terceiros |

Modelos, formulários, arquivos CAD e desenhos técnicos foram incluídos sem alteração (marcados como *original file, kept untouched* na árvore acima). As figuras ficam em `assets/<nome do documento>/`.

### Aviso

Este repositório é **não oficial** e não tem vínculo nem aprovação da SAE International. Todo o conteúdo pertence à SAE International. A fonte oficial prevalece, e a versão vigente deve sempre ser conferida em <https://www.fsaeonline.com/cdsweb/gen/documentresources.aspx>. A pasta **Unofficial Resources** contém material de terceiros, não publicado pela SAE International.

### Créditos

- **Pedro Paulo Nogueira Mendonça** — Autor. LinkedIn: <https://www.linkedin.com/in/pedro-paulo-nogueira-mendon%C3%A7a-866821219/>
- **Enrique Gil Borges** — Suporte ao desenvolvimento e colaborador. LinkedIn: <https://www.linkedin.com/in/enrique-gil-borges-1b884a37a/>
- **Tadarida Electric Racing Team, Laboratório de Mobilidade Automobilística e Urbana (LAMAU)** — Instagram: [@lamau.ufu](https://www.instagram.com/lamau.ufu/)
