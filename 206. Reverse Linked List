/**
 * Definition for singly-linked list.
 * struct ListNode {
 *     int val;
 *     ListNode *next;
 *     ListNode(int x) : val(x), next(NULL) {}
 * };
 */
class Solution {
public:
    ListNode* reverseList(ListNode* head) {
        
        ListNode *pre;
        ListNode *cur;
        ListNode *next;
        pre = NULL;
        cur = head;    
        while(cur !=NULL)
        {
            next=cur->next;
            cur->next=pre;
            pre=cur;
            cur=next;
            
            
            
            
        }
        return pre;
        
    }
};
