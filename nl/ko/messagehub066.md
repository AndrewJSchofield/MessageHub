---

copyright:
  years: 2015, 2017
lastupdated: "2016-11-22"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# 연결 및 인증 방법
{: #rest_connect}

{{site.data.keyword.messagehub}}에 연결하기 위해 Kafka REST API는 [VCAP_SERVICES 환경 변수](/docs/services/MessageHub/messagehub071.html)에서 <code>api_key</code> 및 <code>kafka_rest_url</code>
신임 정보를 사용합니다. 

{{site.data.keyword.messagehub}} Kafka REST API와 인증하려면 사용자 요청의 X-Auth-Token 헤더에 <code>api_key</code>를 지정해야 합니다. 
