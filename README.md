# Netfilmes
 Adaptação do Netflix

   Console.WriteLine("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n");
  int quantidade,produto;
  int i=0;
  int holandesa= 6;
  string hol= "Torta Holandesa";
  int limao= 5;
  string lim= "Torta de Limão";
  int chocolate= 8;
  string choc= "Torta de Chocolate";
  int total=0;
  int valor=0;

  Console.WriteLine("\n                    DOCERIA KAMI-KASY");
  Console.WriteLine("-----------------------------------------------------------");


  do{
    i=i+1;
    Console.Write("0"+i+"   Cod:");
    produto=Convert.ToInt32(Console.ReadLine());

    if (produto==0){
    i=produto;
    Console.WriteLine("\n         **********  Compra Finalizada **********  ");
    }
   if (produto==1){
    
        Console.Write("   "+hol+"\n   VLR UND  R$:"+holandesa+",00");
        Console.Write("  QTD:");
        quantidade=Convert.ToInt32(Console.ReadLine());
        valor= quantidade*holandesa;
        Console.WriteLine("                                          R$:"+valor+",00");
   }
   if (produto==2){
    
        Console.Write("   "+lim+"\n   VLR UND  R$:"+limao+",00");
        Console.Write("  QTD:");
        quantidade=Convert.ToInt32(Console.ReadLine());
        valor= quantidade*limao;
        Console.WriteLine("                                          R$:"+valor+",00");
        
   }
   if (produto==3){
    
        Console.Write("   "+choc+"\n   VLR UND  R$:"+chocolate+",00");
        Console.Write("  QTD:");
        quantidade=Convert.ToInt32(Console.ReadLine());
        valor= quantidade*chocolate;
        Console.WriteLine("                                          R$:"+valor+",00");
   }

  total=total+valor;

  }while(i>0);


Console.WriteLine("-----------------------------------------------------------");
 
 Console.Write("                                Total R$"+total+",00");
 
 
 
  
