## 블록체인이 뭘까?

한문장으로 정의해보자 : 
* 다수의 전통적인 데이타베이스는 단일 혹은 소수의 서버에 의존, 기술적 실패와 사이버 공격에 취약함

    -> 블록체인 데이터는 수천개의 분산화된 네트워크 노드에 저장, 시스템과 데이터는 기술적 실패와 악의적 공격에 대한 저항력, 즉 보안성이 강화됨
* 안정성 : 승인된 블록은 되돌리기 어려움, 데이터가 블록체인에 기록된 다음 삭제하거나 변경하기 어려움
 
    -> EX) 재무기록 저장, 감사 추적을 필요로 하는 데이터


### Blockchain

 관리자 없이 자율적으로 동작하는 분산 시스템 기술을 통칭합니다. 화폐 거래 내역을 '블록'이라는 데이터 단위로 저장한 후 해당 블록의 해시값을 다른 블록에 저장시켜 체인 형태의 연결고리를 만듭니다. 
 비트코인 등장 이후 블록체인을 다양한 분야에 응용하려는 연구가 활발합니다. 상황에 따라 관리자가 존재하는 시스템이나 블록을 사용하지 않는 시스템도 있습니다.
 
 블록체인은 데이터 분산 처리 기술입니다. 즉, 네트워크에 참여하는 모든 사용자가 모든 거래 내역 등의 데이터를 분산, 저장하는 기술을 지칭하는 말입니다. 블록들을 체인 형태로 묶은 형태이기 때문에 블록체인이라는 이름이 붙었죠. 블록체인에서 '블록'은 개인과 개인의 거래(P2P)의 데이터가 기록되는 장부가 됩니다. 이런 블록들은 형성된 후 시간의 흐름에 따라 순차적으로 연결된 '사슬(체인)'의 구조를 가지게 됩니다. 모든 사용자가 거래내역을 보유하고 있어 거래 내역을 확인할 때는 모든 사용자가 보유한 장부를 대조하고 확인해야 합니다. 이 때문에 블록체인은 '공공 거래장부' 또는 '분산 거래장부'로도 불리기도 합니다.

