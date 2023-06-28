#include <iostream>
using namespace std;
int main (){
 
 // variáveis
 int produto =1;
 float preco=0;
 float total = 0;
 float dinheiro=0;
 float troco=0;
 //códigos
 //While(true) para ficar num looping eterno, fazendo o programa funcionar constantemente.
 while(true){
 
 // insersão dos preços e armazenamento do total.
 cout << "Lojas Tabajara" <<endl;
 do{
 cout << "Produto " << produto++ << ": R$ ";
 cin >> preco;
 total = total + preco;
 }while(preco != 0); 
 
 
 /*exposição do total e pedido do valor pago na interface. 
 Além disso, temos a definição de algumas variáveis para que o programa funcione*/
 cout << "Total: R$ " << total << endl;
 cout << "Dinheiro: R$ ";
 cin >> dinheiro;
 troco = dinheiro - total;
 
 
 
 //condicional para o caso de o valor pago não ser suficiente.
 if (dinheiro<total){
 do{
 cout << "valor insuficiente." <<endl;
 cout << "Total: R$ " << total << endl;
 cout << "favor inserir um valor equivalente ou superior ao total: ";
 cin>>dinheiro;
 }while(dinheiro<total); 
 troco = dinheiro - total;
 cout << "total pago." << endl;
 cout << "Troco: R$ " << troco << endl;
 cout << "...\n";
 
 //condicional para o caso de o valor estar completo ou maior que o total.
 }else if (dinheiro >=total){
 cout << "Troco: R$ " << troco << endl;
 cout << "...\n";}
 
 //resetando as variáveis para a manutenção no looping, visando a perfeição do programa. 
 produto=1;
 total = 0; 
 
}//chave para fechar o while(true)
}//chave para fechar o int main()