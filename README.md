# task_3.5

public class Main {
   
   static int[] nums;
   
   static int i = 0;


    public static void main(String[] args) {
        nums = new int[]{4, 2, 6, 2, 65};
        i = nums.length;
        display (i-1);
    }

    static void display (int i) {
        if (i == 0) {
            System.out.println("[" + i + "] - " + nums [i]);
            return;
        } else {
            display(i-1);
            System.out.println("[" + i + "] - " + nums [i]);
        };
    }
}