![image](https://user-images.githubusercontent.com/47058441/65088741-62d74200-d9f5-11e9-9f56-50c2225ad425.png)

#### 블록체인의 특징

 블록체인은 '분산저장'을 한다는 점이 특징입니다. 기존 거래 방식에서 데이터를 위,변조하기 위해선 은행의 중앙서버를 공격하면 가능했습니다. 최근 몇몇 은행 전산망 해킹 사건이 일어났다는 점을 생각해보면 현실적인 위협이다. 그러나 블록체인은 여러 명이 데이터를 저장하기 때문에 위,변조가 어렵습니다. 블록체인 네트워크를 위, 변조하기 위해서는 참여자의 거래 데이터를 모두 공격해야 하기 때문에 사실상 해킹은 불가능하다고 여겨집니다.
 
 또한 블록체인은 중앙관리자가 필요 없다는 점도 특징으로 꼽힙니다. 은행이나 정부 등 중앙기관이나 중앙 관리자가 필요했던 것은 공식적인 증명, 등기, 인증 등이 필요했기 때문이죠. 그러나 블록체인은 다수가 데이터를 저장, 증명하기 떄문에 중앙관리자가 존재하지 않게 됩니다.


### Ethereum

암호화폐 종류의 하나로 알려져 있지만 블록체인 기반애플리케이션을 개발하고 운용하는 플랫폼이라는 뜻도 있습니다. 튜링 완전한 프로그래밍 언어 기반의 애플리케이션을 개발할 수 있습니다. 비트코인과는 근본적으로 구조가 다릅니다.

### Smart Contract

IT 기술을 이용해 계약 내역을 자동으로 실행하는 것을 스마트 계약이라고 합니다. 예를 들어 전자화폐의 잔액이 일정 액수 이하면 신용카드로 자동으로 충전하는 서비스도 스마트 계약의 하나입니다. 이더리움은 스마트 계약을 적용한 대표적인 블록체인 기반 애플리케이션 플랫폼입니다.

<블록체인의 스마트 계약; 현실의 거래 가치 기준을 프로그램으로 구현한 후 설정한 기준을 만족하면 계약을 자동으로 실행합니다.>
* 상대를 신뢰하지 않아도 거래에 문제가 발생하지 않습니다. -> 상대를 믿지 못하더라도 신뢰할 수 있는 거래를 자동으로 실행합니다. '탈중앙화' 블록체인은 거래 정보를 블록에 저장해 누구든 참고할 수 있으므로 조작하기 어렵습니다. 투명한 거래가 가능합니다.
* 중개자가 필요 없으므로 비용을 절감할 수 있습니다. -> 수수료 X

### 작업증명(Proof of Work, PoW) 알고리즘

임의의 참여자들이 상호 운용하는 시스템(혹은 프로토콜)은 시스템에 문제를 발생시키는 참여자가 있어도 제대로 동작하게 만들어야 합니다.
작업 증명 알고리즘은 채굴했다는 사실을 증명한 후에 블록을 생성하게 만드는 방법입니다.(비트코인에서는 채굴할 때 이 알고리즘을 활용) 동시에 증명 없이는 블록을 생성할 수 없게 하는 역할도 합니다. 대량의 컴퓨팅 자원을 이용하는 시스템에서 많이 채택하는 알고리즘입니다.\
작업 증명 알고리즘 이외에 지분증명(Proof of Stake,PoS)과 존재 증명(Proof of Existence,PoE) 알고리즘 등이 있습니다.
'Proof of ~'로 시작하는 용어는 기술적인 의미뿐만 아니라 개념을 설명할 때도 자주 사용하므로 상황에 따라 용어 각각의 정확한 의미를 이해해야 합니다.


## 블록체인/스마트 계약의 취약점과 공격원리

참고 url: https://dasp.co/      &&&     url: https://allblackk.tistory.com/357

#### dasp(Decentralized Application Security Project)_top10

1. Reentrancy

이 악용 사례는 많은 다른 사람들에 의해 여러 번 검토 과정에서 누락되었다. 즉, 검토자가 한 번에 하나의 기능을 검토하는 경향이 있으며 보안 서브 루틴에 대한 호출이 안전하고 의도 된대로 작동한다고 가정한다.

Reentrancy 공격, 재진입성 공격, 가장 유명한 Ethereum 취약점은 처음 발견되었을 때 모든 사람을 놀라게 했다. 그것은 Ethereum의 단단한 포크를 가져온 수백만 달러의 강도로 처음 발표되었다. 재호출은 외부 계약 호출이 초기 실행이 완료되기 전에 호출 계약에 대한 새 호출을 허용 할 때 발생한다. 함수의 경우 이것은 신뢰할 수없는 계약을 호출하거나 외부 주소로 낮은 수준의 함수를 사용하여 계약 실행 상태가 변경 될 수 있음을 의미한다.

2. Access Control

패리티 월렛 라이브러리 계약을 일반 멀티 시그마 지갑으로 전환하고 initWallet 함수를 호출하여 라이브러리의 소유자가 될 수 있었다.

액세스 제어 문제는 스마트 계약뿐만 아니라 모든 프로그램에서 공통적이다. 사실 OWASP 상위 10 위는 5위다. 하나는 대개 공개 기능이나 외부 기능을 통해 계약 기능에 액세스한다. 안전하지 않은 가시성 설정을 사용하면 공격자가 계약의 개인 값이나 논리에 직접 액세스 할 수 있지만 액세스 제어 바이 패스는 때로는 더 미묘하다. 이 취약점은 계약자가 tx.origin 호출자의 유효성을 검사하고 긴 권한 부여 논리를 처리 하고 프록시 라이브러리 또는 프록시 계약에서 require 무분별하게 사용 하도록 비추천된 메소드를 사용할 때 발생할 수 있다. delegatecall.

3. Airthmatic

오버플로우 조건은 잘못된 결과를 제공하며 특히 가능성이 예상되지 않은 경우 프로그램의 안정성과 보안을 손상시킬 수 있다.

정수 오버 플로우와 언더 플로우는 새로운 취약성 클래스는 아니지만 서명되지 않은 정수가 널리 사용되는 대부분의 개발자가 간단한 int유형 (종종 부호가있는 정수)에 익숙한 스마트 계약에서 특히 위험하다. 오버플로우가 발생하면 많은 양성으로 보이는 코드 경로가 도난 또는 서비스 거부 공격의 매개체가 된다.

4. Unchecked Low Level Calls

가능할 때마다 낮은 수준의 "전화"사용은 피해야 한다. 반환 값이 제대로 처리되지 않으면 예기치 않은 동작이 발생할 수 있다.

견고성의 깊은 특징 중 하나는 낮은 수준의 함수다. call(), callcode(), delegatecall()와 send(). 그들의 오류에 대한 설명에서의 행동은 다른 Solinity 함수와는 상당히 다르다. 왜냐하면 그것들은 전파되지 않기 때문에 현재 실행의 완전한 복귀로 이어지지 않을 것이기 때문이다. 대신, 그들은에 설정된 부울 값을 반환 할 것이고 false 코드는 계속 실행될 것이다. 개발자를 놀라게 할 수 있으며 그러한 저급 호출의 반환 값을 확인하지 않으면 페일 오픈 및 기타 원치 않는 결과가 발생할 수 있다. 즉 보내기 실패 할 수 있다.

5. Denial of Service

가스에 도달 제한, 예상치 못한 던져, 예기치 않은 살인, 액세스 제어 위반.

Ethereum의 세계에서는 서비스 거부가 치명적이다. 다른 유형의 응용 프로그램도 결국 복구 될 수 있지만 스마트 계약은 이러한 공격 중 하나에 의해 영원히 오프라인 상태가 될 수 있다. 여러 가지 방법으로 트랜잭션 수신자가 될 때 악의적인 행동, 기능을 계산하는 데 필요한 인위적으로 가스 증가, 스마트 계약의 개인 구성 요소에 액세스 하기 위한 액세스 제어 악용, 혼동 및 과실 사용 등 여러 가지 방법으로 서비스 거부가 발생한다. 공격 클래스에는 여러 가지 변형이 포함되어 있으며 앞으로 수 년 동안 많은 개발이 이루어질 것이다.

6. Bad Randomness

이 계약은 block.number 연령의 유효성에 대한 검증이 불충분하기 때문에 예측 가능한 승자를 공개하기 전에 256 블록을 기다린 미지의 플레이어에게 400 ETH가 손실되었다.

Ethereum에서는 무작위성을 얻기가 어렵다. Solidity는 예측하기 어려운 값에 액세스 할 수 있는 함수와 변수를 제공하지만 일반적으로 광의의 영향을 받는 것처럼 대중보다 더 대중적이다. 이러한 임의성의 출처는 어느 정도 예측 가능하기 때문에 악의적인 사용자는 일반적으로 이를 복제하고 예기치 않은 기능에 의존한다.

7. Front Running

시간의 사용 (TOCTOU) 대의 검사 시간 , 경쟁 조건 , 거래 주문 의존도 (TOD)
cf). 밝혀지면 작동중인 프론트 - 러닝 알고리즘을 얻으려면 약 150 줄의 파이썬이 필요.

