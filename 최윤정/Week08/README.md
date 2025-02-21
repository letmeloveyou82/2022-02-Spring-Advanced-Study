# 📗 토비의 스프링 3.1 Vol.1 스프링의 이해와 원리
## 📝 8장 스프링이란 무엇인가?
#### ✨ 8장에서 다루는 것 : 스프링이란 무엇이고, 어떻게 설명할 수 있으며, 스프링 프레임워크가 만들어진 이유, 존재 목적, 추구하는 가치
## 8.1 스프링의 정의
### 🌱 스프링의 정의
>자바 엔터프라이즈 개발을 편하게 해주는 오픈소스 경량급 애플리케이션 프레임워크

<br>

### ✅ 애플리케이션 프레임워크
- **특정 계층이나, 기술, 업무 분야에 국한되지 않고 애플리케이션의 전 영역을 포괄하는 범용적인 프레임워크**

- 애플리케이션 개발의 전 과정을 빠르고 편리하며 효율적으로 진행하는데 일차적인 목표를 둠
- **스프링이 애플리케이션 프레임워크라 불리는 이유 :**

	- **스프링의 탄생 배경** - J2EE 기술서적에 딸린 예제 프레임워크로부터 시작됨 - 이 책 자체가 애플리케이션 전반에 걸친 모든 분야 포괄함 => 스프링은 자연스럽게 애플리케이션의 전 영역을 지원하는 종합적인 애플리케이션 프레임워크가 됨

	- **애플리케이션의 전 영역을 관통하는 프로그래밍 모델과 핵심 기술을 바탕으로 해서 각 분야의 특성에 맞는 필요를 채워주고 있기 때문**=> 애플리케이션을 빠르고 효과적으로 개발 가능
- **스프링의 일차적인 존재 목적 :** 

	- 핵심 기술에 담긴 프로그래밍 모델을 일관되게 적용해 엔터프라이즈 애플리케이션 전 계층과 전 영역에 전략과 기능을 제공해줌으로써 애플리케이션을 편리하게 개발하게 해주는 **애플리케이션 프레임워크로 사용되는 것**

<br>

### ✅ 경량급
- **불필요하게 무겁지 않다는 의미**

- 스프링의 기원이 된 책에서 비판하는 자바 엔터프라이즈 기술의 불필요한 복잡함에 반대되는 개념
- 스프링은 가장 단순한 서버환경인 톰캣(Tomcat)이나 제티(Jetty)에서도 완벽하게 동작
- 스프링의 장점 :

	- 가볍고 단순한 환경에서도 복잡한 EJB와 고가의 WAS를 갖춰야만 가능했던 엔터프라이즈 개발의 고급 기술을 대부분 사용할 수 있다는 점
- **만들어진 코드가 지원하는 기술수준은 비슷하더라도 그것을 훨씬 빠르고 간편하게 작성하게 해줌으로써 생산성과 품질 면에서 유리**

<br>

### ✅ 자바 엔터프라이즈 개발을 편하게
- 스프링은 근본적인 부분에서 엔터프라이즈 개발의 복잡함을 제거해내고 진정으로 개발을 편하게 해주는 해결책을 제시

- 기존 기술 접근 방법과 스프링의 접근 방법의 차이점 : 

	- 엔터프라이즈 개발의 근본적인 문제점에 도전해 해결책 제시한다는 점
- **편리한 애플리케이션 개발** 

	= 개발자가 복잡하고 실수하기 쉬운 로우레벨 기술에 많은 신경을 쓰지 않으면서도 애플리케이션의 핵심인 사용자의 요구사항, 즉 **비즈니스 로직을 빠르고 효과적으로 구현하는 것**
	- EJB의 비전과 목표였음

	- 그러나 EJB의 문제는 이 과정에서 다른 차원의 더 큰 복잡함을 애플리케이션 개발에 끌고 들어왔다는 점
- **스프링**은 EJB가 궁극적으로 이루고자 했던 이 목적을 제대로 실현하게 해줌 (**개발자가 작성하는 애플리케이션 로직에 더 많은 관심과 시간을 쏟게 해줌**)
- 스프링은 **엔터프라이즈 개발에서 필연적으로 요구되는 기술적인 요구를 충족**하면서도 **개발을 복잡하게 만들지 X**

<br>

### ✅ 오픈소스
- **소스가 모두에게 공개되고, 특별한 라이선스를 취득할 필요없이 얼마든지 가져다 자유롭게 이용해도 된다는 뜻**

