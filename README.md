# ufo
frontE
void setup()
{
  //Define a porta do led como saida (alterado da porta 10 para a 11)
  pinMode(11, OUTPUT);
}
  
void loop()
{
  //Acende o led
  digitalWrite(11, HIGH);
    
  //Aguarda intervalo de tempo em milissegundos (alterado para 2000)
  delay(2000);
    
  //Apaga o led
  digitalWrite(11, LOW);
    
  //Aguarda intervalo de tempo em milissegundos
  delay(1000);
}
