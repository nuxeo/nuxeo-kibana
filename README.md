nuxeo-kibana
============

Deploy the latest Kibana version in nuxeo.war


Build with mvn clean install

Drop the jar in the plugins folder of your nuxeo server

Add the following entries to your nuxeo.conf
  elasticsearch.httpEnabled=true
  elasticsearch.indexName=nuxeo
  
Keep in mind that by doing so kibana becomes accessible to anyone !

Open kibana at http://yournuxeoserver/nuxeo/kibana/

Start with a sample dashboard 

In the dashboard settings panel, enable the preload fields setting

Some sample Queries
  ecm\:primaryType:File
  dc\:title:"test demo"





