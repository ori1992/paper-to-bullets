---
name: paper-to-bullets
description: "Turn a research paper into five bullets: title, question, method, result, limitation. Use whenever the user shares a paper, article or abstract (a .txt, .pdf or pasted text) or asks to triage, skim, summarise or 'tl;dr' one, even if they don't say 'bullets'."
---
Read the paper the user names (or the text they paste) and output exactly five bullets, in this order:

- **Title**: the paper's title and, if present, the authors and year.
- **Question**: the research question the paper asks.
- **Method**: how the paper answers it, in one line.
- **Result**: the main finding, with the key number if there is one.
- **Limitation**: the main limitation the paper states or that the method implies.

The point is a quick triage: can the reader tell in ten seconds whether this paper is worth reading in full? So keep each bullet to one short line and use plain language. Keep the paper's key numbers, but drop jargon a non-specialist would not follow.

Nothing before or after the five bullets. Use only what is in the paper. If an item is missing, write "not stated", so the reader can see the gap instead of reading a guess. For **Limitation**, if the paper names none but one clearly follows from the method (for example, only one sample or one material was tested), you may give it, starting with "Implied:".

If the user gives several papers, write one block of five bullets per paper, each under the paper's file name as a heading.
