# Grade 7 Canvas Processing Tracker

This file records the latest Canvas material incorporated into the subject notes. Before each future import, compare the requested module and week with this tracker and the local `canvas-download-manifest.json` file.

## Latest Completed Coverage

| Subject | Latest completed unit | Latest Canvas week processed | Notes destination | Status |
|---|---|---|---|---|
| Maths | Unit 2 | Week of 9/07 to 9/11 | `Maths/Unit2Notes.md` | Current through the listed week |
| Science | Unit 1 Ecology Part 2 | Week of 9/28 to 10/02 | `Science/Ecology-Part-2.md` | Current through Notebook Page 27 and dated material through 10/02 |
| SocialStudy | Not recorded | Not recorded | `SocialStudy/MasterNotes.md` | Review later |

## Maths Processing History

### Unit 1

- **Week of 8/31 to 9/04:** Completed before this tracker was created, as confirmed by the user. Existing notes remain in `Maths/MasterNotes.md`.

### Unit 2

- **Week of 8/31 to 9/04:** Processed `Unit 2 Simplify Algebraic Expressions.pdf`.
- **Week of 9/07 to 9/11:** Processed:
  - `Unit 2 Distributive Property.pdf`
  - `Unit 2 Factor Linear Expressions.pdf`
  - `Unit 2 Add Linear Expressions.pdf`
  - `Unit 2 Subtract Linear Expressions-1.pdf`

### Maths Local Folder Convention

- Store all Maths materials under `/Users/ketansolanki/Desktop/Hridhaan-7-Grade/Math`; do not use a separate `Canvas-Downloads` folder.
- Store teacher material as `Math/Unit-<number>/YYYY-MM-DD_to_MM-DD/`.
- If a Canvas week crosses a unit boundary, use the same dated folder under both affected unit folders and classify each file by unit.
- Store generated or supplemental worksheets under the applicable `Extra-Practice/` folder.
- Store durable historical manifests under `Math/Import-History/`.
- Deduplicate recursively using Canvas file IDs and SHA-256 hashes before final placement. Keep one canonical copy of byte-identical content; preserve differing revisions with a dated revision suffix.

### Organization Maintenance — 2026-10-08

- Moved all Maths files from the former `Canvas-Downloads/Maths` tree into `Math/Unit-1` and `Math/Unit-2`.
- Renamed the existing Unit 1 weekly folders to ISO ranges from `2026-08-03_to_08-07` through `2026-08-24_to_08-28`.
- Split the existing Unit 2 files into `2026-08-31_to_09-04` and `2026-09-07_to_09-11` according to their Canvas sections.
- Moved supplemental worksheets into the applicable unit's `Extra-Practice` folder and preserved the historical Unit 2 download manifest in `Math/Import-History`.
- Removed one byte-identical duplicate of `Unit 1 Terminating and Repeating Decimals.pdf`; retained the earliest canonical copy under `2026-08-03_to_08-07`.
- Verified all 40 remaining Maths files: zero byte-identical duplicate groups remain.

## Science Processing History

### Unit 1 Ecology Part 1

- **Previous Notebook cutoff:** Completed through `Page 18`, as confirmed by the user. The local files are stored under `Science/Ecology/Week4`.
- **Bridge material reviewed:** `Carrying Capacity and Limiting Factors.pptx` and the Part 1 study-guide material were used to connect population limits to Part 2.

### Unit 1 Ecology Part 2

- **Notebook — Week 5:** Processed every numbered notebook file after Page 18 through `Page 26 Energy Pyramid Practice.pdf`:
  - `Page 19 Carrying Capacity and Limiting Factors.pdf`
  - `Page 20 Quiz #2 Reflection.pdf`
  - `Page 21 Unit 1 Part 1 Study Guide.pdf`
  - `Page 22 Unit 1 Ecology Part 2 Cover Page.pdf`
  - `Page 23 Roles of Organisms in Ecosystem.pdf`
  - `Page 24 Food Chain and Food Web.pdf`
  - `Page 25 Energy Pyramid.pdf`
  - `Page 26 Energy Pyramid Practice.pdf`
