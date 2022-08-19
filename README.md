# CalculatorsimpleInJava
#Calculator simple in Java

int numero1,numero2,resultado;
        String operacion;

        operacion = JOptionPane.showInputDialog("Suma: S \nRestar: R \nMultiplicar: M \nDividir: D ");
        
        
        if(operacion.equalsIgnoreCase("S") ){
                numero1 = Integer.parseInt(JOptionPane.showInputDialog("Digite un Numero"));
                numero2 = Integer.parseInt(JOptionPane.showInputDialog("Digite otro numero"));
                resultado = numero1 + numero2;
                JOptionPane.showMessageDialog(null,"El resultado de la Suma es: "+resultado);
                
        }else if(operacion.equalsIgnoreCase("R") ){
                numero1 = Integer.parseInt(JOptionPane.showInputDialog("Digite un Numero"));
                numero2 = Integer.parseInt(JOptionPane.showInputDialog("Digite otro numero"));
                resultado = numero1 - numero2;
                JOptionPane.showMessageDialog(null,"El resultado de la Resta es: "+resultado);
                
        }else if(operacion.equalsIgnoreCase("M") ){
                numero1 = Integer.parseInt(JOptionPane.showInputDialog("Digite un Numero"));
                numero2 = Integer.parseInt(JOptionPane.showInputDialog("Digite otro numero"));
                resultado = numero1 * numero2;
                JOptionPane.showMessageDialog(null,"El resultado de la Multiplicación es: "+resultado);
                
        }else if(operacion.equalsIgnoreCase("D") ){
                numero1 = Integer.parseInt(JOptionPane.showInputDialog("Digite un Numero"));
                numero2 = Integer.parseInt(JOptionPane.showInputDialog("Digite otro numero"));
                resultado = numero1 / numero2;
                JOptionPane.showMessageDialog(null,"El resultado de la División es: "+resultado);
                
        }else {
            JOptionPane.showMessageDialog(null,"Vuelva a Intentarlo Recuerde: \nSuma: S "
                    + "\nRestar: R \nMultiplicar: M \nDividir: D ");
        }
