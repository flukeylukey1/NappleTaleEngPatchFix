
I’ve fixed the memo bug in the English-patched GDI that caused the To-Do list to clear after it was first opened and prevented the Notes and Requests lists from populating. 

Credit to Rolly for the original 2019 English Patch. 

Thank you to Dereck (ateam) for Universal Dreamcast Patcher and advice on how to share my fix with the community. 

I have generated a DCP that will apply both Rolly's English Patch & my Memo fix to the original, unmodified Japanese GDI (TOSEC).

Use the Universal Dreamcast Patcher to patch this game:
Napple Tale - Arsia in Daydream v1.006 (2000)(Sega)(JP)[!]

Patch has not been tested with any other disc images or CDI images. 

Only changes to Rolly's original Eng patch is a rewrite of MEMO.BIN. The bug was caused by malformed string boundaries in the original Eng Patch's MEMO.BIN, which prevented the game from correctly parsing the To-Do, Notes and Requests data. 
