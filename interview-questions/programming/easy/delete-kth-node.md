Implement a function to delete the k-th element from a singly-linked list.
You can assume that k is always a valid value, in the range 1 <= k <= n

    /*
     * Definition for singly-linked list.
     * public class ListNode {
     *     int val;
     *     ListNode next;
     *     ListNode(int x) { val = x; }
     * }
     */
    public ListNode delete(ListNode head, int k) {
        // ...
    }

Example inputs and expected outputs:

- "1->null", 1 -> "null"
- "1->2->null", 2 -> "1->null"
- "1->2->null", 1 -> "2->null"
- "1->2->3->null", 2 -> "1->3->null"