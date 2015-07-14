# polymorphism
sample

// polymorphism sample program
// it is a static method of method overloading
class overloading
{
	public int add(int x,int y)
	{
		return x+y;
	}
public int add(int x,int y,int z)
	{
		return x+y+z;
	}
public int add(double x,int y)
	{
		return (int)x+y;
	}
public int add(int x,double y)
	{
		return x+(int)y;
	}
}
	class test
	{
		public static void main(String []args)
	{
	overloading o=new overloading();
System.out.println("1st method " + o.add(4,8));
System.out.println("2st method " + o.add(4,8,9));
System.out.println("3st method " + o.add(4.7,8));
System.out.println("4st method " + o.add(4,8.2));
	}

	}
