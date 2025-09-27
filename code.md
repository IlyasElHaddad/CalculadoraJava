
public class interfaz1 extends javax.swing.JFrame {
    

boolean enGrados = false;
boolean nuevaOperacion = false;


    
    private static final java.util.logging.Logger logger = java.util.logging.Logger.getLogger(interfaz1.class.getName());

    public interfaz1() {
        initComponents();
        buttonGroup2.add(jRadioButton1);
        buttonGroup2.add(jRadioButton2);
        jRadioButton1.setSelected(true);


    }

    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {
        java.awt.GridBagConstraints gridBagConstraints;

        jButton22 = new javax.swing.JButton();
        buttonGroup2 = new javax.swing.ButtonGroup();
        jButton1 = new javax.swing.JButton();
        jButton3 = new javax.swing.JButton();
        jButton4 = new javax.swing.JButton();
        jButton5 = new javax.swing.JButton();
        jButton6 = new javax.swing.JButton();
        jButton7 = new javax.swing.JButton();
        jButton8 = new javax.swing.JButton();
        jButton9 = new javax.swing.JButton();
        jButton10 = new javax.swing.JButton();
        jButton11 = new javax.swing.JButton();
        jButton2 = new javax.swing.JButton();
        jButton12 = new javax.swing.JButton();
        jButton13 = new javax.swing.JButton();
        jButton14 = new javax.swing.JButton();
        jButton15 = new javax.swing.JButton();
        jButton16 = new javax.swing.JButton();
        jTextField1 = new javax.swing.JTextField();
        jButton17 = new javax.swing.JButton();
        jButton19 = new javax.swing.JButton();
        jButton20 = new javax.swing.JButton();
        jButton21 = new javax.swing.JButton();
        jButton23 = new javax.swing.JButton();
        jButton24 = new javax.swing.JButton();
        jButton26 = new javax.swing.JButton();
        jRadioButton1 = new javax.swing.JRadioButton();
        jRadioButton2 = new javax.swing.JRadioButton();
        jButton27 = new javax.swing.JButton();

        jButton22.setText("jButton22");

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);
        getContentPane().setLayout(new java.awt.GridBagLayout());

