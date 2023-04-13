# NLM-aspace-profiles-MODS-export

Profiles in Science Digital Object MODS export

- a plugin developed in-house for Staff UI to export MODS records that pulls in non-standard fields specific to Profiles Digital Object records
Rights/Acts Notes
- overrides ALL MODS digital object exports, eg., Export→MODS pull down menu in SUI
  - consider refactoring to separate it out from default MODS export
  - consider refactoring Profiles metadata mappings - most of what is desired could be accomplished through standard descriptive metadata fields 
  - Rights/Acts not meant to be public-facing metadata, but internal administrative metadata