- 개발 과정에 많은 사람이 자유롭게 참여가능
- **오픈소스의 장점** : 

	- 매우 빠르고 유연한 개발 가능

	- 잠재적인 버그와 문제점 빠르게 발견 + 해결
	- 라이선스 비용 부담 X
- **오픈소스 개발 모델 단점** : 

	- 지속적이고 안정적인 개발 계속될지 불확실함
- 그래서, 오픈소스 개발이라는 방법을 선택하긴 했지만, 프레임워크 사용자에게 지속적인 신뢰를 줄 수 있도록 개발을 책임지고 진행할 수 있는 전문 기업 '스프링소스' 만듦
- 스프링은 오픈소스의 장점을 충분히 취하면서 동시에 오픈소스 제품의 단점과 한계 잘 극복하고 있는, 전문적이고 성공적인 오픈소스 소프트웨어라고 할 수 있음

<br>

## 8.2 스프링의 목적
### ✅ 자바의 근본적인 목적 : 
- 객체지향 프로그래밍을 통해 유연하고 확장성 좋은 애플리케이션을 빠르게 만드는 것

<br>

### 🌱 스프링의 목적 : 
- 정의를 통해 살펴봤듯이, '**경량급 프레임워크인 스프링을 활용해서 엔터프라이즈 애플리케이션 개발을 편하게**' 하는 것

<br>

#### 🤔 굳이 스프링을 사용해 엔터프라이즈 애플리케이션 개발을 편하게 하려는 이유? 

> 원래 엔터프라이즈 개발이란 편하지 않기 때문

<br>

### ✅ 엔터프라이즈 시스템이란?
> 서버에서 동작하며 기업과 조직의 업무를 처리해주는 시스템

<br>

### 🧐 엔터프라이즈 시스템 개발은 왜 복잡할까?
1. 기술적인 제약조건과 요구사항이 늘어가기 때문

2. 엔터프라이즈 애플리케이션이 구현해야 할 핵심기능인 비즈니스 로직의 복잡함이 증가하기 때문

<br>

### ✅ 엔터프라이즈 애플리케이션 개발이 실패하는 주요 원인
- **비즈니스 로직의 복잡함**과 **엔터프라이즈 기술적인 복잡함**이 **한데 얽혀 있기 때문**

<br>

### 📝 복잡함을 해결하려는 도전
- 엔터프라이즈 개발의 근본적인 복잡함의 원인은 제거할 대상이 X

- 대신 그 복잡함을 효과적으로 상대할 수 있는 전략과 기법 필요
- 💥 **문제** : 

	- **비즈니스 로직의 복잡함을 효과적으로 다루기 위한 방법**과 **기술적인 복잡함을 효과적으로 처리하는 데 적용되는 방법이 다르다**는 점
- 💡 **해결책** : 
	- **성격이 다른 이 두 가지 복잡함을 분리하자**

#### 😥 실패한 해결책 : EJB

#### 😊 비침투적인 방식을 통한 효과적인 해결책 : 스프링
- 비침투적인(non-invasive) 기술은 기술의 적용 사실이 코드에 직접 반영되지 않는다는 특징이 있음

- 스프링을 이용하면 기술적인 복잡함과 비즈니스 로직을 다루는 코드를 깔끔하게 분리 가능, 그 과정에서 스프링 스스로가 애플리케이션 코드에 불필요하게 나타나지 않도록 함
- 물론 스프링 적용한다 해서 근본적인 복잡함의 원인이 사라지는 건 x
- 하지만, 성격 다른 복잡함들 깔끔하게 분리, 부가적인 복잡함 가져오지 X	

<br>

## 복잡함을 상대하는 스프링의 전략
**스프링의 기본적인 전략** : 비즈니스 로직을 담은 애플리케이션 코드와 엔터프라이즈 기술을 처리하는 코드를 분리시키는 것


### 1️⃣ 기술적 복잡함을 상대하는 전략
스프링은 엔터프라이즈 기술을 적용했을 때 발생하는 복잡함의 문제를 두 가지로 분류하고 각각에 대한 적절한 대응 방법을 제공함


#### 💥 첫 번째 문제  : 기술에 대한 접근 방식이 일관성 없고, 특정 환경에 종속적
#### 💡 해결책 : 
- **서비스 추상화** (기술적인 복잡함은 일단 추상화를 통해 로우레벨의 기술 구현 부분과 기술을 사용하는 인터페이스를 분리하고, 환경과 세부 기술에 독립적인 접근 인터페이스를 제공하는 것이 가장 좋은 해결책)