        jButton1.setText("1");
        jButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton1ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 0;
        gridBagConstraints.gridy = 1;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton1, gridBagConstraints);

        jButton3.setText("3");
        jButton3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton3ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 2;
        gridBagConstraints.gridy = 1;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton3, gridBagConstraints);

        jButton4.setText("4");
        jButton4.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton4ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 0;
        gridBagConstraints.gridy = 2;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton4, gridBagConstraints);

        jButton5.setText("5");
        jButton5.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton5ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 1;
        gridBagConstraints.gridy = 2;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton5, gridBagConstraints);

        jButton6.setText("6");
        jButton6.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton6ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 2;
        gridBagConstraints.gridy = 2;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton6, gridBagConstraints);

        jButton7.setText("7");
        jButton7.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton7ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 0;
        gridBagConstraints.gridy = 3;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton7, gridBagConstraints);

        jButton8.setText("8");
        jButton8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton8ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 1;
        gridBagConstraints.gridy = 3;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton8, gridBagConstraints);

        jButton9.setText("9");
        jButton9.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton9ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 2;
        gridBagConstraints.gridy = 3;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton9, gridBagConstraints);

        jButton10.setText("0");
        jButton10.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton10ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 0;
        gridBagConstraints.gridy = 4;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton10, gridBagConstraints);

        jButton11.setText("2");
        jButton11.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton11ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 1;
        gridBagConstraints.gridy = 1;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton11, gridBagConstraints);

        jButton2.setText("=");
        jButton2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton2ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 3;
        gridBagConstraints.gridy = 5;
        gridBagConstraints.gridwidth = 2;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton2, gridBagConstraints);

        jButton12.setText("+");
        jButton12.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton12ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 3;
        gridBagConstraints.gridy = 2;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton12, gridBagConstraints);

        jButton13.setText("-");
        jButton13.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton13ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 3;
        gridBagConstraints.gridy = 3;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton13, gridBagConstraints);

        jButton14.setText("*");
        jButton14.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton14ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 3;
        gridBagConstraints.gridy = 4;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton14, gridBagConstraints);

        jButton15.setText("C");
        jButton15.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton15ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 3;
        gridBagConstraints.gridy = 1;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton15, gridBagConstraints);

        jButton16.setText("/");
        jButton16.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton16ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 2;
        gridBagConstraints.gridy = 4;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton16, gridBagConstraints);
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 0;
        gridBagConstraints.gridy = 0;
        gridBagConstraints.gridwidth = 5;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jTextField1, gridBagConstraints);

        jButton17.setText("(");
        jButton17.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton17ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 0;
        gridBagConstraints.gridy = 5;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton17, gridBagConstraints);

        jButton19.setText(")");
        jButton19.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton19ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 1;
        gridBagConstraints.gridy = 5;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton19, gridBagConstraints);

        jButton20.setText("cos");
        jButton20.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton20ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 4;
        gridBagConstraints.gridy = 3;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton20, gridBagConstraints);

        jButton21.setText("tan");
        jButton21.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton21ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 4;
        gridBagConstraints.gridy = 2;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton21, gridBagConstraints);

        jButton23.setText(".");
        jButton23.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton23ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 1;
        gridBagConstraints.gridy = 4;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton23, gridBagConstraints);

        jButton24.setText("π");
        jButton24.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton24ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 2;
        gridBagConstraints.gridy = 5;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton24, gridBagConstraints);

        jButton26.setText("sin");
        jButton26.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton26ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 4;
        gridBagConstraints.gridy = 4;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jButton26, gridBagConstraints);

        jRadioButton1.setText("Radianes");
        jRadioButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jRadioButton1ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 5;
        gridBagConstraints.gridy = 4;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jRadioButton1, gridBagConstraints);

        jRadioButton2.setText("Grados");
        jRadioButton2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jRadioButton2ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 5;
        gridBagConstraints.gridy = 3;
        gridBagConstraints.fill = java.awt.GridBagConstraints.HORIZONTAL;
        getContentPane().add(jRadioButton2, gridBagConstraints);

        jButton27.setText("DEL");
        jButton27.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton27ActionPerformed(evt);
            }
        });
        gridBagConstraints = new java.awt.GridBagConstraints();
        gridBagConstraints.gridx = 4;
        gridBagConstraints.gridy = 1;
        getContentPane().add(jButton27, gridBagConstraints);

        pack();
    }// </editor-fold>                        

    private void jButton11ActionPerformed(java.awt.event.ActionEvent evt) {                                          
    if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "2");
    }                                         

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
     if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
     jTextField1.setText(jTextField1.getText() + "1");    }                                        

    private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         
  if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "3");
    }                                        

    private void jButton4ActionPerformed(java.awt.event.ActionEvent evt) {                                         
 if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "4");
    }                                        

    private void jButton5ActionPerformed(java.awt.event.ActionEvent evt) {                                         
         if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "5");
    }                                        

    private void jButton6ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "6");
    }                                        

    private void jButton7ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "7");
    }                                        

    private void jButton8ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "8");
    }                                        

    private void jButton9ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "9");
    }                                        

    private void jButton10ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "0");
    }                                         

    private void jButton12ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { 
        jTextField1.setText(""); 
        nuevaOperacion = false; 
    }
    jTextField1.setText(jTextField1.getText() + "+");
    }                                         

    private void jButton13ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { 
        jTextField1.setText(""); 
        nuevaOperacion = false; 
    }
    jTextField1.setText(jTextField1.getText() + "-");
    }                                         

    private void jButton14ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { 
        jTextField1.setText(""); 
        nuevaOperacion = false; 
    }
    jTextField1.setText(jTextField1.getText() + "*");
    }                                         

    private void jButton16ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { 
        jTextField1.setText(""); 
        nuevaOperacion = false; 
    }
    jTextField1.setText(jTextField1.getText() + "/");
    }                                         

    private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        try {
        String expr = jTextField1.getText();

        //Cambio π por su valor numérico
        expr = expr.replaceAll("π", String.valueOf(Math.PI));

        double resultado = eval(expr);

        //Resultado
        jTextField1.setText(String.valueOf(resultado));
        nuevaOperacion = true;

    } catch (ArithmeticException ae) {
        jTextField1.setText("División por cero");
        nuevaOperacion = true;
    } catch (Exception e) {
        jTextField1.setText("Error");
        nuevaOperacion = true;
    }

}

