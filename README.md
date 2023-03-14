# Pattern
# CREATE A PROGRAM FOR THE FOLLOWING PATTERN 
![image](https://user-images.githubusercontent.com/104237399/224884785-0fd7cf26-5917-4122-bf1d-26211e50359f.png)
# INPUT CODE
~~~
public class Main
{
    public static void main(String[]args)
    {
        for (int i=1;i<=5;i++)
        {
            for(int j=1;j<=5;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
~~~
# OUTPUT
![Screenshot (73)](https://user-images.githubusercontent.com/104237399/224887247-ff4a14c8-e7e2-4508-b100-3ed767e06d4a.png)

# CREATE A PROGRAM FOR THE FOLLOWING PATTERN
![image](https://user-images.githubusercontent.com/104237399/224885186-0a2a5b07-841a-41be-a44b-a4488f71a050.png)
# INPUT CODE
~~~
Public class Main
{
    public static void main(String[]args)
    {
        int rows = 5;
        int count = 1;
        for (int i = rows; i >= 1; i--)
        {
            for (int j = 1; j <= count; j++)
            {
                System.out.print(" ");
            }
            for (int k = 1; k <= 2 * i - 1; k++)
            {
                System.out.print("*");
            }
            System.out.println();
            count++;
        }
    }
}
~~~
# OUTPUT 
![Screenshot (72)](https://user-images.githubusercontent.com/104237399/224886992-f10b274f-4b65-44af-a37f-5e6468480742.png)

# CREATE A PROGRAM FOR THE FOLLOWING PATTERN
![image](https://user-images.githubusercontent.com/104237399/224885481-7e8bbdca-3e30-4d02-8f65-009db832c5eb.png)
# INPUT CODE 
~~~
public class Main
{
    public static void main(String[]args)
    {
        int rows=5;
        for(int i=1; i<=rows;i++)
        {
            for(int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
        for(int i=rows-1;i>=1;i--)
        {
            for (int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
~~~
# OUTPUT

![P3](https://user-images.githubusercontent.com/104237399/224886735-1f232d64-20b9-46f4-a05b-20143f5c9893.jpg)




