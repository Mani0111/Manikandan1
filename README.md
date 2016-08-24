import java.util.Scanner;
public class positive
{
public static void main(String[] args)
{
Scanner in=new Scanner(System.in);
int a=in.nextInt();
int i=0,b,r=0;
if(a>1)
{
while(i<2)
{
b=a%10;
r=(r*10)+b;
a=a/10;
i++;
}
String s=String.valueOf(r);
StringBuffer s1=new StringBuffer(s);
s1.reverse();
System.out.println(s1);
}
else if(a<1)
{
System.out.println("0");
}
else
{
System.out.println("boundary condition");
}
