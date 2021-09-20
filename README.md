public class Read_Csv
{
	public static void main(String[] args) 
	{
	
		File fi=new File("C://Users/Sushmitha/Desktop/TW/t8.shakespeare.txt");
		
		try
		{
			FileReader fr=new FileReader(fi);
			Scanner sc=new Scanner(fi);
			sc.useDelimiter(" ");
			
			while(sc.hasNext())
			{
				System.out.println(sc.next());
			}
			
		}
		catch(Exception e)
		{
			System.out.println(e);
		}		
	}

}