//Operaciones básicas
private double eval(final String str) {
    class Parser {
        int pos = -1, ch;

        void nextChar() { ch = (++pos < str.length()) ? str.charAt(pos) : -1; }

        boolean eat(int charToEat) {
            while (ch == ' ') nextChar();
            if (ch == charToEat) { nextChar(); return true; }
            return false;
        }

        double parse() {
            nextChar();
            double x = parseExpression();
            if (pos < str.length()) throw new RuntimeException("Unexpected: " + (char)ch);
            return x;
        }

        double parseExpression() {
            double x = parseTerm();
            for (;;) {
                if      (eat('+')) x += parseTerm();
                else if (eat('-')) x -= parseTerm();
                else return x;
            }
        }

        double parseTerm() {
            double x = parseFactor();
            for (;;) {
                if      (eat('*')) x *= parseFactor();
                else if (eat('/')) x /= parseFactor();
                else return x;
            }
        }

        double parseFactor() {
            if (eat('+')) return parseFactor();
            if (eat('-')) return -parseFactor();

            double x;
            int startPos = this.pos;
            if (eat('(')) { x = parseExpression(); eat(')'); }
            else if ((ch >= '0' && ch <= '9') || ch == '.') {
                while ((ch >= '0' && ch <= '9') || ch == '.') nextChar();
                x = Double.parseDouble(str.substring(startPos, this.pos));
            } else if (ch >= 'a' && ch <= 'z') {
    while (ch >= 'a' && ch <= 'z') nextChar();
    String func = str.substring(startPos, this.pos);
    x = parseFactor();

    //Esto es para ver en grados o radianes según el radio button que pulsemos
    if (func.equals("sin")) x = Math.sin(enGrados ? Math.toRadians(x) : x);
    else if (func.equals("cos")) x = Math.cos(enGrados ? Math.toRadians(x) : x);
    else if (func.equals("tan")) x = Math.tan(enGrados ? Math.toRadians(x) : x);
    else throw new RuntimeException("Unknown function: " + func);
            } else {
                throw new RuntimeException("Unexpected: " + (char)ch);
            }

            if (eat('^')) x = Math.pow(x, parseFactor());
            return x;
        }
    }
    return new Parser().parse();

    }                                        

    private void jButton15ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        jTextField1.setText("");
    nuevaOperacion = true;
    }                                         

    private void jButton17ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { 
        jTextField1.setText(""); 
        nuevaOperacion = false; 
    }
    jTextField1.setText(jTextField1.getText() + "(");
    }                                         

    private void jButton26ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "sin(");
    }                                         

    private void jButton20ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "cos(");
    }                                         

    private void jButton21ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { jTextField1.setText(""); nuevaOperacion = false; }
    jTextField1.setText(jTextField1.getText() + "tan(");
    }                                         

    private void jButton24ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) {
        jTextField1.setText(""); 
        nuevaOperacion = false; 
    } 
    jTextField1.setText(jTextField1.getText() + "π");
    }                                         

    private void jButton23ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        jTextField1.setText(jTextField1.getText() + ".");
    nuevaOperacion = false;
    }                                         

    private void jButton19ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (nuevaOperacion) { 
        jTextField1.setText(""); 
        nuevaOperacion = false; 
    }
    jTextField1.setText(jTextField1.getText() + ")");
    }                                         

    private void jRadioButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                              
        enGrados = false;
    }                                             

    private void jButton27ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        String text = jTextField1.getText();
    if (!text.isEmpty()) {
        jTextField1.setText(text.substring(0, text.length() - 1));
    }
    }                                         

    private void jRadioButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                              
        enGrados = true;
    }                                             

    public static void main(String args[]) {
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ReflectiveOperationException | javax.swing.UnsupportedLookAndFeelException ex) {
            logger.log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        java.awt.EventQueue.invokeLater(() -> new interfaz1().setVisible(true));
    }

    // Variables declaration - do not modify                     
    private javax.swing.ButtonGroup buttonGroup2;
    private javax.swing.JButton jButton1;
    private javax.swing.JButton jButton10;
    private javax.swing.JButton jButton11;
    private javax.swing.JButton jButton12;
    private javax.swing.JButton jButton13;
    private javax.swing.JButton jButton14;
    private javax.swing.JButton jButton15;
    private javax.swing.JButton jButton16;
    private javax.swing.JButton jButton17;
    private javax.swing.JButton jButton19;
    private javax.swing.JButton jButton2;
    private javax.swing.JButton jButton20;
    private javax.swing.JButton jButton21;
    private javax.swing.JButton jButton22;
    private javax.swing.JButton jButton23;
    private javax.swing.JButton jButton24;
    private javax.swing.JButton jButton26;
    private javax.swing.JButton jButton27;
    private javax.swing.JButton jButton3;
    private javax.swing.JButton jButton4;
    private javax.swing.JButton jButton5;
    private javax.swing.JButton jButton6;
    private javax.swing.JButton jButton7;
    private javax.swing.JButton jButton8;
    private javax.swing.JButton jButton9;
    private javax.swing.JRadioButton jRadioButton1;
    private javax.swing.JRadioButton jRadioButton2;
    private javax.swing.JTextField jTextField1;
    // End of variables declaration                   
}
