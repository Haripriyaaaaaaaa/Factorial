# Factorial
public static void main(String[] args){

Scanner sc=new Scanner(System.in);

int num;

long factorial=1;

System.out.println("Enter number:");

num=sc.nextInt();

for(int i=1;i<=num;i++)

{

factorial*=i;

}

System.out.printf("Factorial of %d=%d",num,factorial);

}

}

OUTPUT:

Enter number:

8

Factorial of 8=40320BUILD SUCCESSFUL
