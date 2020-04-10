# madamira_tests

Selected texts converted into JSON for texts with MADAMIRA.

1. texts are broken down into sections
  2. `KEY` :: section ID (RE: `\$\d{5}\$`)
  3. `VALUE` :: text (as it appears in the original file)
2. Two additional "variables":
  1. `"HEAD"` :: inculdes the metadata header from the original text
  2. `"INDEX"` :: includes IDs of all sections in the order they appear in the text; **NOTE:** :: JSON file preserves the original order of sections; `INDEX` has been generated as a precaution.
