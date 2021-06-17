public class ATM {
    public int countBanknotes(int sum){
       int [] numbersBanknotes = new int[]{500, 200, 100, 50, 20, 10, 5, 2, 1};
        int count = 0;
        int i = 0;
        while ( i < numbersBanknotes.length){
            int justaNumber = numbersBanknotes[i];
            i++;

            while (sum - justaNumber >=0){
                    sum -= justaNumber;
                    count++;
            }
        }
                return count;
    }

   public static void main(String[] args) {
       ATM bank = new ATM();

        //Should be 6 - 500 + 50 + 20 + 5 + 2 + 1
        System.out.println(bank.countBanknotes(578));
    }
}
