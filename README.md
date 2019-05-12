# 5170711092_TugasPBO

package inheritance;


public class tuhan {
    void penciptaan (){
        System.out.println("sperma");
        System.out.println("segumpal darah");
        System.out.println("janin");
    }
    void takdir (){
       System.out.println("hidup");
       System.out.println("bernafas"); 
       System.out.println("mati");
    }
    
}


package inheritance;


public class manusia extends tuhan {
    protected manusia (){
        System.out.println("bodoh");
        System.out.println("pesimis");
        System.out.println("gila");
        
    }
    
    @Override
    void takdir (){
        System.out.println("seorang laki-laki");
        System.out.println("anak pertama");
        System.out.println("hidup di jawa");
        
    }
    
    package inheritance;


public class Inheritance {

   
    public static void main(String[] args) {
        tuhan a = new tuhan ();
        manusia aa = new manusia ();
        aa.penciptaan();
        aa.takdir();
        a.penciptaan();
        a.takdir();
    }
    
}

    
    @Override
    void penciptaan (){
        System.out.println("balita");
        System.out.println("remaja");
        System.out.println("dewasa");
        
    }
    
}
