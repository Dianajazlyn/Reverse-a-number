import java.util.Scanner,
class ReverseInt
{
Static int reverse(int n)
{
  int rev=0;digit;
  while(n!=0)
  {
    digit=n%10;
    rev=rev*10+digit;
    n=n/10;
  }
  return rev:
}
Public Static void main(String args[])
{
Scanner ip= new Scanner(System.in);
int num=ip.nextInt();
int rev=reverse(num);
System.out.println("Reversed Num="+res);
}
}
    
