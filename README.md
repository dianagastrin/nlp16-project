# NLP Project 
###Objective:
Given a Wikipedia biography entry as one chunk of text, divide the text
to pargraphs and name the paragraphs as closely as possible to the way it is in the
original entry.

###Algorithm:
* Prepare the texts, gather some statistics regarding average number of paragraphs, typicall topics etc.
* Run "tiling" on the text to split into segments.
* Learn titles/topics using the original Wikipedia entry and possibly some by product of the tiling (specifically, the topic word lists produced by LDA).
* Match title to automatically produced pargagraphs using the learned classifier.
* Evaluate the results.
* Hope for the best.

### References:
**Learning Biography Sections**
* http://www.aclweb.org/anthology/D15-1095
**Tiling**
* https://www.lt.tu-darmstadt.de/fileadmin/user_upload/Group_UKP/publikationen/2012/Riedl_Biemann_ACL_SRW_2012_TopicTiling_A_Text_Segmentation_Algorithm.pdf
