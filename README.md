# String-methods-in-Java
public class Main{
    public static void main(String[] args){
       String s="  Hello, World!.   ";
       
       int len=s.length();
       System.out.println("LENGTH:"+len);
       
       String sub=s.substring(3,8);
       System.out.println("SUBSTRING:"+sub);
       
       String caps=s.toUpperCase();
       System.out.println("IN UPPERCASE:"+caps);
       
       String low=s.toLowerCase();
       System.out.println("IN LOWERCASE:"+low);
       
       char l1=s.charAt(12);
       System.out.println("ELEMENT:"+l1);
       
       String snew=s.trim();
       System.out.println("NEW SENTENCE:"+snew);
       
       String s1=s.replace("World","Universe");
       System.out.println("REPLACED SENTENCE:"+s1);
       
       boolean has=s.contains("World");
       System.out.println("CONTAINS:"+has);
       
      
    
    }
}
