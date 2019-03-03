//@author: Zack Barnes

import java.util.ArrayList; 

public class FibSum
{
	private static	ArrayList<Integer> fibSeq = new ArrayList<>();
	
	public static void main(String[] args){
		System.out.println(sumArrayList(getFibSeq(64)));
	}// end method: main	
	
	
	// create fib sequence of elements < 4 million
	private static ArrayList<Integer> getFibSeq(int n){
		fibSeq.add(1);
		fibSeq.add(2);
		int nextTerm = 0;
		for(int i = 1; i <= n; i++){
			nextTerm = fibSeq.get(i-1) + fibSeq.get(i);
			if(nextTerm < 4000000){
			fibSeq.add(nextTerm);
			}
			else break;
		}
		return fibSeq;
	}
	
	// sum over all even elements in the ArrayList
	private static int sumArrayList(ArrayList<Integer> arr){
		int count =0;
		for(int i = 0; i < arr.size(); i++){
			if(arr.get(i) % 2 == 0){
				count+= arr.get(i);
			}
		}
		return count;	
	}
	
	
	
}// End Class Definition: FibSum
