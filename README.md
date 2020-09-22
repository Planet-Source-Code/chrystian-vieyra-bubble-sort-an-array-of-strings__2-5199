<div align="center">

## Bubble sort an array of Strings


</div>

### Description

Sorts an array of structures by using the bubble sort
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Chrystian Vieyra](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/chrystian-vieyra.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\), Java \(JDK 1\.3\), Java \(JDK 1\.4\), Java \(JDK 1\.5\)
**Category**       |[Data Structures](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/data-structures__2-67.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/chrystian-vieyra-bubble-sort-an-array-of-strings__2-5199/archive/master.zip)





### Source Code

```
import java.util.Scanner;
public class bubblesort
{
	public static void main(String[] args)
	{
		String[] Array;
		Array=new String[10];
		String temp;
		Scanner input=new Scanner(System.in);
		for(int i=0;i<10;i++){
			System.out.println("Give me the name ");
			Array[i]=input.next();
			}
	for(int x=1;x<10;x++)
		{
		for(int y=0;y<10-x;y++)
			{
			if(Array[y].compareTo(Array[y+1])>0)
				{
				temp=Array[y];
				Array[y]=Array[y+1];
				Array[y+1]=temp;
				}
				}
				}
	for(int i=0;i<10;i++){
		System.out.println("The sorted values are "+Array[i]);
		}
		}
		}
```

