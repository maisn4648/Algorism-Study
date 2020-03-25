# Algorism-Study


ch.1  기본 알고리즘


point 1) if else 문의 default
 
 문미에 else if 로 끝난다면 그 뒤에 else ; 가 추가로 붙게 됨.

point 2) do{} while(조건문);



      Q17) n단의 피라미드를 출력하는 함수를 작성하라
      
      point) 한 상황에 두 지표를 모두 운용해야할때, 각 지표별로 조건문을 활용해 해결한다.
      
      ex) 한 줄에 0과 1 이 작성되는 조건이 다르다면 해당 조건에 맞게 조건문을 작성하면 된다.
      
      
      for(i=1;i<=n;i++) {
      
      for(j=1;j<=n-i;j++)
        printf(' ');
      for(j=1;j<=2*(i-1)+1;j++)
        printf('*');
       printf('\n');
       
       
       +a) 조건문 사용시 1로 시작시 <=를 사용
                        0으로 시작시 < 를 사용해야한다.
      
      
      
      
