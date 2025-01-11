# Total-no.of-odd-nos-between-1-and-100-
Public cass TotalOddNum {
    Public static void main(String args[]) {
        int count = 0;
        for (int i = 1; i <= 100; i++) { 
            if (i % 2 != 0) {
                count++;
            }
        }
        System.out.println("The count of odd numbers between 1 and 100 is: " + count);
    }
}

OUTPUT:

The count of odd numbers between 1 and 100 is: 50
