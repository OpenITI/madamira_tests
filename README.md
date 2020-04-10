# Classical Arabic Texts for MADAMIRA Tests

Selected texts converted into JSON for texts with MADAMIRA.

1. texts are broken down into sections
  - `KEY` :: section ID (RE: `\$\d{5}\$`)
  - `VALUE` :: text (as it appears in the original file)
2. Two additional "variables":
  - `"HEAD"` :: inculdes the metadata header from the original text
  - `"INDEX"` :: includes IDs of all sections in the order they appear in the text; **NOTE:** :: JSON file preserves the original order of sections; `INDEX` has been generated as a precaution.

# Repository Structure

All texts (preserve their original URIs + `.json`) are stored in the `data` subfolder.

# List of texts

- `0748Dhahabi.TarikhIslam.MGR20180917-ara1.mARkdownSimple.json`