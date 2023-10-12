# include <stdio.h>
int main() {
char status;
char gender;
int age;
printf("Enter Maritul Status(Married/Unmarried) and Gender(boy/girl): ");
scanf("%c %c",&status,&gender);
printf("Enter Age: ");
scanf("%d",&age);
if(((status=='M')||(status=='U'))&&(gender=='b')&&(age>=30)||(status=='U')&&(gender=='g')&&(age>=25)){
    printf("You Are Eligible For Driving Job In This Company");
}else{
    printf("You Are Not Eligible");
}
    return 0;
}


