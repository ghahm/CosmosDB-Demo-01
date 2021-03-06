### 원본 Intro (필독)
https://github.com/Microsoft/developer-immersion-data/blob/master/labs/sp-gda/gdaexpericence1/story_a_gda_using_cosmosdb/content/intro.md

### 데모 환경
1. 데모 환경 구성 : azure powershell과 arm template을 이용하여 리소스 배포 ([powershell script 및 arm template 위치](https://github.com/ghahm/CosmosDB-Demo-01/tree/master/ARM-Template))

2. 리소스
* **Cosmos DB** <br>
(1) Location : east us (latency 데모를 위해 원거리에 생성) <br>
(2) Type : Document(SQL API) DB 1 EA for flight information / Mongo DB 1 EA for feedback
* **Function App & Storage Account** <br>
(1) Location : east us / japan east (latency 비교를 위해 2곳에 생성했으나 실제 데모에서는 Japan East만 사용함) <br>

3. 데모 아키텍처
* ***ContosoAir Web Service (PC) -> ContosoAir App Service (Function App in Japan East) -> ContosoAir Cosmos DBs (Document DB and Mongo DB in East US or Japan East)***

[[Home]](https://github.com/ghahm/CosmosDB-Demo-01) / [[Next]](https://github.com/ghahm/CosmosDB-Demo-01/blob/master/content/0.md)
