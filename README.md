# Relationship Extraction Python Sample

  The IBM Watson [Relationship Extraction][relationship_extraction] service parses sentences into their various components and detects relationships between the components. It can process new terms (like people's names in a news feed) it has never analyzed before through contextual analysis. Sentence components include parts of speech (noun, verb, adjective, conjunction, etc.) and functions (subjects, objects, predicates, etc.). The service maps the relationships between the components so that users or analytics engines can more easily understand the meaning of individual sentences and documents.

## Getting Started
In order to run the application in your local environment you will have to install the dependencies listed in `requirements.txt`.

```sh
pip install -r requirements.txt
```

`requests`  is being used to call the Relationship Extraction API.

## Usage
Simple text analysis:
```sh
echo "New York is awesome" | python main.py
```

You can also pipe a file:
```sh
cat article.txt | python main.py
```

From .txt to .xml:
```sh
cat article.txt | python main.py > article.xml
```
## License

This library is licensed under Apache 2.0. Full license text is
available in [COPYING](https://github.com/watson-developer-cloud/nodejs-wrapper/blob/master/LICENSE).

## Open Source @ IBM
  Find more open source projects on the [IBM Github Page](http://ibm.github.io/)

[relationship_extraction]: http://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/sireapi/
