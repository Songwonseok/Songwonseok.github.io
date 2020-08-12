---
title: "프로세스와 스레드의 차이"
date: 2020-08-11 15:00:00 -0400
categories: Study
---

[프로세스와 스레드의 차이]



### 프로세스란 무엇인가?

**- 프로세스 :** 자기 자신만의 주소 공간을 갖는 독립적인(Self-Contained) 실행 프로그램

**- 멀티 프로세스 :** 두 개 이상의 프로세스가 실행되는 것. 프로그램이 여러개 띄워져 있는 형식.

**- 멀티 태스킹 :** 두 개 이상의 프로세스를 실행하여 일을 처리하는 것



> **프로그램 :** 스태틱하게 머신에 인스톨되어있는 인스트럭션(코드, 커맨드, 실행해야할 명령)등의 집합
>
> **프로세스 :** 프로그램이 실행중(프로그램 안의 인스트럭션들이 실행되고 있는 중)인 것.
>
> 

### 스레드란 무엇인가?

**- 스레드(경량 프로세스) :** 프로세스 내의 독립적인 순차흐름 또는 제어

**- 멀티 스레드 :** 하나의 프로세스에서 여러 개의 스레드가 병행적으로 처리

![230B7D3359019EBE18](../../assets/images/study/processAndThread/그림1.jpg)

- 프로세스 내에 스레드란 개념이 포함되어 있으므로 스레드와 프로세스는 서로 연관이 되어 있습니다. 프로세스는 실행중인 프로그램 객체 자체를 말하고, 하나의 실행흐름 자체를 스레드라고 말합니다. 하나의 프로세스안에 스레드가 여러개 있는 것을 멀티 스레드라고 말합니다. 
- 네트워크 프로그래밍을 할때에는 멀티 쓰레딩이 필요합니다. 게임프로그래밍에서 특히 멀티 스레드를 많이 사용하게 됩니다. 예를 들면, 사용자가 게임을 하려면 크게 1.사용자의 input, 2.네트워크로부터 전송되는 input 두개의 input이 있게 됩니다. 1,2는 동시에 병렬적으로 일어나야 합니다.
- 한 프로세스에 스레드가 2개있다는 말은 해단 프로세스 내 실행흐름이 2개 존재한다는 의미와 동일합니다. 한 프로그램 안에서 여러가지 태스크를 동시 수행하고 싶을때, 쓰레드를 사용하게 됩니다. **네트워크 프로그래밍에서는 반드시 필요합니다.** 예를 들면, 가장 간단한 네트워크 프로그래밍인 채팅 프로그램에서는 채팅메시지에서 채팅을 쓰는 부분(키보드 input), 상대방의 채팅메시지를 전달받는 부분(network input) 결과적으로 single thread에서는 부자연스럽게 돌아가게 될 것입니다.

![230B7D3359019EBE18](../../assets/images/study/processAndThread/그림2.png)

![230B7D3359019EBE18](../../assets/images/study/processAndThread/그림3.png)

### 스레드의 활용

> **1) 게임 프로그래밍**
>
>   \- 게임에 등장하는 캐릭터를 움직이게 하는 스레드
>
>   \- 여러 캐릭터들이 동시에 움직인다 (대부분의 게임에서 각 캐릭터는 각각의 스레드를 가짐)
>
> **2) N/W 프로그래밍**
>
>   \- 프로그램의 흐름을 담당하는 스레드
>
>   \- 네트워크로부터 데이터를 기다리는 스레드



### 멀티 프로그래밍

\- 여러 개의 프로그램들이 단일 CPU 상에서 동시에 실행되는 것

\- 컴퓨터에는 한 개의 CPU내에 존재하기 때문에 진정한 의미로는 여러개의 프로그램이 동시에 실행된다고 볼 수는 없습니다.

\- 한 프로그램이 일부 실행되고 나서 또 다른 프로그램이 일부 실행되는 방식입니다.

**- 모든 프로그램이 동시에 수행되는것처럼 보이게 됩니다.**





궁극적으로 프로세스간에도 스위치가 일어나고 있고, 스레드 안에서도 스위치가 일어나고 있는 모습(CPU를 갖고있는 동안)이 됩니다. 그리고 프로그래밍시에는 스레드는 각각 별도의 함수로 구성되어 있습니다.



### 프로세스 생명주기

![230B7D3359019EBE18](../../assets/images/study/processAndThread/그림4.png)



**프로세스 주소 공간**
\- 텍스트 영역 : 프로세서가 실행하는 코드를 저장하는 영역
\- 데이터 영역 : 전역 변수가 저장되는 공간
\- 힙 영역 : 프로세스가 실행 중에 사용하기 위해 동적으로 할당받은 메모리 공간
\- 스택 : 호출된 프로시저용으로 지역변수와 명령어들을 저장하는 공간





출처: https://12bme.tistory.com/65 [길은 가면, 뒤에 있다.]

https://m.blog.naver.com/PostView.nhn?blogId=nr_1995&logNo=221265266303&proxyReferer=https:%2F%2Fwww.google.com%2F