public class IterativeAlgorithms {

    // 1. Sum from 0 to n
    public static int sumN(int n) {
        int sum = 0;
        for (int i = 0; i <= n; i++) {
            sum += i;
        }
        return sum;
    }

    // 2. Factorial of a number
    public static int factorial(int n) {
        int result = 1;
        for (int i = 1; i <= n; i++) {
            result *= i;
        }
        return result;
    }

    // 3. n-th power of a natural number
    public static int power(int base, int exponent) {
        int result = 1;
        for (int i = 0; i < exponent; i++) {
            result *= base;
        }
        return result;
    }

    // 4. Sum of elements in a list
    public static int sumList(int[] numbers) {
        int sum = 0;
        for (int num : numbers) {
            sum += num;
        }
        return sum;
    }

    // 5. Arithmetic mean of a list
    public static double mean(int[] numbers) {
        return numbers.length == 0 ? 0 : (double) sumList(numbers) / numbers.length;
    }

    // 6. Standard deviation of a list
    public static double standardDeviation(int[] numbers) {
        if (numbers.length == 0) return 0;
        double meanValue = mean(numbers);
        double sumSquaredDifferences = 0;
        for (int num : numbers) {
            sumSquaredDifferences += Math.pow(num - meanValue, 2);
        }
        return Math.sqrt(sumSquaredDifferences / numbers.length);
    }

    // 7. Sum of the first even numbers up to n
    public static int sumEven(int n) {
        int sum = 0;
        for (int i = 2; i <= n; i += 2) {
            sum += i;
        }
        return sum;
    }

    // 8. Sum of even elements in a list
    public static int sumEvenList(int[] numbers) {
        int sum = 0;
        for (int num : numbers) {
            if (num % 2 == 0) sum += num;
        }
        return sum;
    }

    // 9. Get a list of even numbers from a given list
    public static int[] getEvenList(int[] numbers) {
        int count = 0;
        for (int num : numbers) {
            if (num % 2 == 0) count++;
        }
        int[] evens = new int[count];
        int index = 0;
        for (int num : numbers) {
            if (num % 2 == 0) evens[index++] = num;
        }
        return evens;
    }

    // 10. List of first even numbers up to n
    public static int[] evenList(int n) {
        int size = n / 2;
        int[] evens = new int[size];
        int index = 0;
        for (int i = 2; i <= n; i += 2) {
            evens[index++] = i;
        }
        return evens;
    }

    // 11. Dot product of two lists
    public static int computeDotProduct(int[] list1, int[] list2) {
        if (list1.length != list2.length) throw new IllegalArgumentException("Lists must be the same size.");
        int product = 0;
        for (int i = 0; i < list1.length; i++) {
            product += list1[i] * list2[i];
        }
        return product;
    }
}
