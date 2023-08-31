# 🔎 Document Search Demo 

This is the source code for [Using Haystack with REST API](https://haystack.deepset.ai/tutorials/20_using_haystack_with_rest_api) tutorial.

## Usage

Clone this repository and run `docker-compose up` inside *`/doc-search`* folder:

```sh
git clone https://github.com/bilgeyucel/document-search-demo
cd doc-search
docker-compose up
```

This will launch an empty Elasticsearch instance and the Haystack API. Test if everything is OK with the Haystack API by sending a cURL request to the `/initialized` endpoint. If everything works fine, you will get `true` as a response.

```sh
curl --request GET http://127.0.0.1:8000/initialized
```

To **upload your documents to Elasticsearch**, follow the [Indexing Files to Elasticsearch](https://haystack.deepset.ai/tutorials/20_using_haystack_with_rest_api#indexing-files-to-elasticsearch) section of the tutorial.

