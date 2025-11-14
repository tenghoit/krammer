
# slides extraction

* attr: class_code, topic, date?
* text extraction: 
    * probably sure there's py lib for pptx, etc we can just use
    * for imgs, just ignore for now
    * also py lib for pdf, so user notes are easy to extract
* chunking: one slide per chunk? since normally one topic per slide


# embedding  

* models: test small first, can store diff models embeddings
* embed each chunk?
* maybe generate a concepts list per chunk to cmp later

# db

* can we get away with using chromadb, or need postgres (i dont have exp)

## chunk strat schema

* class_code, topic, slide#, concepts 

# notes

* folder for user notes
* 

# cmp process

* user specify what class and topic + paste notes 
* takes metadata to query db, get list of chunks
* for each chunk (concept list), check if concept in notes, else add chunk info to output
* result could be a small summary of missed concepts + citations for chunks/slides

# guardrails

* check if class code or topic exists
* no notes?

# considerations

* feel more 


