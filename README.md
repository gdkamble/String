public class compareTo_String {

	public static void main(String[] args) 
	{
		String s1="om";
		String s2="Om";
		System.out.println(myEqual(s1,s2));

	
	}

	private static boolean  myEqual(String s1, String s2) {
		// TODO Auto-generated method stub
		if(s1.length()==s2.length())
		{
			for(int i=0;i<s1.length();i++)
			{
				if(s1.charAt(i)!=s2.charAt(i))
					return false;
			}
					return true;
					
			}
			return false;
	}

}
	
	
