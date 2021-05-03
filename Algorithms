public class Main {
    public static void main(String[] args) {
        int[] inputArray = {5, 2, 10, 23, 310, 1};

        printArray(bubbleSort(inputArray));
    }
    /*
    Bubble The Biggest element to the end of the array
    Time Complexity of that is Quadratic Time Complexity in the worst case
    It is good in general but with large inputs of array it will be a disaster
     */
    public static int[] bubbleSort(int[] inputArray) {
        int n = inputArray.length;
        for (int i = 0; i < n - 1; i++) {
            for (int j = 0; j < n - i - 1; j++) {
                if (inputArray[j] > inputArray[j + 1]) {
                    int temp = inputArray[j];
                    inputArray[j] = inputArray[j + 1];
                    inputArray[j + 1] = temp;
                }
            }
        }
        return inputArray;
    }

    public static void printArray(int[] inputArray) {
        for (int number : inputArray) {
            System.out.print(number + " ");
        }
    }

}
