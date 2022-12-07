# Comp-6.11
import java.util.Random;

public static void main(String[] args) {
	Random generator = new Random();
	int num;
        
	for(int i=1; i<=20; i++) {
            num = generator.nextInt(50)+1;
            for(;num>=0; num--) 
            {
		System.out.print("-");
            }
            System.out.println(" ");
        }

    }

}
