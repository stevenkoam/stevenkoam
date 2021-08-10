#include <stdio.h>
int main()
{
           int score = 0;
           printf("점수를 출력하세요.:);
           scanf_s("%d", &score);
           if((score < 0) || (score > 100))
           printf("NA\n");
          else if(score >= 90)
           printf("A\n");
          else if(score >= 80)
           printf("B\n");
          else if(score >= 70)
           printf("C\n");
          else if(score >= 60)
           printf("D\n");
          else
           printf("F\n");
          return 0;
      }
           
           
           
