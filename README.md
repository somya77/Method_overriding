# Method_overriding
class Father
{
int a=100;
 void cal()
{
 System.out.println("SUPER CLASS FATHER");
}
}
class Son extends Father
{
 int b=200;
 void cal()
{
  int sum=a+b;
  System.out.println("SUB CLASS SON");
System.out.println("Sum:"+sum);
}
}
class Daughter extends Father
{
int c=2;
void cal()
{
int mul=a*c;
 
 System.out.println("SUB CLASS DAUGHTER");
System.out.println("Mul:"+mul);
}
}
class Test20
{
public static void main(String args[])
{
Father f=new Father();
 Son objs=new Son();
 Daughter objd=new Daughter();
 f.cal();
 objs.cal();
 objd.cal();
}
}

