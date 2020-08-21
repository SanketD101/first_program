# first_program
package CSES;

public class maxNoArr {
	static void maxNo(int arr[],int size) {
		int max = arr[0];
		for(int i=1;i<size;i++) {
			if(arr[i]>max)
				max=arr[i];
		}	
		System.out.println(max);
	}

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int arr [] = {1,3,8,5,2,6,8,1};
		maxNo(arr,arr.length);
	}

}

