###Java02
***
+  1、  


    public class ZuoYe01 {
	    public static void main(String[] args){
			System.out.println("請輸入你的成績:");
			Scanner scanner = new Scanner (System.in);
		int score =scanner.nextInt();
	 	if(score >= 90){
	 		System.out.println("优");
	 	}
	 	else if(score >= 80 && score<90){
	 		System.out.println("良");
	 	}
	 	else if(score >=70 && score<80){
	 		System.out.println("中");
	 	}
	 	else if(score >=60 && score<70){
	 		System.out.println("及格");
	 	}
	 	else if(score < 60){
	 		System.out.println("差");

	 	}
	     }
    }
    
    
+  2.



    public class ZuoYe02 {
	    public static void main(String[] args){
		String input = JOptionPane.showInputDialog("请输入你的成绩");
		int score=Integer.parseInt(input)/10;
	switch (score){
	case 9:
		JOptionPane.showMessageDialog(null,"优");
	break;
	case 8:
		JOptionPane.showMessageDialog(null,"良");
	break;
	case 7:
		JOptionPane.showMessageDialog(null,"中");
	break;
	case 6:
		JOptionPane.showMessageDialog(null,"及格");
	break;
	default:
		JOptionPane.showMessageDialog(null,"差");
	break;		
	}
	}
    }
+ 3.



