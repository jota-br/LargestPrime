public class LargestPrime {
    public static int getLargestPrime (int number) {
        
        int largestPrimeNumber = -1;
        for (int i = 2; i <= number; i++) {
            for (int j = 2; j <= i; j++) {
                if (i % j == 0 && i > j) {
                    break;
                }
                if (number % i == 0 && i % j == 0 && i == j) {
                    largestPrimeNumber = i;
                } 
            }
        }
        return largestPrimeNumber;
    }
}
