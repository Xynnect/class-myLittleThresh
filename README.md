
public class myLittleThresh extends Thread{

	/**
	 * @param args
	 */
	public static void main(String[] a) {
		// TODO Auto-generated method stub
		myLittleThresh t = new myLittleThresh();
		t.start();
		System.out.println("This is printed from the application thread");

	}
	public void run(){
	System.out.print("This is printed by an extra thread");	
	}

}

