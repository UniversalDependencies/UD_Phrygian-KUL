# Summary

UD Phrygian-KUL started as part of a Master's thesis in linguistics at KU Leuven, annotating the New Phrygian subcorpus of the ancient Phrygian language. It has since expanded to include Middle Phrygian texts.

# Introduction

UD Phrygian-KUL annotates the Middle and New Phrygian subcorpora of the ancient Phrygian language. The data are comprised of epigraphic material dating ca. 4th century BCE-3rd century CE following the editions by Obrador-Cursach (2020, pp. 525-606) and Oreshko and Alagöz (2023). Additional grammatical information is derived from Ligorio and Lubotsky (2018) and Oreshko (2023).

In case any rights were violated, please notify the contributors so that we can resolve the issue.

Since the data are epigraphic, the inscriptions can be linked to various metadata through stable identifiers provided by [Trismegistos](https://www.trismegistos.org/tm/index.php) (cf. Depauw & Gheldof, 2014). Each identifier thus represents an inscription, augmented by a number identifying the sentence and one for the token whenever applicable. These three elements are separated by a hyphen (-) and included in the MISC field. This way, there is little difficulty in finding the provenance and approximate date of every Phrygian inscription.

# Edition

The data are based mainly on the aforementioned editions. Some changes have been made, however, in order to keep up with new insights and to quell compatibility issues.

In their edition of G-12, Oreshko and Alagöz (2023) use ś to represent a modified s-sign of the Phrygian alphabet. This is, however, impractical for UD, as there is no single combined Unicode character for that combines an acute and underdot, which is necessary in order to comply with the Leiden Editorial Conventions. For this reason, these data deviate from the edition in that the original ś is replaced by a capital letter S. Considering there is no convention for the use of capital letters in Phrygian, this is a way to preserve the distinction in the G-12 inscription between the s-signs as well as to underdot them (Ṣ).

Some New Phrygian texts are emended following Hämmig (2022). As such, the verb forms ουελασκετου and ουελασκοννου appear in the corpus (lemma ουελασκετου).

# Lemmas

Most data in the LEMMA-field are compiled in Obrador-Cursach (2020, pp. 154–411)

# Acknowledgments

The data were annotated by Oggi Peeters as part of a Master's thesis in linguistics at KU Leuven (Peeters, 2024). Thus, it goes without saying that any errors are my own. A big thank-you goes to supervisors Alek Keersmaekers and Toon Van Hal for their guidance throughout the project, as well as to Mark Depauw for his help in acquiring the necessary textual metadata from Trismegistos.

# References

* Depauw, M., & Gheldof, T. (2014). Trismegistos. An interdisciplinary Platform for Ancient World Texts and Related Information. In Ł. Bolikowski, V. Casarosa, P. Goodale, N. Houssos, P. Manghi, J. Schirrwagen (Eds.), _Theory and Practice of Digital Libraries - TPDL 2013 Selected Workshops (Communications in Computer and Information Science 416)_, 40–52.
* Hämmig, A. E. (2022). A “new” Neo-Phrygian curse formula. In B. Obrador-Cursach & I.-X. Adiego (Eds.), _Phrygian linguistics and epigraphy: new insights_ (pp. 89–102). Universitat de Barcelona.
* Ligorio, O., & Lubotsky, A. (2018). Phrygian. In J. Klein, B. Joseph, & M. Fritz (Eds.), _Handbook of Comparative and Historical Indo-European Linguistics_, 1816–1831. De Gruyter Mouton.
* Obrador-Cursach, B. (2020). _The Phrygian Language_. Brill.
* Oreshko, R. (2023). Observations on the language of the newly discovered Phrygian inscription from Gordion (G-12). _Kadmos_, _62_(1/2), 53–94.
* Oreshko, R., Alagöz, U. (2023). A New Phrygian Inscription from Gordion: A Pergamene Contingent in Phrygia in the early Reign of Antiochus I. _Belleten_, _78_(310), 793–831.
* Peeters, O. (2024). _Fragments and Formula: An annotated corpus for the Phrygian language_ (0832354_57760851) [Master's thesis, KU Leuven]. Teneo. https://repository.teneo.libis.be/delivery/DeliveryManagerServlet?dps_pid=IE21049119&

# Changelog

* 2026-05-15 v2.18
  * Corrections in annotation
  * Fixed readability of TM-identifiers in MISC-field.
  * Middle Phrygian texts added (W-11, G-12).
  * README.md updated for expansion of the corpus.
* 2025-11-15 v2.17
  * Implementation of ExtPos.
  * Corrections in annotation.
* 2024-11-15 v2.15
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.15
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: nonfiction
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Peeters, Oggi
Contributing: here
Contact: oggi.peeters@student.kuleuven.be
===============================================================================
</pre>
