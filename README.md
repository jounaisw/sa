
 7 
 8 import java.util.Arrays;
 9 import java.util.Scanner;
10 
11 public class HS_Array3 {
12 
13     public static void main(String[] args) {
14         
15         int[][] array=new int[][]{{2,1},{2,1,3},{2,1}};
16         for(int i=0;i<array.length;i++){
17             String str=(i+1)+"班";
18             Arrays.sort(array[i]);
19             System.out.println(str+"排序以后");
20             for(int j=0;j<array[i].length;j++){
21                 System.out.println(array[i][j]);
22             }
23         }
24     }
25 }# sa
af
