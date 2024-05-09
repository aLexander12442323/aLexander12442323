- 👋 Hi, I’m @aLexander12442323
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
  String universidad="Uni camacho",tipo_carrera="";
    int pasaje_sistemas=50000,pasaje_industrial=30000,totalpasaje=0;
    int contsistemas1=0,contsistemas2=0,contsistemas3=0;
    int containdustrial1=0,contindustrial2=0,containdustrial3=0;
    int acomuplatasistema1=0,acumaplastssitema2=0,acomuplatasistemas3=0;
    int acomulaplataindustrial1=0,acomuplataindustrial2=0,acomuplataindustrial3=0;
    
    Scanner Tc = new Scanner(System.in);
    
    public void leerdatos(){
        System.out.println("ingrese a que carrera pertenece \n sistemas \n industrial");
        tipo_carrera=Tc.next();
        
    }
    public void bus1(){
    if (tipo_carrera.equalsIgnoreCase("sistemas")){        
        totalpasaje=pasaje_sistemas;
        contsistemas1=contsistemas1+1;
        acomuplatasistema1=acomuplatasistema1+pasaje_sistemas;
        }
    else
        if (tipo_carrera.equalsIgnoreCase("industrial"))
        {
            totalpasaje=pasaje_industrial;
            containdustrial1=containdustrial1+1;
            acomulaplataindustrial1= acomulaplataindustrial1+pasaje_industrial;
        }
  
    }
    public void bus2(){
        if (tipo_carrera.equalsIgnoreCase("sistemas"))
        {
        totalpasaje=pasaje_sistemas;
        contsistemas2=contsistemas2+1;
         acumaplastssitema2=acumaplastssitema2+pasaje_sistemas; 
        }
        else
            if (tipo_carrera.equalsIgnoreCase("industrial"))
        {
            totalpasaje=pasaje_industrial;
            contindustrial2=contindustrial2+1;
            acomuplataindustrial2=acomuplataindustrial2+pasaje_industrial;
        }
    }
    public void bus3(){
        if (tipo_carrera.equalsIgnoreCase("sistemas"))
        {
            totalpasaje=pasaje_sistemas;
            contsistemas3=contsistemas3+1;
            acomuplatasistemas3= acomuplatasistemas3+pasaje_sistemas;
        }
        else
            if (tipo_carrera.equalsIgnoreCase("industrial"))
        {
            totalpasaje=pasaje_industrial;
            containdustrial3=containdustrial3+1;
            acomuplataindustrial3=acomuplataindustrial3+pasaje_industrial;
        }
    }
public void salida1(){
        System.out.println("  " +universidad );
        System.out.println("cuantas personas se subieron de sistemas: " + contsistemas1);
        System.out.println("cuantas personas se subieron de industrial: " + containdustrial1);
        System.out.println("cuanta plata es de sistemas: " + acomuplatasistema1);
        System.out.println("cuanta plata es de industrial: " + acomulaplataindustrial1);
       
    }
    public void salida2(){
        System.out.println("  " +universidad );
        System.out.println("cuantas personas se subieron de sistemas: " + contsistemas2);
        System.out.println("cuantas personas se subieron de industrial: " + contindustrial2);
        System.out.println("cuanta plata es de sistemas: " + acumaplastssitema2);
        System.out.println("cuanta plata es de industrial: " + acomuplataindustrial2);
    }
    public void salida3(){
        System.out.println("  " +universidad );
        System.out.println("cuantas personas se subieron de sistemas: " + contsistemas3);
        System.out.println("cuantas personas se subieron de industrial: " + containdustrial3);
        System.out.println("cuanta plata es de sistemas: " + acomuplatasistemas3);
        System.out.println("cuanta plata es de industrial: " + acomuplataindustrial3);
    }
      public void datosdecano(){
        System.out.println("datos del decano");
        System.out.println("cuantos viajaron de sistemas en el bus 1:"+contsistemas1);
        System.out.println("cuantos viajaron de sistemas en el bus 2:"+contsistemas2);
        System.out.println("cuantos viajaron de sistemas en el bus 3:"+contsistemas3);
        System.out.println("total de sistemas:"+(contsistemas1+contsistemas2+contsistemas3));
        System.out.println("cuantos viajaron de industrial en el bus 1:"+containdustrial1);
        System.out.println("cuantos viajaron de industrial en el bus 2:"+contindustrial2);
        System.out.println("cuantos viajaron de industrial en el bus 3:"+containdustrial3);
        System.out.println("total de industrial:"+(containdustrial1+contindustrial2+containdustrial3));
        System.out.println("plata de los de sistemas en el bus 1:"+acomuplatasistema1);
        System.out.println("plata de los de sistemas en el bus 2:"+acumaplastssitema2);
        System.out.println("plata de los de sistemas en el bus 3:"+acomuplatasistemas3);
        System.out.println("total plata de lo de sistemas:"+(acomuplatasistema1+acumaplastssitema2+acomuplatasistemas3));
        System.out.println("plata de los de industrial en el bus 1:"+acomulaplataindustrial1);
        System.out.println("plata de los de industrial en el bus 2:"+acomuplataindustrial2);
        System.out.println("plata de los de industrial en el bus 3:"+acomuplataindustrial3);
        System.out.println("total plata de los de industrial:"+(acomulaplataindustrial1+ acomuplataindustrial2+acomuplataindustrial3));
        System.out.println("  el total de plata es:"+(acomuplatasistema1+acumaplastssitema2+ acomuplatasistemas3+ acomulaplataindustrial1+ acomuplataindustrial2+acomuplataindustrial3));
        
        
    }
     

    
}
<!---
aLexander12442323/aLexander12442323 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
