# Sunagawa-miTAG-annotations

The taxonomic affiliations for the miTAGS contained in the Sunagawa et al (2015) dataset (http://ocean-microbiome.embl.de/companion.html) are difficult to interpret ecologically. The full taxonomy strings are too long to easily understand at a glance, and parsing by taxonomic level is not a good option since taxa vary widely in the depth of their annotations. For example, cyanobacteria should be annotated at the genus level or higher but many other abundant but less described taxa do not have any taxonomic information at that level. To overcome this, I've done some manual curation to provide a short taxonomic identifier that can be used to provide an indicator of the rough ecological niche of an organism while remaining short enough to be interpreted at a glance.

If you find it useful to your work, you can just cite this github repository (McNichol, J. 2020. Sunagawa miTAG annotations. github.com/jcmcnch/Sunagawa-miTAG-annotations/).

Notes:
* MG = Marine Group (to shorten names)
* Some taxonomies were altered to stick with updated SILVA taxonomy (i.e. *Betaproteobacteria* is now *Burkholderiales*)
* New SILVA 138 taxonomies were used wherever possible (i.e. the ID indicated in Sunagawa was still in SILVA 138 and could be grepped out), but in cases where there was only the SILVA 108 taxonomic information I made my best guess. For example, if something had the exact same classification in SILVA 108, I often called it the same thing as its counterparts in SILVA 138.
* In general, these taxonomic classifications are biased by my own personal knowledge about which group is meaningful to me and I made some assumptions (i.e. "SAR11 Surface 1" is equivalent to "SAR11 clade I")
* Let me know if you see anything that can be improved
