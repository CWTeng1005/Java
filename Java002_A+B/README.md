【实现A+B】
步骤：
1. 导入Scanner类：'import java.util.Scanner;'
   - 用于从控制台读取用户输入的类
3. 创建主类和主方法：'public class AddNumbers'和'public static void main(String[] args)'
   - 所有Java程序的入口点都是'main'方法
5. 创建Scanner对象：'Scanner scanner = new scanner(System.in);'
   - 'System.in'是输入流，'Scanner'使用它来读取输入
7. 提示用户输入第一个和第二个整数：
   - 使用'System.out.print'来提示用户输入，并使用'scanner.nextInt()'读取输入的整数
9. 计算和：'int sum = a + b;'
10. 输出结果：'System.out.println("两个整数的和是：" + sum);'
11. 关闭Scanner: 'scanner.close();'
