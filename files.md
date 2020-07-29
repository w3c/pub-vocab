
![W3C Logo](https://www.w3.org/Icons/w3c_home)

# Files in the repository

* **.var files**: necessary to control redirection on the `https://www.w3.org/ns/` directory and its subdirectories. 
* **pub-context.jsonld**: the JSON-LD context file as used by Web Publications
* **pub-vocab/manifest.{rdf,ttl,jsonld}**: the vocabulary files in various formats
* **pub-vocab-context.jsonld**: the context file used by for the proper compaction of the context file

Conversion from the `.ttl` source to `.rdf` and `.json` can be done, e.g., via https://rdf-translator.appspot.com/. Compacting of the jsonld file can be done on https://json-ld.org/playground/ using the `pub-vocab-context.jsonld` context file.
