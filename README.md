# OPENBOTCAMP
CURSO EN LINEA EJERCICIOS
public class Ejercicio1 {
    
    public static void main (String[] args){
      
           Persona persona = new Persona();
        
           persona.setName("Alejandro");
           persona.setEdad(19);
           persona.setPhone(7223456);
       
        // consultar informacion 
        System.out.println("Mi nombre es : " +persona.getName () );
        System.out.println("Mi edad es : " +persona.getEdad () );
        System.out.println("Mi numero de celular es : "+persona.getPhone () );
        
}
    
}

class Persona {

    
    public String getName() {
        return name;
    }

   
    public void setName(String name) {
        this.name = name;
    }

   
    public int getEdad() {
        return edad;
    }

    
    public void setEdad(int edad) {
        this.edad = edad;
    }

   
    public double getPhone() {
        return phone;
    }

    
    public void setPhone(double phone) {
        this.phone = phone;
    }
     private String name;
     private int edad;
     private double phone;
   
}

