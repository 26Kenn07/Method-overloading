# Method-overloading
Q5-A2

package AP;

public class Over {

    int ans;
    
    int get(int x,int y){
        ans = x+y;
        return ans;
    }
    
    int get(int x)
    {
    	ans = x*x;
    	return ans;
    }
    
	public static void main(String[] args) {
		Over O = new Over();
		System.out.println("Sum= "+O.get(5,7));
		System.out.println("Square= "+O.get(5));
	}
}

