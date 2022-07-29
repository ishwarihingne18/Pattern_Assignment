# Pattern_Assignment
My pattern programs
class Pattern_23
{
	public static void main(String args[])
	{
		int i,j;
		
		for(i=1;i<=5;i++)
		{
			for(j=1;j<=5-i;j++)
			System.out.print(1);

			for(j=1;j<=i;j++)
			{
				System.out.print(i);
				
			}

		System.out.println();
		}		
	}
}