광부는 외부 소유 주소 (EOA)를 대신하여 코드 실행에 대한 가스 요금을 통해 항상 보상을 얻으므로 사용자는 트랜잭션을 보다 신속하게 채굴 할 수 있도록 더 높은 수수료를 지정할 수 있다. Ethereum 블록 체인은 공개되어 있으므로 누구나 다른 사람들의 보류중인 거래 내용을 볼 수 있다. 즉, 특정 사용자가 퍼즐이나 다른 중요한 비밀에 대한 솔루션을 공개하는 경우 악의적인 사용자가 솔루션을 훔쳐 원래 거래를 선점하기 위해 더 높은 수수료로 거래를 복사 할 수 있다. 똑똑한 계약의 개발자가 조심하지 않으면 이러한 상황이 실제적이고 파괴적인 선행 공격이 될 수 있다.

8. Time Manipulation

타임 스탬프 종속성이라고도 한다. 광부가 계약에 대한 지분을 보유하고 있다면 광산 채굴 블록에 적절한 타임 스탬프를 선택함으로써 이점을 얻을 수 있다.

게임의 특정 시간에 토큰 판매를 잠금 해제하여 자금을 확보하는 것에서 계약은 때로는 현재 시간에 의존해야 한다. 이것은 대개 Solidity에서 block.timestamp별칭 now을 통해 이루어진다. 광부로부터 그 가치는 얻어진다. 트랜잭션의 광부는 광산이 발생한 시간을 보고하는 데 여유가 있기 때문에 좋은 스마트 계약은 광고되는 시간에 크게 의존하지 않는다. 그 주 block.timestamp에서 논의 된 바와 같이 때때로 난수의 생성에 사용되는 (MIS) 인 #4-6. 나쁜 임의성(Bad Randomness).

