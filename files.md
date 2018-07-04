

![W3C Logo](https://www.w3.org/Icons/w3c_home)

# Files in the repository

* **.var files**: necessary to control redirection on the `https://www.w3.org/ns` directory. 
* **wp-context.jsonld**: the JSON-LD context file as used by Web Publications
* **wp.{rdf,ttl,json}**: the vocabulary files in various formats
* **wp-vocab-context.jsonld**: the context file used by `wp.json`
* **update**: used by the maintainer (IH) to convert the Turtle source for the vocabulary into the other two formats. 
	* `Closure` is a local CLI to a more general tool ([RDF/OWL RL service](https://www.ivan-herman.net/Misc/2008/owlrl/)) used here simply as a converter from Turtle to RDF/XML and JSON-LD
	* `jsonld` is a [CLI to a JSON-LD processor](https://github.com/digitalbazaar/jsonld-cli)

    If the tool is used locally, it should be updated to the local environment...