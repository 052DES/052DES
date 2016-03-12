# 052DES//20142984 程憧憬
//随机数四则运算
import javax.swing.JOptionPane;
public class Main {

	public static void main(String[] args) {
		// TODO 自动生成的方法存根
      for(int i=0;i<=29;i++)    
		  {
    	  int FirstNum=(int)(Math.random()*100);
		
		int SecondNum=(int)(Math.random()*100);
		int x=(int)(Math.random()*100);
		
		
		if(x%4==0)
			System.out.println(FirstNum+" + "+SecondNum+"=");
		if(x%4==1)
			System.out.println(FirstNum+" - "+SecondNum+"=");
		if(x%4==2)
			System.out.println(FirstNum+" * "+SecondNum+"=");
		if(x%4==3)
			System.out.println(FirstNum+" / "+SecondNum+"=");
	     }
	 
      for(int j=0;j<=29;j++)    
  		  {
      	  int Num1=(int)(Math.random()*100);
  	      int Num2=(int)(Math.random()*100);
  		  int Num3=(int)(Math.random()*100);
  		  int Num4=(int)(Math.random()*100);
  		  if(Num1==0) { Num1=(int)(Math.random()*100);}
  		  if(Num2==0) { Num2=(int)(Math.random()*100);}
  		  if(Num4==0) { Num4=(int)(Math.random()*100);}
  		  int x=(int)(Math.random()*100);
  		
  		
  		if(x%4==0)
  			System.out.println(Num1+"/"+Num2+" + "+Num3+"/"+Num4+"=");
  		if(x%4==1)
  			System.out.println(Num1+"/"+Num2+" - "+Num3+"/"+Num4+"=");
  		if(x%4==2)
  			System.out.println(Num1+"/"+Num2+" * "+Num3+"/"+Num4+"=");
  		if(x%4==3)
  			System.out.println(Num1+"/"+Num2+" / "+Num3+"/"+Num4+"=");
  	     }
  	
											}
  
				}
