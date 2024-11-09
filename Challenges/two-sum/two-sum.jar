import java.util.Arrays;

public class TwoSum {
    public static void main(String[] args) {
        TwoSum twoSum = new TwoSum();
        Solution solution = twoSum.new Solution();

        var result = solution.twoSum(new int[]{2, 7, 11, 15}, 9);
        
        System.out.println(Arrays.toString(result));
    }

    class Solution {
        public int[] twoSum(int[] nums, int target) {
            for (int i = 0; i < nums.length - 1; i++) {
                for (int j = i + 1; j < nums.length; j++) {
                    if (nums[i] + nums[j] == target) {
                        return new int[]{i, j};
                    }
                }
            }
            return new int[]{};
        }
    }
}
