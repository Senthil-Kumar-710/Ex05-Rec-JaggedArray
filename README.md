# <p align="center">Jagged Array</p>
## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.
## Algorithm:
 ### Step 1: 
Create a new Class named cpu.
### Step 2:
Create a jagged array of 4arrays.
```
int[][] array = new int[4][];
```
### Step 3:
Create as many sub-nodes as you wish inside one node of jagged array.
### Step 4:
Give the sample CPU usage in the jagged array.  
### Step 5:
Print the sample CPU usage in the jagged array.
### Step 6:
End of the Program.



## Program:
Developed By: **Senthil Kumar S**
</br>

Register No: **212221230091**
</br>

```C#
using System;

namespace exp5
{
    class cpu
    {
        public static void Main(String[] args)
        {

            int[][] cpu = new int[4][];

            cpu[0] = new int[5];
            
            cpu[1] = new int[8];
            
            cpu[2] = new int[3];
            
            cpu[3] = new int[4];

            for (int i = 0; i < 4; i++)
            {
            
                for (int j = 0; j < cpu[i].Length; j++)
                {
                
                    cpu[i][j] = i * j + 70;
                    
                }
            }

            for (int i = 0;i < 4; i++)
            {
            
                for(int j=0; j < cpu[i].Length; j++)
                {
                
                   Console.WriteLine("CPU usage at Node {0} is {1}",i,cpu[i][j]);
                   
                }
                
             Console.WriteLine();
             
            }
        }
    }
}
```

</br>
</br>

## Output:
![ou1](https://user-images.githubusercontent.com/93860256/236781878-3a80b27a-06a7-4877-9a53-41f25b62f280.jpg)

## Result:
Thus, a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.
