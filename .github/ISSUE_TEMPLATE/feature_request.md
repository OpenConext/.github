---
name: New feature
about: Suggest an idea for this project
title: ''
labels: ['needs refinement']
assignees: ''

---

# New Feature Request

## Summary

**Problem:** What is the pain point? (e.g., "Users cannot filter results by date.")

**Value:** Why should we build this? (e.g., "Improves data accessibility for
power users.")

## Proposed Solution

- **Action:** Describe the logic or flow change.
- **Design:** [Link to Figma/Screenshots]
- **Impact:** Does this affect existing APIs or UI components?

## Developer Checklist

*To be completed by the developer during implementation.*

- [ ] Add required changes and feature flags config files
- [ ] Create and document database changes and migrations
- [ ] Create and document API changes and migrations
- [ ] check for backwards compatibility
- [ ] Updated CHANGELOG and other documentation where needed

## Testing and QA

*Describe how to verify and test this change.*

### Test Environment and Setup

1. Point to [URL/Branch]
2. Use account with [Role/Permissions]

### Test Checklist

- [ ] Happy Path: Feature works as intended under normal conditions.
- [ ] Edge Case: [Describe specific test item]
- [ ] Validation: [Describe specific test item]
- [ ] UI/UX: Verified layout across screen sizes.

## Extra Information

Add any other context, related issues, or technical notes here.

### Defenition of Done
- [ ] Code Review & Merge: De Developer (Dev) heeft een Pull Request (PR) aangemaakt, deze is goedgekeurd door een andere Dev of de Technisch Product Manager (TPM), en de code is gemerged naar main.
- [ ] Testversie Gebouwd: De Developer heeft een werkende -SNAPSHOT versie van de betrokken applicatie(s) gebouwd.
- [ ] Installatie op Testomgeving: De -SNAPSHOT versie is geïnstalleerd op de interne testomgeving door de Dev of de TPM.
- [ ] Functionele Validatie: De Product Manager (PM) en/of de TPM heeft de functionaliteit getest en gevalideerd op de interne testomgeving.
- [ ] Changelog Bijgewerkt: De CHANGELOG in de relevante GitHub-repository('s) is bijgewerkt met de wijzigingen.
- [ ] Issue Koppeling: Het GitHub Issue bevat een link naar de relevante Pull Request(s) of commit(s).
- [ ] Afsluiting: Het GitHub Issue is gesloten en verplaatst naar de 'Delivered' kolom.
