# Occurance-of-character-in-java
//
import java.util.*;
public class Pract {

	public static void main(String[] args)
	{
		
		String str = "SSuuiJJiiT";
		char[] ch = str.toCharArray();
		int c=0,cap=0;
		for(int i =97,m=65;i<123||m<97;i++,m++)
		{
			for(int k=0;k<ch.length;k++)
			{
				if((char)i==ch[k])
				{
					c++;
				}
				if((char)m==ch[k])
				{
					cap++;
				}
			}
			if(c>=1)
			{
				System.out.println((char)i+" "+c);
			}c=0;
			
			if(cap>=1)
			{
				System.out.println((char)m+" "+cap);
			}cap=0;
		}
	
	}

}



