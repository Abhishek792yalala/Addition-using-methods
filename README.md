# Addition-using-methods

//Adding numbers using methods: 
class Code{
    int m1(int a, int b){
        int r1=a+b;
        System.out.println("The sum of a and b is : "+ r1);
        return r1;



    }

    int m1(int x, int y, int z){
        int r2=x+y+z;
        System.out.println("The sum of x, y and z is : "+ r2);
        return r2;

    }
    public static void main(String ... args){
        Code c=new Code();
        c.m1(1,2);
        c.m1(1,2,3);


    }
}
/*
The sum of a and b is : 3
The sum of x, y and z is : 6
 */
