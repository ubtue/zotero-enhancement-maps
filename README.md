# zotero-enhancement-maps

Files in this repository are meant to be used by ub_tools + zotkat repositories. It is needed to give ub_tools and zotkat developers write access to the same files.

## Special-Cases
The following files are generated automatically on a nightly basis by importing data from Zeder. They __MUST NOT__ be editted manually - Manual changes will automatically be overwritten. Changes must be made
directly to the journal's entry in Zeder.

* ISSN_to_SSG.map - Imported from Zeder column `ber`. Currently only generated for IxTheo/RelBib. KrimDok entries need to be manually updated in Zeder before they can be imported.
