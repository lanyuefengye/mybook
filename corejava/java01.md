##java习题作业
***
+ 一、选择题：
 - 1-5:ADBBA
 - 6-10:CAADD
 - 11-15:BDDAC
 - 16-20:BDBDC
 - 21-22:CA
+ 二、填空题：
 -  1、float型浮点数
 -  2、7.5
 -  3、4
 -  4、20
+ 三、编程题：
 -  1、
 
 
 
   
   
         public class Zuoye01{
	public static void main(String[] args){
	 double n1,n2,n3;
	 n1=22;
	 n2=64;
	 n3=n1+n2;
	 System.out.println("n3 ="+n3);
	 System.out.println("n1-n2 ="+(n1-n2
	 System.out.println("n1*n2 ="+(n1*n2));
	 System.out.println("n1/n2 ="+(n1/n2));
	 System.out.println("n1%n2 ="+(n1%n2));}}



 -  2、
 
 
 
    public class ZuoYe02 {
		public static void main(String[] args){
		String str01 = JOptionPane.showInputDialog("赋给n1的值：");
		int n1 = Integer.parseInt(str01);
		String str02 = JOptionPane.showInputDialog("赋给n2的值：");
		int n2 = Integer.parseInt(str02);
	if(n1>n2 ){
			System.out.println("true!");
		}else{
			System.out.println("false!");
		}
	if(n1<n2){
			System.out.println("true!");
		}else{
			System.out.println("false!");
		}
	if(n1-n2>=0){
			System.out.println("true!");
		}else{
			System.out.println("false!");
	}
	if(n1-n2<=0){
			System.out.println("true!");
		}else{
			System.out.println("false!");
		}
	if(n1%n2==0){
			System.out.println("true!");
		}else{
			System.out.println("false!");	
		}
		}
    }
 -  3、
 
 
    public class ZuoYe03 {
		public static void main(String[] args){
		float c=0,f=0;
		while(f==60){
			c=5f/9*(f-32);
		}
		System.out.println("c="+c);
		while(f==90){
			c=5f/9*(f-32);
		}
		System.out.println("c="+c);
	
		}
	}
 -  4、
 
 
 
    public class ZuoYe04 {
	public static void main(String[] args){
		double c,s;
		double r = 1.5;
		System.out.println("c="+2*3.14*r);
		System.out.println("c="+3.14*r*r);
			
		}
	}





