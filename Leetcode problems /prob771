import java.util.*; 

class Solution {
    public int numJewelsInStones(String J, String S) {
        
        int sum = 0;

        char[] ch = new char[J.length()]; 
        char[] ch2 = new char[S.length()]; 
  
        for (int i = 0; i < J.length(); i++) { 
            ch[i] = J.charAt(i); 
        } 
        for (int i = 0; i < S.length(); i++) { 
            ch[i] = S.charAt(i); 
        }
  
        for (int i = 0; i < ch.length(); i++) { 
            for (int j = 0; j < ch2.length(); j++) {
                if (ch2[j].equals(ch[i])) {
                    sum++;
                }
            }
        } 
    }
}