- **템플릿/콜백 패턴** (판에 박힌 반복적 작업 흐름과 API 사용 코드 제거해줌 -> 기술 사용하는 코드도 최적화된 핵심 로직에만 집중하도록 도와줌)

#### 💥 두 번째 문제  : 기술적인 처리를 담당하는 코드가 성격이 다른 코드에 섞여 등장함
#### 💡 해결책 : 
- **AOP** (**최후까지 애플리케이션 로직을 담당하는 코드에 남아있는 기술 관련 코드를 깔끔하게 분리해서 별도의 모듈로 관리하게 해주는 강력한 기술임.** 기술을 다루는 코드로 인한 복잡함이 기술 그 자체 이상으로 불필요하게 증대되지 않도록 도와주는 가장 강력한 수단)

<br>

### 2️⃣ 비즈니스와 애플리케이션 로직의 복잡함을 상대하는 전략
- **자바라는 객체지향 기술 그 자체**

- 스프링은 단지 객체지향 언어의 장점을 제대로 살리지 못하게 방해했던 요소를 제거하도록 도와줄 뿐

<br>

### ✅ 두 복잡함을 해결하는 데 스프링이 공통적으로 사용하는 도구 : 객체지향과 DI
- **스프링의 기본 전략** : 

	- 자바의 기본인 객체지향에 충실한 설계가 가능하도록 단순한 오브젝트로 개발할 수 있고, 객체지향의 설계 기법을 잘 적용할 수 있는 구조를 만들기 위해 DI 같은 유용한 기술을 편하게 적용하도록 도와주는 것
- **서비스 추상화, 템플릿/콜백, AOP**와 같은 스프링의 기술은 **모두 DI를 바탕으로 할 수 있는 것**들임

- **DI**는 객체지향 설계 기술이 없이는 존재 의미가 없음
- DI는 특별한 기술이라기 보단, **유연하게 확장할 수 있는 오브젝트 설계를 하다 보면 자연스럽게 적용하게 되는 객체지향 프로그래밍 기법**이며, **스프링은 단지 그것을 더욱 편하고 쉽게 사용하도록 도와줄 뿐임**
- 결국 DI는 좋은 오브젝트 설계의 결과물이기도 하지만, 반대로 DI를 열심히 적용하다 보면 객체지향 설계의 원칙을 잘 따르고 그 장점을 살린 설계가 나올 수도 있음
- 🧐 **왜 스프링이 힘들게 비즈니스 로직 자체를 기술적인 코드와 특정 기술의 스펙이 침범하지 않는 코드로 만들어주는 데 그토록 힘을 썼을까?**

	- 순수한 비즈니스 로직만이 담고 있는 코드엔 객체지향 분석과 설계에서 나온 도메인 모델을 쉽게 적용 가능해서 
- [결론] : 모든 스프링의 기술과 전략은 객체지향이라는 자바 언어가 가진 강력한 도구를 극대화해서 사용할 수 있도록 돕는 것이다.

<br>


## 8.3 POJO 프로그래밍
**"스프링의 정수(essence)는 엔터프라이즈 서비스 기능을 POJO에 제공하는 것"**

- 엔터프라이즈 서비스 : 보안, 트랜잭션과 같은 엔터프라이즈 시스템에서 요구되는 기술

- 이런 기술을 POJO에 제공한다 = 엔터프라이즈 서비스 기술과 POJO라는 애플리케이션 로직을 담은 코드를 분리했다는 뜻

### 🌱 스프링의 가장 강력한 특징과 목표 : 
> '분리됐지만 반드시 필요한 엔터프라이즈 서비스 기술을 POJO 방식으로 개발된 애플리케이션 핵심 로직을 담은 코드에 제공한다'는 것

<br>

## POJO
스프링의 핵심 = POJO 프로그래밍

스프링의 주요 기술인 IoC/DI, AOP와 PSA는 애플리케이션을 POJO로 개발할 수 있게 해주는 **가능기술**(enabling technology)라고 불림


### ✅ POJO란 무엇인가?
**POJO(Plain Old Java Object)**

단순하게 보자면 그냥 평범한 자바오브젝트라고 할 수 있지만, 적어도 다음의 **세 가지 조건**을 충족해야 POJO라고 불릴 수 있음

#### ✅ POJO의 조건 3가지
1. 특정 규약(contract)에 종속되지 X

2. 특정 환경에 종속되지 X
3. 객체지향적인 자바 언어의 기본에 충실하게 만들어져야 함

#### [결론] 
✅ **진정한 POJO** = **객체지향적인 원리에 충실하면서, 환경과 기술에 종속되지 않고 필요에 따라 재활용될 수 있는 방식으로 설계된 오브젝트**

