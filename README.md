## Stracture
- base branch is the main source. Which contains all necessary info of the source.
- From base branch create branches for different languages, such as zh-Hant, zh-Hans. These branches accept changes from other sources.
- Set the language of the base branch as the default branch.
- If a change should apply to the base branch, apply there and then merge to the main branch.

## Todo
### Issues
- [ ] `se clean` remove double space in .svg to one, `&#x20;` won't work.

### Lint
- [ ] Check and correct "hidden" text also such as image alt.

### Style
- [ ] Evaluate different Chinese fonts for images and text.

### Convert
- [ ] Convert between repo zh-Hant and zh-Hans automatically.
- [ ] Evaluate different types of converter in OpenCC: HK, TW, etc.

### Build
- [ ] Add build-images to workflow.

### Documents
- [ ] Add standards
- [ ] Add visualization on relations between versions/languages.
