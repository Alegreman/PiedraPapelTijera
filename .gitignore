import static javax.swing.JOptionPane.*;
public class PiedraPapelTijera
{
   public static int función(int mínimo, int máximo)
      {
          int numero = (int) Math.floor( (int)Math.random() * (máximo - mínimo + 1) + mínimo);
          return numero;
      }//función
      int piedra = 0; 
      int papel = 1;
      int tijera = 2;
      String opciones[]={"Piedra","Papel","Tijera"};
      int opcionMaquina = función (0,2);
      int opcionUsuario =Integer.parseInt (showInputDialog("¿Qué eliges?\nPiedra: 0\nPapel: 1\nTijera: 2", 0));
      
      showMessageDialog(null,"Elegiste: " + opciones[opcionUsuario]+"Java eligió: " + opciones[opcionMaquina]);

      if(opcionUsuario == piedra)
         {
             if(opcionMaquina == piedra)
             {
                 showMessageDialog(null,"Empate!");
             }
    else if(opcionMaquina == papel)
             {
                 showMessageDialog(null,"Perdiste :( ");
             }
    else if(opcionMaquina == tijera)
             {
                 showMessageDialog(null,"Ganaste!");
             }
         
   else if(opcionUsuario == papel)
             {
                if(opcionMaquina == piedra)
                {
                   showMessageDialog(null,"Ganaste!");
                }
          else if(opcionMaquina == papel)
                {
                    showMessageDialog(null,"Empate!");
                }
          else if(opcionMaquina == tijera)
                {
                    showMessageDialog(null,"Perdiste!");
                }
            }
   else if(opcionUsuario == tijera)
   {
       if(opcionMaquina == piedra)
       {
           showMessageDialog(null,"Perdiste!");
       }
       else if(opcionMaquina == papel)
       {
           showMessageDialog(null,"Ganaste!");
       }
       else if(opcionMaquina == tijera)
       {
           showMessageDialog(null,"Empate!");
       }
   }
   else
         {
             showMessageDialog(null,"¿Pos qué carajo?");
         }
             }
      public static void main(String ar[])
         {
            función(0,2);
         }//main     
      }//class