✅ 그런 **POJO에 애플리케이션의 핵심 로직과 기능을 담아 설계하고 개발하는 방법** = **POJO 프로그래밍**

<br>

### 🤗 POJO의 장점 
POJO가 될 수 있는 조건이 그대로 POJO의 장점이 됨
- 깔끔한 코드

- 자동화된 테스트에 매우 유리
- 객체지향적인 설계 자유롭게 적용 가능

<br>

### ✅ POJO 프레임워크란?
스프링은 POJO를 이용한 엔터프라이즈 애플리케이션 개발을 목적으로 하는 프레임워크

#### **POJO 프레임워크**
- **POJO 프로그래밍이 가능하도록 기술적인 기반을 제공하는 프레임워크**

- 대표 예시 : 

	- **스프링 프레임워크** (엔터프라이즈 애플리케이션 개발의 모든 영역과 계층에서 POJO 방식의 구현이 가능하게 하려는 목적으로 만들어짐)

	- **하이버네이트** (주로 DB 이용 기술에 POJO 적용)

#### 👀 엔터프라이즈 애플리케이션 전체의 복잡함 상대
- 비즈니스 로직의 복잡함 - POJO 

- 엔터프라이즈 기술의 복잡함 - 스프링 프레임워크

<br>

## 8.4 스프링의 기술
스프링에는 POJO 프로그래밍을 손쉽게 할 수 있도록 지원하는 **세 가지 가능기술**을 제공 
> **IoC/DI, AOP, PSA**

스프링의 기술들은 스프링 프레임워크가 만들어진 진정한 목표인 POJO 기반의 엔터프라이즈 개발을 편리하게 해주는 도구일 뿐.

다른 관점에서 보자면, IoC/DI, AOP, PSA라는 것 자체가 이미 스프링이 중요한 가치를 두는 객체지향의 원리를 충실히 적용해 나온 결과임.

<br>

## ✅ 제어의 역전(IoC) / 의존관계 주입(DI)
IoC/DI는 **스프링의 가장 기본이 되는 기술이자 스프링의 핵심 개발 원칙**

나머지 두 가지 기술인 AOP와 PSA도 IoC/DI에 바탕을 두고 있음

#### DI를 왜 쓸까?
- 유연한 확장이 가능하게 하기 위해서

- DI는 개방폐쇄원칙(OCP)이라는 객체지향 설계 원칙으로 잘 설명될 수 있음
- **확장**에는 열려있고, **재사용**이 가능하다는 장점 존재

<br>

### 🧐 DI의 활용 방법
#### 1️⃣ 핵심기능의 변경
- 의존 대상의 구현을 바꾸는 것

- ex) 디자인 패턴의 전략 패턴 
#### 2️⃣ 핵심기능의 동적인 변경
- 의존 오브젝트의 핵심기능 자체를 바꾸는데, 동적으로 매번 다르게 변경 가능

- 기술적으로 보자면, 다이내믹 라우팅 프록시 or 프록시 오브젝트 기법 활용한 것
#### 3️⃣ 부가기능의 추가
- 핵심기능은 그대로 둔 채로 부가기능을 추가

- ex) 데코레이터 패턴

	- 인터페이스를 두고 사용하게 하고, 실제 사용할 오브젝트는 외부에서 주입하는 DI를 적용해두면 데코레이터 패턴 쉽게 적용 가능
- 부가기능의 추가 방식을 특정 오브젝트가 아니라 좀 더 많은 대상으로 일반화해서 적용하면 AOP가 됨

#### 4️⃣ 인터페이스의 변경
- 클라이언트가 사용하는 인터페이스와 실제 오브젝트 사이에 인터페이스가 일치하지 않는 경우

- 디자인 패턴에서 말하는 오브젝트 방식의 어댑터 패턴의 응용이라고 볼 수 있음
- 이를 좀 더 일반화해서 아예 인터페이스가 다른 다양한 구현을 같은 방식으로 사용하도록, 중간에 인터페이스 어댑터 역할을 해주는 레이어를 하나 추가하는 방법 = 일관성 있는 서비스 추상화(PSA)
#### 5️⃣ 프록시
- 프록시 패턴의 전형적인 응용 방법 

- 프록시는 언제 필요한가? 

	- 필요한 시점에서 실제 사용할 오브젝트를 초기화하고 리소스를 준비하게 해주는 지연된 로딩(lazy loading)을 적용하고 싶을 때

	- 원격 오브젝트를 호출할 때 마치 로컬에 존재하는 오브젝트처럼 사용할 수 있게 해주는 원격 프록시를 적용하려고 할 때


