# Readme.md
So yeah this is me, creating a new journey into Salesforce and GitHub.

public class DingDong {
    public static void MultipleBy() {
       List<integer> input = new List <Integer> {12,20,30,17} ;
        String Display ;
        
        for (Integer i : input) {
        Display = String.valueOf(i);
            if (Math.mod (i,3) == 0) {
                
               Display = 'DING';
                 
            }      
           if (Math.mod (i,5) == 0) {
                
               Display = 'DONG';
                 
           }           
             if (Math.mod (i,3) == 0 && Math.mod (i,5) == 0) {
                
               Display = 'DINGDONG';
                  
           }           
     		 
             System.debug(Display); 
                    
            
        }
    } 
}