- **Week of 9/07 to 9/11:** Processed the dated Canvas module material:
  - `9-8.pptx`
  - `Producer, Consumer, and Decomposer.pptx`
  - `9-9.pptx`
  - `Food Chain and Food Web.pptx`
  - `9-10.pptx`
  - `Energy Pyramid Doodle Notes.pdf`
  - `energy pyramid slide show tpt.pptx`
  - `9-11.pptx`
  - `The Lion King Student Print Version.pdf`
- **Notebook — Week of 9/14 to 9/18:** Processed `Page 27 Biomes.pdf`.
- **Week of 9/14 to 9/18:** Processed:
  - `The Lion King Activity KEY.pdf`
  - `9-15.pptx`
  - `Biomes.pptx`
  - `9-16.pptx`
  - `Biomes Worksheet.docx`
  - `Biomes Worksheet Rubric.docx`
  - `9-17.pptx`
  - `9-18.pptx`
  - `Biome Comparison _ Graphic Organizer Worksheet.docx`
  - `Biome Comparison _ Rubric.docx`
- **Week of 9/28 to 10/02:** Processed:
  - `9-28.pptx`
  - `9-29.pptx`
  - `Unit 1 Ecology Part 2 Energy Flow and Biomes Study Guide.docx`
  - `Unit 1 Ecology Part 2 Energy Flow and Biomes Study Guide KEY.docx`
  - `9-30.pptx`
  - `Unit1 Part 2 Review.pptx`
  - `10-1.pptx`
  - `10-2.pptx`

**Next Science starting points:**

- In the Canvas **Notebook** section, begin with the first item after `Page 27 Biomes.pdf`.
- In **Unit 1 Ecology Part 2**, begin with the first dated section after `10/02`.
- Latest local source folders: `Science/Ecology/2026-09-14_to_09-18` and `Science/Ecology/2026-09-28_to_10-02`, with Canvas streams kept in separate subfolders.
- Notes destination: `Science/Ecology-Part-2.md` on GitHub; local mirror: `Science/Ecology/Ecology-Part-2.md`.

### Science Local Folder Convention

- Store each import under `Science/Ecology/YYYY-MM-DD_to_MM-DD/`.
- Within each dated week, keep Canvas streams separate as `Notebook/` and `Unit-<name>/`.
- Keep that week's `canvas-download-manifest.json` at the dated-week root.
- Use `Science/_Incoming/<stream>/` only as temporary staging; compare file IDs and SHA-256 hashes recursively before moving sources into a dated week.
- Never use Canvas module position (`--latest`) as a substitute for a week. Science unit modules contain multiple weeks. Select each tracker-recorded module explicitly and start after its recorded item cutoff.

### Organization Maintenance — 2026-09-30

- Normalized older Science sources into ISO-dated week folders covering `2026-08-03` through `2026-09-11`.
- Removed 38 byte-identical duplicates created by an accidental positional download of the complete `Unit 1 Ecology Part 1` and `Unit 0 Basic Science` modules.
- Preserved 20 locally missing historical files in their correct dated folders.
- Preserved the differing Canvas copy of `Variables.pdf` as `Variables (Canvas revision 2026-09-30).pdf` rather than overwriting the existing file.
- Saved the accidental download manifest as `Science/Import-History/2026-09-30-positional-module-import.json` for auditability.
- No Canvas cutoff was advanced because this maintenance run did not retrieve material after the recorded Science cutoffs.

## Tracking Rules for Future Imports

1. Read this tracker before downloading new material.
2. Select only modules or weeks later than the latest completed coverage unless the user requests a recheck.
3. Use Canvas file IDs and SHA-256 hashes in the local download manifest to detect exact duplicates.
4. After notes are updated and verified on GitHub, update the subject row and append the processed week and filenames here.
5. Do not mark a week complete if any potentially important source could not be downloaded or read.

Last updated: 2026-10-08
