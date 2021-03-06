## 1. 깨끗한 코드
- ### 코드가 존재하리라
  코드는 요구사항을 상세히 표현하는 수단이다.  
  어느 수준에 이르면 코드의 도움 없이 요구사항을 상세하게 표현하기란 불가능하다.  
  기계가 실행할 정도로 상세하게 요구사항을 명시하는 작업, 바로 이것이 프로그래밍이고 이렇게 명시한 결과가 코드다.

  그러므로 코드도 항상 존재하리라.

- ### 나쁜 코드
  나쁜 코드는 왜 짜는 것인가? 시간이 없어서? 서두르느라?  
  우리 모두는 자신이 짠 쓰레기 코드를 보면서 나중에 손보겠다고 생각한 경험이 있다.  

  그때 그 시절 우리는 르블랑의 법칙을 몰랐다.  
  나중은 결코 오지 않는다.

- ### 나쁜 코드로 치르는 대가
  나쁜 코드는 개발 속도를 크게 떨어뜨린다.  
  코드를 고칠 때마다 엉뚱한 곳에서 문제가 생긴다. 매번 얽히고설킨 코드를 '해독'해서 얽히고설킨 코드를 더한다. 시간이 지나면서 쓰레기 더미는 점점 높아지고 깊어지고 커진다.

  나쁜 코드가 쌓일수록 팀 생산성은 떨어진다. 복구를 시도하지만 결국 나쁜 코드를 더 많이 양산한다. 생산성은 더더욱 떨어져 거의 0이 된다.

  **원대한 재설계의 꿈**  
  나쁜 코드로 인해 결국 재설계팀이 만들어져 재설계를 시작해서 새 시스템을 내놓기로 한다. 단, 기존 시스템 기능을 100% 제공해야 하고 기존 시스템에 가해지는 변경도 모두 따라잡아야 한다. 이 과정은 매우 오래 걸릴 수 있다. 새 시스템이 기존 시스템을 따라잡을 즈음이면 팀원들은 모두 팀을 떠났고 새로운 팀원들이 새 시스템을 설계하자고 나선다.

  시간을 들여 깨끗한 코드를 만드는 노력이 비용을 절감하는 방법일 뿐만 아니라 전문가로서 살아남는 길이라는 사실을 인정하리라.

  **태도**  
  좋은 코드가 어째서 순식간에 나쁜 코드로 전락할까? 우리는 온갖 이유를 들이댄다.  
  요구사항이 변해서, 일정이 촉박해서, 상사의 압박탓이라고 한다.  
  하지만 이런 상황에도 좋은 코드를 사수하는 일은 바로 프로그래머의 책임이다.

  나쁜 코드의 위협을 이해하지 못하는 관리자 말을 그대로 따르는 행동은 전문가답지 못하다.

  **원초적 난제**  
  나쁜 코드가 업무 속도를 늦춘다는 사실을 알고 있지만 기한을 맞추려면 나쁜 코드를 양산할 수 밖에 없다고 느낀다. 즉, 빨리 가려고 시간을 들이지 않는다.

  그러나 나쁜 코드를 양산하면 기한을 맞추지 못한다. 기한을 맞추는 유일한 방법은, 그러니까 빨리 가는 유일한 방법은, 언제나 코드를 최대한 깨끗하게 유지하는 습관이다.

  **깨끗한 코드라는 예술?**  
  '코드 감각'이 없는 프로그래머도 때로는 나쁜 모듈을 알아본다. 하지만 그것으로 끝이다.  
  '코드 감각'이 있는 프로그래머는 나쁜 모듈을 보면 좋은 모듈로 개선할 방안을 떠올린다.

  **깨끗한 코드란?**  
  > 나는 우아하고 효율적인 코드를 좋아한다. 코드를 망치려는 유혹에 빠지지 않는다.
  
  > 깨끗한 코드는 잘 쓴 문장처럼 읽힌다.
  
  > 깨끗한 코드는 작성자가 아닌 사람도 읽기 쉽고 고치기 쉽다.
  
  > 깨끗한 코드는 언제나 누군가 주의 깊게 짰다는 느낌을 준다.
  
  > 코드를 읽으면서 짐작했던 기능을 각 루틴이 그대로 수행한다면 깨끗한 코드라 불러도 되겠다.

- ### 우리는 저자다
  코드를 짤 때는 자신이 저자라는 사실을, 여러분의 노력을 보고 판단을 내릴 독자가 있다는 사실을 기억하라.

  코드를 읽는 시간 대 코드를 짜는 시간 비율이 10대 1을 훌쩍 넘는다. 새 코드를 짜면서 우리는 끊임없이 기존 코드를 읽는다. 기존 코드가 읽기 쉬우면 새 코드를 짜기도 쉽다.

  급하다면, 서둘러 끝내려면, 쉽게 짜려면, 읽기 쉽게 만들면 된다.

- ### 보이스카우트 규칙
  > 캠프장은 처음 왔을 때보다 더 깨끗하게 해놓고 떠나라.

- ### 결론
  이 책을 읽는다고 뛰어난 프로그래머가 된다는 보장은 없다.  
  나머진 여러분이 하기 나름이다.
