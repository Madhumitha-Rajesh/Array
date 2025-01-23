# Array

Coding-

package array;
public class Array {
    public static void main(String[] args) {
        //single dimensional array
        int[] singlearray={1,2,3,4,5};
        System.out.println("One-dimensional array");
        for(int i=0;i<singlearray.length;i++){
            System.out.println(singlearray[i]+" ");
        }
        System.out.println();
        //two-dimensional array
        int[][] twodimensionalarray={{1,2,3},{4,5,6},{7,8,9}};
        System.out.println("Two-dimensional array");
        for(int i=0;i<twodimensionalarray.length;i++){
            for(int j=0;j<twodimensionalarray.length;j++){
                System.out.println(twodimensionalarray[i][j]+" ");
            } 
            System.out.println();
        }
        //multi-dimensional array
        int[][][] multidimensionalarray={{{1, 2, 3},{4, 5, 6}},{{7, 8, 9},{10, 11, 12}}};
        System.out.println("Multidimensional array");
        for(int i=0;i<multidimensionalarray.length;i++){
            for(int j=0;j<multidimensionalarray.length;j++){
                for(int k=0;k<multidimensionalarray.length;k++){
                    System.out.println(multidimensionalarray[i][j][k]+" ");
                }
                System.out.println();
            }
            System.out.println();
        }
        
    }
    
    
}

Output-


One-dimensional array
1 
2 
3 
4 
5 

Two-dimensional array
1 
2 
3 

4 
5 
6 

7 
8 
9 

Multidimensional array
1 
2 

4 
5 


7 
8 

10 
11 
