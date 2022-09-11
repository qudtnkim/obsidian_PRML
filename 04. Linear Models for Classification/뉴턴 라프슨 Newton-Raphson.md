# Newton's method
#뉴턴랩슨법 #뉴턴법
#newtons_method 의 기본적인 알고리즘은 다음같다.

optimize 함수 J(w)를 2차함수로 근사하기 위해서, 그 2차함수의 최소점(W1) 으로 파라미터를 update 하는 것이다. 

근사에 사용한 2차함수의 최소점 $w_{n}$ 으로 파라미터를 update 하는 것이 뉴턴 메소드의 기본적인 알고리즘. 

==이는 learning rate가 고정된 gradient decent보다 획기적으로 빠르게 최소점을 향해 간다.==

==그러나 이경우 반드시 오차함수 J(W)가 convex 해야한다는 것이 가정되어야한다.==

다시 말해 J(w)의 Hessian Matrix가 모든 Eigenvalue를 양수로 가지고 있어야한다는 의미이기도 하다.

Optimize 함수 J(W)를 2차 함수로 근사화 할 때, 2차 [[테일러 전개]]를 사용한다.

![[Pasted image 20220831221222.png]]


3번째 줄에서의 w의 update 과정을 보면 J(w)를 2번 미분한 Hessian 과 1번 미분한 Gradient 를 볼 수 있다. 

매순간의 HEssian inverse matrix 가 learning rate의 역할을 하고 있어 곡률 특성을 반영한 빠른 Weight Update가 이루어 진다.