9. Short Address

오프 체인 문제, 클라이언트 취약점이라고 한다. 토큰 전송에 대한 데이터를 준비하는 서비스는 사용자가 20 바이트 길이의 주소를 입력한다고 가정했지만 주소의 길이는 실제로 확인되지 않았다.

짧은 주소 공격은 EVM 자체가 잘못 채워진 인수를 받아들이는 부작용이다. 공격자는 특수하게 조작 된 주소를 사용하여 잘못 코딩 된 클라이언트가 인수를 잘못 인코딩하여 트랜잭션에 포함시키도록 하여 이를 악용 할 수 있다. EVM 문제입니까, 고객 문제입니까? 대신 스마트 계약으로 수정해야합니까? 모든 사람들이 다른 견해를 가지고 있지만 사실은 많은 양의 에테르가이 문제로 직접 영향을 받을 수 있다는 것이다. 이 취약점은 아직까지 야생에서 악용되지는 않았지만 클라이언트와 Ethereum 블록 체인 간의 상호 작용으로 인해 발생하는 문제를 잘 보여준다. 다른 오프 체인 문제가 존재한다. 중요한 것은 특정 자바 프론트 엔드, 브라우저 플러그인 및 공용 노드에 대한 Ethereum 에코 시스템의 깊은 신뢰다.

10. Unknown Unknowns

더 많은 보안 감사 또는 더 많은 테스트가 차이를 만들지 않았을 것이라고 생각한다. 가장 큰 문제점은 리뷰어가 무엇을 찾아야할지 몰랐다는 것이다.

Ethereum은 아직 초기 단계에 있다. 똑똑한 계약을 개발하는 데 사용되는 주요 언어인 Solidity는 아직 안정적인 버전에 도달하지 못했고 생태계의 도구는 아직 실험적이다. 가장 위험한 스마트 계약 취약성 중 일부는 모든 사람을 놀라게 했으며, 예기치 않게 또는 똑같이 파괴적인 또 다른 공격이 없을 것이라고 믿을만한 이유가 없다. 투자자가 복잡하지만 가벼운 감사를 거친 코드에 많은 돈을 투자하기로 결정하는 한, 새로운 발견이 계속해서 끔찍한 결과를 낳을 것이라고 보고 있다. 형식적으로 똑똑한 계약을 확인하는 방법은 아직 성숙하지는 않지만 오늘날의 불안정한 현상을 극복하는 방법으로 큰 약속을 갖고있는 것으로 보인다. 새로운 종류의 취약점이 계속 발견되면 개발자는 계속해서 문제를 해결해야 한다. 악의적인 사람들이하기 전에 새로운 도구를 개발해야 한다. 상위 10 위는 스마트 계약 개발이 꾸준하고 성숙해질 때까지 빠르게 발전 할 것이다.












