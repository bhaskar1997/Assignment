import java.util.Scanner;
public class NoOfOccurChar
{
public static void main(String[] args)

{
	int count=0;
	int i,j,k;
	boolean flag;
	String str = "aaabbcdde";

	char[] arr = str.toCharArray();
	int len = arr.length;
	for(i=0;i<len;i++)
	{
	flag=true;
	for(k=0;k<i;k++)
	{
		if(arr[i] == str.charAt(k))
		{	
		flag=false;
		}
	}
	if(flag)
	{
		for(j=0;j<len;j++)
		{
			if(arr[i] == str.charAt(j))
			{
			count++;
			}
		}

	System.out.println(arr[i]+ "->" +count);
	count= 0;
	}
	}

	System.out.println("captalize the alternate char of the string");

	for(i=0;i<arr.length;i++)
	{
		char ch = str.charAt(i);
		if(i % 2 == 0)
		 {
        		System.out.print(Character.toLowerCase(ch));
    		} 
                else 
		{
        		System.out.print(Character.toUpperCase(ch));
		}
	}
	System.out.println();

}
}
