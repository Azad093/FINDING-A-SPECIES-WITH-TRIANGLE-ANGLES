 int angle1,angle2,angle3;
    printf("enter a three angles: \n");
    scanf("%d %d %d",&angle1,&angle2,&angle3);

    if(angle1+angle2+angle3 != 180 ){   // girdiğimiz sayı 180e eşit olmalı

        printf("Triangles will not be formed with the angles you enter.");

    }else{
       }if(angle1 == 60 && angle2 == 60 && angle3 == 60){
           printf("equilateral triangle is formed");

       }else if(angle1 ==angle2 || angle1 ==angle3  || angle2  == angle3){

          printf("isosceles triangle formed");
       }else{
          printf("polygonal triangle");
       }

