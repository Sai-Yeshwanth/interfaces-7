interface A
{
	void display();
}
interface B extends A
{
	void show();
}
class C implements A
{
	public void display()
	{
		System.out.println("Im from interface A");
	}
	public void show()
	{
		System.out.println("Im from interface B");
	}
}
class Jala 
{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 C c = new C();
			 c.display();
			 c.show();
		
	}
}

