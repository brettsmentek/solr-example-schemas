## Solr example schemas

A repository to get started with Apache Solr schemas for rich documents (Word, PDF, PowerPoint, images). Includes a minimum schema as a starting point and a full generated schema.

#### The Basic Stack

- [Git](https://git-scm.com/)
- [Apache Solr 6](http://lucene.apache.org/solr/)

### Assumptions

1. You have Solr installed with schema config files at ```./server/solr/configsets/```


### To use

1. Place the desired schema in the ```./server/solr/configsets/``` directory.
2. Update ```./scripts/cloudupdate.bat``` and ```./scripts/cloudlink.bat``` to reflect your configuration name and your Solr collection name.
3. Run ```cloudupdate.bat``` to create or update the schema in SolrCloud.
4. Run ```cloudlink.bat``` to link the schema with your selected Solr collection.