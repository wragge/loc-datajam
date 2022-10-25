# LoC Data Jam notebooks

I used these notebooks to extract country names from a very large collection of digitised books from the Library of Congress.

* [Download text files from Amazon S3 using the API](download_from_amazon_api.ipynb)
* [Extracting place names using Spacy and Named Entity Recognition](spacy.ipynb)
* [Look for countries in Wikidata matching the place names extracted through NER](get_countries.ipynb)
* [Filter place references using the Wikidata results](linking-countries-to-references.ipynb)
* [Extract sentences containing country names from the texts](process_sentences.ipynb)
* [Process metadata](process_metadata.ipynb)
* [Save data to an SQLite database for delivery via Datasette](prepare_for_datasette.ipynb)

You can view the results in [this database](https://loc-books-yajhxrvxsa-ts.a.run.app/), or using this [simple app](https://wragge.github.io/loc-books-demo/).