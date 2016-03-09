class Solution {
public:
    bool isIsomorphic(string s, string t) {
        
        if(s.length()!=t.length())
            return false;
        map<char, char> check;
        map<char, char> check1;
        
        
        for (int i = 0; i < s.length(); ++i) {
            if (check.find(s[i]) == check.end()) 
            {
            
                 check[s[i]] = t[i];
                 
            }
            else if(check[s[i]] != t[i])
            
                  
                 return false;
        }
        
        
         for (int i = 0; i < t.length(); ++i) {
            if (check1.find(t[i]) == check1.end()) 
            {
            
                 check1[t[i]] = s[i];
                 
            }
            else if(check1[t[i]] != s[i])
            
                  
                 return false;
        }
        return true;
    }
};
