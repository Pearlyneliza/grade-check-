# grade-check-
To check the grade for 5 subjects

#include<stdio.h>
int main()
{
float s1,s2,s3,s4,s5,per;
printf("Enter marks of 5 subjects\n");
scanf("%f %f %f %f %f", &s1,s2,s3,s4,s5);
per=(s1+s2+s3+s4+s5)/5.0;
  if(per>=85)
{
 printf("Grade A\n");
}
else
{
  if(per>=70)
{
print("Grade B\n");
}
else
{
   if(per>=55)
   {
printf("grade C\n");
   }
   else
   {
if(per>=40)
{
printf("Grade D\n");
}
else
{
printf("failed!\n");
}
}
}
}
return 0;
}

