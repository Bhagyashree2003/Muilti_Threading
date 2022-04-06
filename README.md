# Muilti_Threading
java cod of multiple threading

class mythread extends Thread

{

public void run()

{
		int i=0;
    
		while(i<40)
    
		{
    
			System.out.println("My thread is running");
      
			System.out.println("I'M Happy..");
      
			i++;
      
		}
    
	}
  
}

class mythread1 extends Thread

{

	public void run()
  
	{
		int i=0;
    
		while(i<40)
    
		{
    
			System.out.println("My thread1 is running");
      
			System.out.println("I'M sad..");
      
			i++;
      
		}
    
	}
  
}

class multi_threading

{

	public static void main(String args[])
  
	{
  
		mythread m=new mythread();
    
		mythread1 m1=new mythread1();
    
		m.start();
    
		m1.start();
    
	}
  
}
