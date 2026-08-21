# Homepage Publication Update Design

## Goal

Update the homepage to announce three newly accepted papers and list them in the 2026 publications section while preserving the existing Jekyll markup and visual style.

## Scope

Only `_pages/about.md` will be changed during implementation. The separate legacy publications page, site styles, navigation, and assets are out of scope.

## News

Add two entries at the top of the existing scrollable news list, in reverse chronological order:

1. `2026.08: 2 papers accepted by EMNLP 2026`
2. `2026.07: 1 paper accepted by Journal of Computer Research and Development (in Chinese)`

## Publications

Add three individual entries to the top of the 2026 publication list:

1. **Mitigating Overthinking via Interleaved System-1/2 Reasoning in Large Language Models**
   - Authors: Han Ding, **Wei Chen**, Fuzhen Zhuang
   - Venue: Conference on Empirical Methods in Natural Language Processing (**EMNLP 2026**)

2. **Structure Matters: Semantic-Structural Dual-Path Arbitration Named Entity Recognition with LLMs**
   - Authors: Xinghong Hou, Yiqi Tong, **Wei Chen**, Wei Guo, Fuzhen Zhuang
   - Venue: Findings of the Association for Computational Linguistics: EMNLP 2026 (**EMNLP 2026 Findings**)

3. **Multi-view Enhanced Graph Attention Network for Multimodal Knowledge Graph Completion**
   - Authors: **Wei Chen**, Fuzhen Zhuang
   - Venue: *Journal of Computer Research and Development (in Chinese)*, 2026

The two EMNLP papers will appear before the July journal paper because the August acceptances are newer. Each paper will use the homepage's existing `publication-title`, `publication-authors`, and `publication-venue` markup. Wei Chen's name will be bold. No paper or code links will be shown because no public URLs were supplied for these three papers.

## Verification

Run the repository's available Jekyll build or equivalent local validation, then inspect the generated homepage markup to confirm:

- both news entries are present and ordered correctly;
- all three publication entries appear in the 2026 section;
- titles, author order, venue labels, emphasis, and HTML structure are correct;
- no unrelated tracked files are changed.
