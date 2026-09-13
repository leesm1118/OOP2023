# OOP2026
### Homework1
```java
public class hellowold {
	 public static void main(String []args){
		 int i , j; 
		 for(i=0; i<10; i++) {
			  for(j=0; j<=i; j++) {
			    System.out.print("#");
			  }
			  for(; j<=10; j++) {
			    System.out.print(" ");
			  }
			  System.out.println();
			}
		 for(i=0; i<=10; i++) {
			  for(j=0; j<=10-i; j++) {
			    System.out.print("#");
			  }
			  for(; j<=10; j++) {
			    System.out.print(" ");
			  }
			  System.out.println();
			}
		 for(i=0; i<10; i++) {
			  for(j=0; j<=10-i; j++) {
			    System.out.print(" ");
			  }
			  for(; j<=10; j++) {
			    System.out.print("#");
			  }
			  System.out.println();
			}
		 for(i=0; i<=10; i++) {
			  for(j=0; j<=i; j++) {
			    System.out.print(" ");
			  }
			  for(; j<=10; j++) {
			    System.out.print("#");
			  }
			  System.out.println();
			}
}
}
```
![Alt homework11](./images/homework1.jpg)

### Homework2
```java
public class Main {
    public static void main(String[] args) {
        int a = 1;
        int b = 1;
        for(int i=1; i<=20; i++) {
            System.out.print(a + " ");
            int next = a + b;
            a = b;
            b = next; 
        }
    }
}
```
![Alt homework11](./images/homework2.png)

### Homework3
```java
public class Main {
    public static void main(String[] args) {
        int a = 1;
        int b = 2;
        for (int i = 1; i <= 20; i++) {
             System.out.println(b + "/" + a + " = " + (double)b / a);
            
            int temp = a + b;
            a = b;
            b = temp;
        }
    }
}
```
![Alt homework11](./images/homework3.jpg)

### Homework4
```java
public class Main {
    public static void main(String[] args) {
        for (int i = 1; i <= 9; i++) {
            for (int j = 1; j <=9; j++) {
                System.out.printf("%d*%d=%-2d\t", j, i, j * 1);
            }
            System.out.println();
        }
       
    }
}
```
![Alt homework11](./images/homework4.jpg)

### Homework5

### Homework6
```java
public class Binomial {
    public static void main(String[] args) {
        int binomial[][] = new int[7][7];
        for (int i = 0; i < 7; i++) {
            binomial[i][0] = 1;
            binomial[i][i] = 1;

            for (int j = 1; j < i; j++) {
                binomial[i][j] =
                    binomial[i - 1][j - 1] + binomial[i - 1][j];
            }
        }
        for (int i = 0; i < 7; i++) {
            for (int j = 0; j <= i; j++) {
                System.out.print(binomial[i][j] + " ");
            }
            System.out.println();
        }
    }
}
```
![Alt homework11](./images/homework6.jpg)
