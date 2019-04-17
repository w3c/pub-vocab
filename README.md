

![W3C Logo](https://www.w3.org/Icons/w3c_home)

# Vocabulary for Web Publications Manifest

This is the repository for the Web Publication Manifest vocabulary and JSON-LD context files. It is adjunct to the work on Web Publications, developed by the [Publishing Working Group](https://www.w3.org/publishing/groups/publ-wg/).

The vocabulary and context files in this repository are served via their canonical URL, based on `https://www.w3.org/ns/wp` and `https://www.w3.org/ns/wp-context`, respectively, using content negotiations. The HTTP requests are resolved to

- `https://www.w3.org/ns/wp.{jsonld,json,rdf,ttl,html}` for the vocabulary
- `https://www.w3.org/ns/wp-context.{json,jsonld}` for the JSON-LD context file

depending on the accept header of the request.

## Contributing to the Repository

Use the standard fork, branch, and pull request workflow to propose changes to the specification. Please make branch names informative—by including the issue or bug number for example.

Editorial changes that improve the readability of the spec or correct spelling or grammatical mistakes are welcome.

Please read [CONTRIBUTING.md](CONTRIBUTING.md), about licensing contributions.

## Final locations of the documents

These files are _not_ aimed to be part of a W3C Technical Report. Instead, the `wp.*` and `wp-context.*` files are meant to be copied to the `https://www.w3.org/ns/` directory (which can only be done by a W3C staff member).

## Code of Conduct

W3C functions under a [code of conduct](https://www.w3.org/Consortium/cepc/).
