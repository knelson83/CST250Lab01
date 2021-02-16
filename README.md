# CST250Lab01

Assignment 1: 1-2

**
 *
 * @author kiwin
 * Number 2 from assignment 1
 */

public class array2{
    
    public static void main(String[] args){
        
        
       int [] inputArray = {13,16,3,1};
      int [] n = inputArray;
       
    }
    
    public static int[] removeElement(int[] inputArray, int n){
        
       inputArray[4] = inputArray[inputArray.length - 1];
       
         for (int element : inputArray){
            System.out.println(element);
        
           
       }
       return inputArray;
    }
        
    }

