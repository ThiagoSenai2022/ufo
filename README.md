# ufo
frontE
void setup()
{
  //Define a porta do led como saida
  pinMode(11, OUTPUT);
}
  
void loop()
{
  //Acende o led
  digitalWrite(11, HIGH);
    
  //Aguarda intervalo de tempo em milissegundos 
  delay(2000);
    
  //Apaga o led
  digitalWrite(11, LOW);
    
  //Aguarda intervalo de tempo em milissegundos
  delay(1000);
}
// linha 6 alterado da portado led 10 para a 11) thiago 08set
// linha 15 alterado intervalo para 2000 ms) thiago 08set
