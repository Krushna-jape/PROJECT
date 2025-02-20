public class AddTwoNumbers {
    public static void main(String[] args) {
        int num1 = 5;
        int num2 = 10;
        int sum = num1 + num2;
        System.out.println("Sum of " + num1 + " and " + num2 + " is: " + sum);
    }
}
rows = 5
# Upper half of the diamond
for i in range(1, rows + 1):
    print(' ' * (rows - i) + '*' * (2 * i - 1))
# Lower half of the diamond
for i in range(rows - 1, 0, -1):
    print(' ' * (rows - i) + '*' * (2 * i - 1))
