public class Fraccion{

//Atributos
int numerador = 0;
int denominador = 1;

//Métodos

//Constructor
public Fraccion(int n, int b){
		this.numerador = n;
		this.denominador = d;
	}

Fraccion dividir(int num, int denom){
		int nuevoNumerador = this.numerador * num;
		int nuevoDenominador = this.denominador * denom;

   fraccionResultado = new Fraccion(nuevoNumerador, nuevoDenominador)

   return fraccionResultado;
} //dividir

 public Fraccion multiplicar(int num, int denom){
       int nuevoNumerador = this.numerador * num;
       int nuevoDenominador = this.denominador * denom;

   Fraccion fraccionResultado = new Fraccion(nuevoNumerador, nuevoDenominador);

   return fraccionResultado;
  } //multiplicar


public Fraccion sumar(int num, int denom){

   int nuevoDenominador=denom;
   int nuevoNumerador=this.num+this.denom;
   Fraccion fraccionResultado = new Fraccion(nuevoNumerador, nuevoDenominador);

  return fraccionResultado;

   } //sumar

public Fraccion restar(int num, int denom){

   int nuevoDenominador=denom;
   int nuevoNumerador=this.num-this.denom;
   Fraccion fraccionResultado = new Fraccion(nuevoNumerador, nuevoDenominador);

  return fraccionResultado;
}//restar

public Fraccion potencia(int pot){
   pot= Math.pow(num,denom);
        return pot;
    }

  public Fraccion raizCuadrada(){
      return (Math.sqrt(this.numerador, this.denominador));  
    }

  public Fraccion porcentaje(int porciento){
      porciento = (this.numerador + this.denominador)*100/this. denominador;
      return porciento;  
    }

public double convertirADecimal(){
        return (double) (this.numerador / this.denominador);
    }

<!---
Alexanderhuitzil24/Alexanderhuitzil24 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
