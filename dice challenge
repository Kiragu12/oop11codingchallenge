import java.util.Random;

public class SimpleDiceGame {
    public static void main(String[] args) {
        Random rand = new Random();

        int d1 = rand.nextInt(6) + 1;
        int d2 = rand.nextInt(6) + 1;
        int d3 = rand.nextInt(6) + 1;
        int total = d1 + d2 + d3;

        System.out.println("You rolled: " + d1 + ", " + d2 + ", " + d3);

        if (d1 == d2 && d2 == d3) {
            System.out.println("Triples! +6 bonus!");
            total += 6;
        } else if (d1 == d2 || d2 == d3 || d1 == d3) {
            System.out.println("Doubles! +2 bonus!");
            total += 2;
        }

        System.out.println("Total score: " + total);

        if (total >= 15) {
            System.out.println("You win!");
        } else {
            System.out.println("You lose!");
        }

        // Simple subscription notice
        int daysLeft = rand.nextInt(12); // 0–11
        if (daysLeft == 0) {
            System.out.println("Your subscription has expired.");
        } else if (daysLeft <= 5) {
            System.out.println("Subscription ends in " + daysLeft + " day(s). Renew soon!");
        } else {
            System.out.println("Subscription is active. " + daysLeft + " days left.");
        }
    }
}
