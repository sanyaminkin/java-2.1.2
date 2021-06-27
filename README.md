public class Main {
    
    public static void main(String[] args) {


        int balance = 200;
        int refill = 1200;
        int bonus = refill / 100;

        int total;
        if (refill > 1000) {
            total = balance + refill + bonus;
        } else {
            total = balance + refill;
        }

        System.out.println("Баланс счета: " + total);


    }
}
