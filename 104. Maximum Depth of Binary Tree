/**
 * Definition for a binary tree node.
 * struct TreeNode {
 *     int val;
 *     TreeNode *left;
 *     TreeNode *right;
 *     TreeNode(int x) : val(x), left(NULL), right(NULL) {}
 * };
 */
class Solution {
public:
    int maxDepth(TreeNode* p) {
        if (p==NULL) return 0;
  int left_height = maxDepth(p->left);
  int right_height = maxDepth(p->right);
  if(left_height > right_height)
  {
      return left_height + 1 ;
  }
  else 
    return right_height + 1;
  
        
    }
};