#### 6️⃣ 템플릿과 콜백
- 템플릿/콜백 패턴은 DI의 특별한 적용 방법

- 반복적으로 등장하지만 항상 고정적인 작업 흐름과 그 사이에서 자주 바뀌는 부분을 분리해서 템플릿과 콜백으로 만들고 이를 DI 원리를 응용해 적용하면 지저분하게 매번 만들어야 하는 코드를 간결하게 만들 수 있음

#### 7️⃣ 싱글톤과 오브젝트 스코프
- **DI는 DI 할 오브젝트의 생명주기를 제어할 수 있음**

- DI를 프레임워크로 이용한다 = DI 대상 오브젝트를 컨테이너가 관리한다
- 가장 기본이 되는 스코프 : 싱글톤

	- 스프링의 DI는 기본적으로 싱글톤으로 오브젝트를 만들어서 사용하게 함

	- 클래스 자체는 싱글톤을 고려하지 않고 자유롭게 설계해도 된다는 장점 있음

- 때론 단일 싱글톤이 아니라 임의의 생명주기를 갖는 오브젝트가 필요할 때도 있음 -> **스프링에서는 싱글톤 외에도 다양한 스코프를 갖는 오브젝트를 만들어 DI에 사용 가능**

#### 8️⃣ 테스트
- DI의 중요한 용도는 바로 테스트

- 여타 오브젝트와 협력해서 동작하는 오브젝트를 효과적으로 테스트하는 방법 = 가능한 한 고립시키자
- 의존 오브젝트를 대신해 스텁 또는 목 오브젝트 같은 테스트 대역을 활용하자 
	- DI를 위해 만든 수정자 메소드를 사용하면 테스트 코드 안에서 수동으로 목 오브젝트 주입 가능

	- 또는 테스트용으로 설정을 별도로 만드는 방법도 있음

#### 결론
- 잘 살펴보면 DI의 용도는 디자인 패턴 중에서 오브젝트 합성 방식을 따르는 패턴과 관련 있음을 알 수 있음

- 오브젝트 스코프의 패턴 : GoF의 디자인 패턴 중에서 오브젝트 합성 방식을 따르는 패턴과 관련 있으며, DI의 구조에 대부분 잘 들어맞음

- 패턴의 장점들을 애플리케이션 전 영역에서 간단한 설정만으로 자연스럽게 적용할 수 있게 만들어주는 것이 바로 DI

<br>

## ✅ 애스펙트 지향 프로그래밍(AOP)
AOP와 OOP는 서로 배타적이 아님

**AOP : 객체지향 기술의 한계와 단점을 극복하도록 도와주는 보조적인 프로그래밍 기술**

AOP를 사용하면 그 결과로 OOP를 더욱 OOP 답게 만들어줄 수 있음

스프링의 목적인, POJO만으로 엔터프라이즈 애플리케이션을 개발하면서도 엔터프라이즈 서비스를 선언적으로 제공하는 데 반드시 필요한 것이 바로 AOP 기술

IoC/DI를 이용해 POJO에 선언전인 엔터프라이즈 서비스를 제공할 수 있지만 일부 서비스는 순수한 객체지향 기법만으로는 POJO의 조건을 유지한 채로 적용하기 힘듦 => 이런 문제 해결하기 위해 AOP가 필요!

<br>

### 🧐 AOP의 적용 기법
1. **스프링과 같이 다이내믹 프록시를 사용하는 방법** (기존 코드에 영향 주지 않고 부가기능 적용하게 해주는 데코레이터 패턴을 응용한 것)

2. **자바 언어의 한계를 넘어서는 언어의 확장을 이용하는 방법** (AspectJ)

<br>

### 👀 AOP의 적용 단계
#### 적용 1단계 : 미리 준비된 AOP 이용
- 트랜잭션

- `@Configurable` 애노테이션

#### 적용 2단계 : 전담팀을 통한 정책 AOP 적용
#### 적용 3단계 : AOP의 자유로운 이용

<br>

## 포터블 서비스 추상화(PSA)
### ✅ PSA란?
> 환경과 세부 기술 변화에 관계없이 일관된 방식으로 기술에 접근할 수 있게 해주는 것
>
>Portable Service Abstraction

서비스 추상화를 위해 필요한 기술은 DI뿐

결국 DI 응용 방법의 한 가지이므로, DI를 적극 활용해서 개발한다면 서비스 추상화는 자연스럽게 만들어 쓸 수 있음
