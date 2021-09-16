# Java-1HomeWork2
/**
*Java 1. Home work 2
*@author Darya Kononenko
*@version 14 Sep 2021
*/
class HomeWork2 {
	public static void main(String [] args) {
		positiveNumber(4 , 25);
		negativeNumber1(-19);
		negativeNumber1(0);
		wordsThree();
	}
	
	static void positiveNumber(int a , int b ){
		System.out.println( a + b >= 10 && a + b <= 20? "True" : "False");
	}
	
	static void negativeNumber1(int k){
		System.out.println(k >= 0 ? "Число положительное" : "Число отрицательное");
	}
	
	static void negativeNumber2 (int c){
		System.out.println(c < 0? "True" : "False");
	}
	
	public static void wordsThree (){
		for (int i = 0; i < 5; i++) {
			System.out.println("Landscape");
		}
	}
}

