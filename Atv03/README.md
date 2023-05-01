# Aluna
- Clara Padilha Martinhão

# Atividade
- Usando a classe JOptionPane para entrada de dados, crie uma classe que receba a nota de
duas provas e de um trabalho. Calcule e mostre a média.

# Código

```
import javax.swing.JOptionPane;

public class Atv03 { 
    public static void main(String[] args) { 
        String auxiliar = null;   
        float p1, p2, trabalho, media;    

        auxiliar = JOptionPane.showInputDialog("Nota da primeira prova");  
        p1 = Float.parseFloat(auxiliar);  

        auxiliar = JOptionPane.showInputDialog("Nota da segunda prova");
        p2 = Float.parseFloat(auxiliar);
        
        auxiliar = JOptionPane.showInputDialog("Nota do trabalho");
        trabalho = Float.parseFloat(auxiliar);

        media =  p1 + p2 + trabalho)/3; 
        JOptionPane.showMessageDialog(null, "A média final é: " + media);
    }

```
