# Elasticsearch Box
A [wercker](http://wercker.com/) box for elasticsearch with kuromoji and icu plugin.

### Installed
- `elasticsearch`@1.3.4
- `elasticsearch-analysis-kuromoji`@2.3.0
- `elasticsearch-analysis-icu`@2.3.0

### How to use this box
In the `wercker.yml` of your application use the following box definition: 

```
services:
  - heathrow/elasticsearch@0.0.1
```
