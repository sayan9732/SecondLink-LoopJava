# SecondLink-LoopJava
public class Main {
    int f = 30;
    int g = 45;
    int k= 555;
     int j = 666;
    public static void main(String[] args){
        Main d1 = new Main();
        System.out.println(d1.k);
        d1.test();
    }
    public void test(){
        Main d2 = new Main();
        System.out.println(d2.j);
        d2.test2();
    }
    public void test2(){
        Main d3 = new Main();
        System.out.println(d3.g);
        d3.test3();
    }
    public void test3(){
        Main d3 = new Main();
        System.out.println(d3.g);

    }
}
