# The Wiener Holocaust Library

[![See on the EHRI Portal](https://img.shields.io/badge/See_on-the_EHRI_Portal-83004c)](https://portal.ehri-project.eu/institutions/gb-003348)

The Wiener library offers an API where it is possible to download the contents in a own XML model.

1. Create a dataset using the URLSet harvesting option. Paste the elements contained in the collectionsURLSet.tsv file. It is possible that a header containing the token for the API is required.
2. Add the following ECT transformation:
    1. soutron_to_ead.tsv
3. Convert the files and ingest them with no further options.