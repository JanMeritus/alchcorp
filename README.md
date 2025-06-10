# alchcorp
Medieval alchemical corpus metadata

## Content

Contains metadata for used texts in:

VOZÁR, Zdenko (2025). Alchymistické florilégiá: K digitálnej archeológii stredovekých textov a symbolov. Online. Doctoral theses, Dissertations. Brno: Masaryk University, Faculty of Arts. Available from: https://is.muni.cz/th/tanvq/?lang=en;vysl=21710;id=253414

VOZÁR, Zdenko (2025). Alchemy and Its Genres: Towards Quantitative Approaches to Medieval Latin Alchemical Texts. Teorie vědy Theory of Science. https://doi.org/10.46938/tv.2025.683


## Formatting - csv

Provisional format

## Description

It will be soon expanded. Table contains descriptive metadata of each of texts, directive metadata and internat metadata for processing reasons, structural description of processed title (specific model organisation units, chapters and paragraphs), bibliography and holder metadata.

### Descriptive metadata
'''
id	      - identification of work <integer>
group_id	- identification of periodical group <integer>

title_author	
title_lang
title_typ
title_genre	
ed_type
name_tid	
name	
year_creatio_tmp	
year_creatio_bf	
year_creatio_aft	
year_orig_tmp	
year_act_tmp	
name_short	
name_short_la	
name_version	
name_full	note
'''
### Directive metadata
'''
corpus_added - identification of participation in corpus	<boolean> (mainly for works in preparation)
'''
### Internal metadata
'''
obj_loc	
obj_change	- last change of object, ISO 8601
obj_lemm_udp - versions of UDP segmentation processing unit, tokens and sentences qual. dependent
'''
### Title structure

Warning: dependent on specific structuration of work during its digitisation. Only pars and tokens respect physical outlook of title instance.
'''
struct_ou	- organisational units
struct_lib	- books - chapters, dependent
struct_pars	- paragraphs in edition
struct_tok	- tokens after preprocessing
'''
## Bibliography and holder metadata
'''
act_rl_ed	
act_rl_trs	
act_pubname	
act_publoc	
act_print	
act_title	
act_perio	
act_ext	
act_isbn	
orig_publoc	
orig_depoins	
orig_depoloc	
orig_sign	
orig_ext	
digi_aut	
accessed_last	
lc_ref	
'''


