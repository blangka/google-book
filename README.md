# 구글 엔지니어는 이렇게 일한다 책을 읽으며

구글은 지속 가능한 서비스를 만들기 위해 어떤 방식으로 일하고 있는지 알아보고자 책을 읽어보았다.

## 책의 핵심 내용

### 소프트웨어의 핵심 가치는 지속 가능성 (Sustainability)
- 지속 가능성을 위해선 빠른 피드백과 실험을 통한 빠른 배포가 필요하다.  
- 기대 수명과 업그레이드의 중요성 관계는 수명이 길수록 기아 급수적으로 늘어난다.

### 하이럼의 법칙
- 시스템의 복잡성은 시간이 지남에 따라 지수적으로 증가한다.
- 복잡성을 줄이기 위해선 단순성을 추구해야 한다.
- API 사용자가 충분히 많다면 API 명세에 적힌 내용은 중요하지 않다. 시스템의 모든 행위는 누군가는 이용하게 될것이기 떄문이다.

### 개발 과정의 문제점은 일찍 발견 할수록 비용이 적게 든다.

### 팀워크 이끌어 내기
- 숨기는 것은 해롭다. 코드, 실패, 잘못된 결정 등을 숨기지 말자.
- 버스 지수(버스에 치어서 일을 할수 없게 될 떄 프로젝트가 망하게 되는지 지수)를 줄이자. 프로젝트의 필요한 지식과 노하우를 분산 시키자.
- 상호 작용이 중요하다. 겸손, 존중, 신뢰 3개의 기둥이 중요하다.
- 빠르게 실패하고 반복하자.
- 비난 없이 받아 들이자.
- 항상 배우고 항상 질문하라.

### 관리자 TL 이 된다는 것  
경력의 대부분을 개발자로 지낸 사람은 하루의 시작과 끝을 코드, 설계 문서, 해결한 버그더미를 가르키며 보람을 느낀다.
하지만 관리자로 일을 하게 되면 하루의 시작과 끝을 팀원들의 일을 도와주는 것으로 보게 된다.   
결국 이런 생각을 하게 된다. 
<span style="color:red">
오늘 한 일이 하나도 없군
</span>
  
하지만 관리자로 일을 하게 되면 팀원들의 성장을 도와주는 것이 가장 중요한 일이 된다.

그럼에도 관리자를 선택해야 하는 순간은 다음과 같다
- 경력 스펙트럼의 확장
- 동료들로 꾸려진 팀 하나가 성장하고 발전하는 것을 지켜보는 것이 즐거운가?
- 사실 알고보면 적성에 맞을지도?? 지도하고 , 도와주고, 팀을 보호하는 것이 매우 뛰어나다는 사실을 깨닫곤한다. 

### 규칙
프로세스를 통한 규칙으로 좋은 행동을 장려 하고 나쁜 행동을 억제 해야 한다.  
규칙은 다음과 같은 특징을 가지고 있어야 한다.
- 명확하고 간단하다.
- 쉽게 적용 가능하다.
- 규칙의 양을 최소화 한다.
- 일관 되어야 한다.
- 오류를 내기 쉽거나 예상과 다른 동작할 여지가 있는 구조를 피하자.
- 모범 사례 강제하기

### TL이 피해야 하는 것 안티패턴
- 만만한 사람 고용하기
- 저성과자 방치하기
- 사람 문제 무시하기
- 만인의 친구 되기
- 채용 기준 타협하기
- 팀을 어린이 처럼 대하기

### TL이 해야 하는 것
- 자존심 버리기
- 마음 다스리기
- 촉매자 되기
- 장애물 치우기
- 선생이자 멘토 되기
- 명확한 목표 세우기
- 정직하기
- 행복한지 확인하기

### 코드 리뷰
- 그린 필드 리뷰와 새로운 기능 개발
  - 완전히 새로운 코드를 대상으로 하는 가장 드문 유형의 코드 리뷰
  - 유지 보수가 쉬워야함
  - 충분한 문서 필요
- 동작 변경, 개선, 최적화
  - 죽은 코드 제거
  - 테스트 코드 필요
- 버그 수정과 롤백
  - 문제되는 부분만 수정(온전히 버그 잡는데만 집중)
  - 원자적으로 해결
- 리팩터링과 대규모 변경
  - 도메인 전문가와 엔지니어들의 리뷰 필요

****
## 현재 나의 상태
책을 읽고 나의 상태를 객관적으로 살펴보았다.
- 테스트 코드를 작성하고, 코드 리뷰를 통해 빠른 피드백을 받고 있는가?
> 형식적인 테스트 코드를 작성하고 있고 더 많은 시간을 자동화에 투자 하고 있지 못하다.  
> 코드 리뷰는 팀원들과 함께 하고 있지만, 시간적 제약으로 만족할 만큼 리뷰를 하고 있지 못하다.
- 팀워크의 3개의 기둥을 잘 지키고 있는가?
> 업무의 분배나 진행 사항에 대한 공유는 충분한 의견을 청취 하지 못하고 개인의 판단으로 진행하는 경우가 많다.  
> 제한적인 일정, 여러 조직관의 커뮤니케이션 비용 등의 문제로 인해 상호 작용이 부족하지만 나 자신의 핑계가 아닌가 하고 되돌아 볼 필요가 있다.
- 버스 지수를 줄이고 있는가?
> 고질적인 나의 잘못인것 같다. 프로젝트의 핵심 정보에 대해서 주도적으로 교통 정리를 하며 공유가 미흡하다.  
> 많은 부분은 팀원을 신뢰하며 위임할 필요가 있다.

