import java.util.*;

class HelloWorld {
    
    public static int[] getConcatenation(int[] nums) {
        
        int length = nums.length;
        int[] answer = new int[length * 2];

        for (int i = 0; i < length; i++) {
            answer[i] = nums[i];
            answer[i + length] = nums[i];
        }

        return answer;
    }
    
    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the Array Size: ");
        int size = sc.nextInt();
        int[] nums = new int[size];
        
        System.out.print("Enter the Elements of Array: ");
        
        for (int i = 0; i < size; i++) {
            nums[i] = sc.nextInt();
        }
        
        int[] answer = getConcatenation(nums);
        
        System.out.print("Concatenation of Array: ");
        
        for (int i = 0; i < size * 2; i++) {
            System.out.print(answer[i] + " ");
        }
    }
}
