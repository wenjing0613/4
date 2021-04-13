package week1;
import java.util.Scanner;
public class test {
public static void main(String[] args) {
Scanner x = new Scanner(System.in);
System.out.println("请输入成绩");
int a=x.nextInt();
int n=a/10; //百分制转换为等第
private float allAveg = 0.0f;//学生的平均成绩
switch(n){
case 10: //表示如果n=10，也就是一百分，输出A
case 9:
System.out.println("A");
break;
case 8:
System.out.println("B");
break;
case 7:
System.out.println("C");
break;
case 6:
System.out.println("D");
break;
case 5:
case 4:
case 3:
case 2:
case 1:
case 0:
System.out.println("FAIL"); //低于六十分的输出不及格 FAIL
break；
public CalScores dealData() {
allAveg = allScore / 5;
return this;
}
default:System.out.println(" 请输入一个正确的成绩"); //输入的不是百分制，报错
}
}
}
