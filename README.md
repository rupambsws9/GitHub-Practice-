# include <stdio.h>
<br>
int main() {
    <br>
char status;
<br>
char gender;
<br>
int age;
<br>
printf("Enter Maritul Status(Married/Unmarried) and Gender(boy/girl): ");
<br>
scanf("%c %c",&status,&gender);
<br>
printf("Enter Age: ");
<br>
scanf("%d",&age);
<br>
if(((status=='M')||(status=='U'))&&(gender=='b')&&(age>=30)||(status=='U')&&(gender=='g')&&(age>=25)){
    <br>
    printf("You Are Eligible For Driving Job In This Company");
    <br>
}else{
    <br>
    printf("You Are Not Eligible");
    <br>
}<br>
    return 0;<br>
}


