---
description: '${platform} 을 이용하시기 위해서는 몇 가지 과정이 필요합니다.'
---

# Getting Started

## Required

${platform} 의 검색 서비스를 이용하기 위해서는 계정 및 ${app} 을 생성해야 합니다.

### Step 1 : Sign Up

-- Home 화면 구현이 아직 안됨

### Step 2 : Create an App

최초로 계정 정보를 등록하신 후 접하게 되는 아래 화면에서 새로운 ${APP} 을 생성하실 수 있습니다. ${Platform} 의 계정관리를 제외한 모든 기능들은 ${APP} 단위로 구분되어 있기 때문에 ${APP} 은 서로 정보를 공유하거나 영향을 주지 않습니다. 따라서 사용자는 다양한 설정값과 데이터로 만들어진 여러 개의 ${APP}을 동시에 운영하는 것이 가능합니다.

* 애플리케이션 이름 : ${APP} 이름
* 애플리케이션 설정 언어 : ${APP} 은 이곳에서 설정한 언어를 앞으로 들어올 ${query} 의 언어라고 인지합니다.
* 임계값 : 임계값은 검색엔진 성능의 엄격함을 나타냅니다. 검색엔진이 ${query} 를 전달받으면 우선 ${answer}이 될만한 후보군들을 찾아냅니다. 그리고 각 후보가 ${answer}에 적절한지 점수를 매깁니다. 최종적으로 검색엔진은 임계값 이상의 점수를 가진 후보군 중 가장 높은 점수의 후보군을  ${answer}로 사용자에게 전달합니다. 만약 모든 후보군의 점수가 임계값에 미치지 못한다면 검색엔진은 ${noanswer} 로 판단합니다.

{% hint style="info" %}
애플리케이션 언어는 한국어와 English 로 설정 가능합니다.
{% endhint %}

{% hint style="warning" %}
임계값을 지나치게 낮게 설정한다면 잘못된 ${query} 에 대해서도 ${answer} 를 찾아내서 반환하게 됩니다. 반면 임계값이 너 높으면 ${answer} 판단이 엄격해지게 되어 많은 ${query} 에 대해서 ${noanswer}로 판단합니다. 따라서 Test 를 거쳐 적절한 임계값을  설정하기를 권장드립니다. 
{% endhint %}

![](.gitbook/assets/image%20%2810%29.png)

### Step 3 : Authentication

${App} 을 생성하게 되면 ${platform} 의 기능 대부분을 사용하실 수 있습니다. 하지만 API와 SDK 를 사용할 때는 ${App}의 Application Code 값과 API Key 값이 필요합니다. 이 값들은 Setting 탭에서 확인하실 수 있습니다.

dfasdfasdf

![http://alpha.42maru.com/applications/{app\_code}/settings](.gitbook/assets/image%20%285%29.png)

### Step 4 : Dashboard

대쉬보드를 확인하는 과정을 보여줄 

## Optional : Installation SDK

### Python

```text
$ pip install ~~~
```

## Next Steps

계정 및 ${app} 이 생성 되었다면 ${platform} 의 기능들을 정삭적으로 이용하실 수 있습니다. 

### Search Services

{% page-ref page="search-service/usd-mrc/" %}

{% page-ref page="search-service/usd-nlp.md" %}



### Features

{% page-ref page="product/usd-mrc.md" %}

{% page-ref page="product/log.md" %}

{% page-ref page="product/static/" %}

{% page-ref page="product/frequently.md" %}

{% page-ref page="product/simulation.md" %}

{% page-ref page="product/api.md" %}

{% page-ref page="product/app.md" %}

### 

### Additional Resources

{% page-ref page="quick-start/untitled.md" %}

{% page-ref page="quick-start/glossary.md" %}

{% page-ref page="quick-start/security.md" %}

{% page-ref page="quick-start/usd-mrc.md" %}

{% page-ref page="quick-start/troubleshooting.md" %}

