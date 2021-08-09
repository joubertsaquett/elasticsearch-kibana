
# 🔖 About

This project is an example of how to upload nodejs logs to Elasticsearch and Kibana.

## 🗂 Support material

- [Elasticsearch e Kibana](https://www.elastic.co/pt/elastic-stack)
- [Elasticsearch para NodeJS](https://www.npmjs.com/package/elasticsearch)
- [API do Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/client/javascript-api/16.x/api-reference.html)

## 👍🏻 How to download

```bash

    // Clone repository
    $ git clone ....

    // Access directory
    $ cd elasticsearch/app/

    // Install dependencies
    $ npm install

    // Back to elasticsearch/
    $ docker-compose -f service.yaml up

    // Start nodejs project in elasticsearch/app/
    $ npm run dev
```

---

## IMPORTANT 
The type of hits must be created in ElasticSearch.

Open Kibana:

- Click on: "Connect to your Elasticsearch index" to create.



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
