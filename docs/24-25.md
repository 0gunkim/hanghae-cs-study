---
layout: single
title: "1일 1로그(24,25)"
categories: coding
tag: [python, jekyll, blog]
toc: true
author_profile: false
sidebar:
  nav: "docs"
# search: false
---

## 😁 알고리즘이란?

알고리즘 : 추상적이고 이상적인 절차를 기술한 것, 구현에 필요한 세부 사항과 현실적인 고려 사항을 무시합니다. 정확하고 명료한 레시피입니다. 즉, 특정 문제를 풀기 위한 단계적인 절차, 문제 해결 방법을 추상화하여 단계적 절차를 논리적으로 기술해 놓은 명세서이고 특정 문제의 해결 방법 자체입니다. ex) 요리의 레시피, 음악의 악보, 가전제품 등의 사용 설명서

알고리즘의 조건?

1. 변환 대상이 되는 입력이 있어야 한다.
2. 한번 이상의 변환 과정을 겪어서 결과를 출력해야 한다.
3. 명령어들은 명백하고 모호하지 않아야 한다.
4. 순차적인 실행을 하고 실행이 종료되어야 한다.
5. 모든 명령들이 오류 없이 실행 되어야 한다.

의미가 완전히 알려져 있고 구체적으로 명시된 기본 연산으로 표현, 이러한 기본 연산을 사용하여 각 단계를 상세히 설명하고 모든 가능한 상황을 다룸, 그리고 알고리즘은 결국 멈춰야 한다.

## 🤣 프로그램이란?

**프로그램** : 실제 컴퓨터가 과제를 완료하기 위해 수행해야 하는 모든 단계를 구체적으로 서술합니다.

어떤 문제를 해결하기 위하여 그 처리 방법과 순서 를 기술하여 컴퓨터에 주어지는 일련의 명령문 집합체 즉, 사용자의 입력에 따라 그 입력된 값을 일정한 처리 방법과 순서에 따라 처리하여 결과를 산출해내는 명령문 집합입니다.

하나 이상의 알고리즘이 컴퓨터가 직접 처리할 수 있는 형태로 표현된 것이라고도 생각해 볼 수 있으며, 실질적인 문제도 신경 써야 합니다.즉, 알고리즘을 구현한 것이라고도 볼 수 있습니다.

**프로그램의 실질적인 문제점**

불충분한 메모리, 제한된 프로세서 속도, 유효하지 않거나 악의적으로 잘못된 입력 데이터, 하드웨어 결함, 네트워크 연결 불량 등 있습니다.

**알고리즘과 프로그램의 관계**

[http://kocw.xcache.kinxcdn.com/KOCW/document/2018/wonkwang/leesangwon0409/1.pdf](http://kocw.xcache.kinxcdn.com/KOCW/document/2018/wonkwang/leesangwon0409/1.pdf)

(알고리즘 : 작전, 프로그램 : 전투)

### 😶 프로그래밍과 프로그래밍 언어

프로그래밍(programming)이란 이와 같이 특정 목적을 달성하기 위해 설계된 알고리즘(algorithm)을 프로그래밍 언어를 사용하여 구체적인 프로그램으로 작성하는 과정 즉, 프로그램을 만드는 모든 작업입니다.

프로그래밍 언어 : 컴퓨터가 어떤 과제를 수행하는 데 필요한 계산 단계를 사람에게도 어느 정도 자연스러운 형태로 표현하도록 해주는 언어

ex) HTML, WML, Perl, SGML, JavaScript, Java, c/c++, XML, php

최초로 진정한 프로그래밍이 가능했던 전자식 컴퓨터에서 프로그래밍 과정

1. 프로그래머가 명령어와 데이터를 이진수로 변환
2. 카드나 종이 테이프에 구멍을 뚫어서 그 수를 기계가 판독할 수 있게 만든 다음, 컴퓨터 메모리에 적재

**에드삭**(EDSAC : Electronic Delay Storage Automatic Calculator)은 영국에서 개발된 초기 컴퓨터
이며 최초의 컴퓨터들 가운데 하나이며, 세계 최초의 실용적 프로그램 내장 전자식 컴퓨터입니다.

![Untitled](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/7ee33eeb-3f3f-4b34-ad29-e193c9d4d854/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220803%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220803T173321Z&X-Amz-Expires=86400&X-Amz-Signature=ed3c7898e234335a89551ac3c0fa07b0c09a7378f0c6cb0c1a2d18638bdcb01f&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

에드삭에서는 프로그램 작성을 쉽게 하는 연구가 이루어져 '초기명령'이라는 것이 만들어졌어요. 이것은 오늘날의 어셈블러(언어변환용 프로그램)의 기능을 가진 서브루틴(부분 프로그램) 등 프로그램에 있어서 중요한 방식을 포함하고 있답니다.

### 😎 어셈블러

**어셈블러**(assembler)는 어셈블리어를 기계어 형태의 오브젝트 코드로 해석해 주는 컴퓨터 언어 번역 프로그램을 말합니다. 어셈블러는 기본 컴퓨터 명령어들을, 컴퓨터 프로세서가 기본 연산을 수행하는데 사용할 수 있는 비트 패턴으로 변환시키는 프로그램입니다. 특정한 처리를 수행하는 프로그램입니다.

![Untitled](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/073978b2-22ea-412b-9789-ff43db8bf16b/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220803%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220803T173343Z&X-Amz-Expires=86400&X-Amz-Signature=b8932a5d877a34f1f30da42a5adda94f1bcaeb09f27d5bdc68389c135e564882&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

**기계어**는 실제로 컴퓨터의 CPU가 읽어서 실행할 수 있는 0과 1로 이루어진 명령어의 조합이다. 이러한 각 명령어에 대해 사람이 알아보기 쉬운 니모닉 기호(mnemonic symbol)를 정해 사람이 좀 더 쉽게 컴퓨터의 행동을 제어할 수 있도록 한 것이 **어셈블리 언어**입니다.

ex) x86 계열 CPU의 기계어 명령 : `10110000 01100001` , 어셈블리어 : `mov al, 061h`

어셈블리 언어는 대개 프로세서의 명령어와 일대일로 연결되고, 명령어가 이진수로 인코딩되는 특정한 방식과 메모리에 정보가 배치되는 방식등을 알고 있습니다. 즉, 특정 프로세서용 어셈블리 언어 프로그램을 다른 프로세서용으로 변환하고 싶다면 프로그램을 완전히 새로 작성해야 합니다.

## 🤩 참고

[알고리즘과 프로그램, 같은 뜻 아니다?](http://www.codingworldnews.com/news/articleView.html?idxno=3042)

[알고리즘과 프로그램의 차이점](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=kohchangwoo1&logNo=30036840962)

[프로그래밍 언어 종류(C. Java, php 등 10개)와 사용도, 순위](https://jhnyang.tistory.com/83)

[에드삭 - 위키백과, 우리 모두의 백과사전](https://ko.wikipedia.org/wiki/%EC%97%90%EB%93%9C%EC%82%AD)

[어셈블리어 - 위키백과, 우리 모두의 백과사전](https://ko.wikipedia.org/wiki/%EC%96%B4%EC%85%88%EB%B8%94%EB%A6%AC%EC%96%B4#%EC%96%B4%EC%85%88%EB%B8%94%EB%9F%AC)

[[Assembly] 어셈블리어란 무엇인가?](https://coding-factory.tistory.com/304)
