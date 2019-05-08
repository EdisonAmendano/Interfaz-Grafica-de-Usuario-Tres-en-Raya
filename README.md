
 	
1. Crear tres repositorios en GitHub con el nombre “Interfaz Grafica de Usuario - Calculadora”, “Interfaz Grafica de Usuario – Tres en Raya” y “Interfaz Grafica de Usuario – El Ahorcado”

![2 1](https://user-images.githubusercontent.com/49033575/57345092-3a6a3d80-710f-11e9-9105-a9fa46c9c0e3.png)

2.
![2 2](https://user-images.githubusercontent.com/49033575/57345184-7dc4ac00-710f-11e9-9f12-03da05fbac80.png)

package ec.edu.ups.vista;

import java.awt.Image;
import javax.swing.ImageIcon;

public class VentanaPrincipal extends javax.swing.JFrame {

    int c;
    ImageIcon o;
    ImageIcon x;
    int[][] m;
    int fin;

    public VentanaPrincipal() {
        fin = 0;
        c = 0;
        o = new ImageIcon("o.jpg");
        x = new ImageIcon("x.jpg");
        m = new int[3][3];
        for (int i = 0; i < m.length; i++) {
            for (int j = 0; j < m.length; j++) {
                m[i][j] = 0;
            }
        }

        initComponents();

    }

    
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jLabel1 = new javax.swing.JLabel();
        btn1 = new javax.swing.JButton();
        btn2 = new javax.swing.JButton();
        btn3 = new javax.swing.JButton();
        btn4 = new javax.swing.JButton();
        btn5 = new javax.swing.JButton();
        btn6 = new javax.swing.JButton();
        btn7 = new javax.swing.JButton();
        btn8 = new javax.swing.JButton();
        btn9 = new javax.swing.JButton();
        btnReiniciar = new javax.swing.JButton();
        jLabelResultado = new javax.swing.JLabel();

        jLabel1.setText("jLabel1");

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        btn1.setToolTipText("");
        btn1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn1ActionPerformed(evt);
            }
        });

        btn2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn2ActionPerformed(evt);
            }
        });

        btn3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn3ActionPerformed(evt);
            }
        });

        btn4.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn4ActionPerformed(evt);
            }
        });

        btn5.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn5ActionPerformed(evt);
            }
        });

        btn6.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn6ActionPerformed(evt);
            }
        });

        btn7.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn7ActionPerformed(evt);
            }
        });

        btn8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn8ActionPerformed(evt);
            }
        });

        btn9.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn9ActionPerformed(evt);
            }
        });

        btnReiniciar.setText("Reiniciar");
        btnReiniciar.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnReiniciarActionPerformed(evt);
            }
        });

        jLabelResultado.setFont(new java.awt.Font("Tahoma", 0, 36)); // NOI18N

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addContainerGap()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                            .addComponent(btnReiniciar, javax.swing.GroupLayout.PREFERRED_SIZE, 102, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                .addGroup(layout.createSequentialGroup()
                                    .addComponent(btn1, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                    .addComponent(btn4, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE))
                                .addGroup(layout.createSequentialGroup()
                                    .addComponent(btn2, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                    .addComponent(btn5, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE))
                                .addGroup(layout.createSequentialGroup()
                                    .addComponent(btn3, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                    .addComponent(btn6, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE))))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(btn7, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(btn8, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(btn9, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)))
                    .addGroup(layout.createSequentialGroup()
                        .addGap(65, 65, 65)
                        .addComponent(jLabelResultado, javax.swing.GroupLayout.PREFERRED_SIZE, 179, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(btn4, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btn7, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btn1, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(btn5, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btn2, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btn8, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                    .addComponent(btn9, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btn6, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btn3, javax.swing.GroupLayout.PREFERRED_SIZE, 110, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(btnReiniciar)
                .addGap(18, 18, 18)
                .addComponent(jLabelResultado, javax.swing.GroupLayout.DEFAULT_SIZE, 46, Short.MAX_VALUE)
                .addContainerGap())
        );

        pack();
    }// </editor-fold>                        

    private void btn4ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn4.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[0][1] = 1;

        btn4.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn8ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn8.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[1][2] = 1;

        btn8.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn9ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn9.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[2][2] = 1;

        btn9.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn3ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn3.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[2][0] = 1;

        btn3.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn5ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn5.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[1][1] = 1;

        btn5.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn2ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn2.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[1][0] = 1;

        btn2.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn1ActionPerformed(java.awt.event.ActionEvent evt) {                                     

        btn1.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[0][0] = 1;

        btn1.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn6ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn6.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[2][1] = 1;

        btn6.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btn7ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        btn7.setIcon(new ImageIcon(x.getImage().getScaledInstance(100, 100, 100)));
        m[0][2] = 1;

        btn7.setEnabled(false);
        c++;
        maquina();
    }                                    

    private void btnReiniciarActionPerformed(java.awt.event.ActionEvent evt) {                                             
        //  VentanaPrincipal.main (null);
        c = 0;
        fin = 0;
        for (int i = 0; i < m.length; i++) {
            for (int j = 0; j < m.length; j++) {
                m[i][j] = 0;
            }
        }
        btn1.setIcon(null);
        btn2.setIcon(null);
        btn3.setIcon(null);
        btn4.setIcon(null);
        btn5.setIcon(null);
        btn6.setIcon(null);
        btn7.setIcon(null);
        btn8.setIcon(null);
        btn9.setIcon(null);
        btn1.setEnabled(true);
        btn2.setEnabled(true);
        btn3.setEnabled(true);
        btn4.setEnabled(true);
        btn5.setEnabled(true);
        btn6.setEnabled(true);
        btn7.setEnabled(true);
        btn8.setEnabled(true);
        btn9.setEnabled(true);

    }                                            
    private void maquina() {
        int x = -1;
        int y = -1;
        int co = 0;
        int cn = 0;
        int n = 3;
        do {
            n--;
            for (int i = 0; i < m.length && cn == 0; i++) {
                co = 0;
                if (m[i][co] == 0 && cn == 0) {
                    if (i == 0 && cn == 0) {
                        if (m[i + 1][co] == m[i + 2][co] && m[i + 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (i == 1 && cn == 0) {
                        if (m[i - 1][co] == m[i + 1][co] && m[i - 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (i == 2 && cn == 0) {
                        if (m[i - 1][co] == m[i - 2][co] && m[i - 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (m[i][co + 1] == m[i][co + 2] && m[i][co + 1] == n && cn == 0) {
                        x = i;
                        y = co;
                        cn = 1;
                    }
                }
            }
            for (int i = 0; i < m.length && cn == 0; i++) {
                co = 1;
                if (m[i][co] == 0 && cn == 0) {
                    if (i == 0 && cn == 0) {
                        if (m[i + 1][co] == m[i + 2][co] && m[i + 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (i == 1 && cn == 0) {
                        if (m[i - 1][co] == m[i + 1][co] && m[i - 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (i == 2 && cn == 0) {
                        if (m[i - 1][co] == m[i - 2][co] && m[i - 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (m[i][co - 1] == m[i][co + 1] && m[i][co - 1] == n && cn == 0) {
                        x = i;
                        y = co;
                        cn = 1;
                    }
                }
            }
            for (int i = 0; i < m.length && cn == 0; i++) {
                co = 2;
                if (m[i][co] == 0 && cn == 0) {
                    if (i == 0 && cn == 0) {
                        if (m[i + 1][co] == m[i + 2][co] && m[i + 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (i == 1 && cn == 0) {
                        if (m[i - 1][co] == m[i + 1][co] && m[i - 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (i == 2 && cn == 0) {
                        if (m[i - 1][co] == m[i - 2][co] && m[i - 1][co] == n) {
                            x = i;
                            y = co;
                            cn = 1;
                        }
                    }
                    if (m[i][co - 2] == m[i][co - 1] && m[i][co - 2] == n && cn == 0) {
                        x = i;
                        y = co;
                        cn = 1;
                    }
                }
            }

            if (m[1][1] == 0 && cn == 0) {
                if (m[0][0] == m[2][2] && m[0][0] == n) {
                    x = 1;
                    y = 1;
                    cn = 1;
                }
                if (m[0][2] == m[2][0] && m[0][2] == n && cn == 0) {
                    x = 1;
                    y = 1;
                    cn = 1;
                }
            }
            if (m[0][0] == 0 && cn == 0) {
                if (m[1][1] == m[2][2] && m[1][1] == n) {
                    x = 0;
                    y = 0;
                    cn = 1;
                }
            }
            if (m[0][2] == 0 && cn == 0) {
                if (m[1][1] == m[2][0] && m[1][1] == n) {
                    x = 0;
                    y = 2;
                    cn = 1;
                }
            }
            if (m[2][0] == 0 && cn == 0) {
                if (m[1][1] == m[0][2] && m[1][1] == n) {
                    x = 2;
                    y = 0;
                    cn = 1;
                }
            }
            if (m[2][2] == 0 && cn == 0) {
                if (m[1][1] == m[0][0] && m[1][1] == n) {
                    x = 2;
                    y = 2;
                    cn = 1;
                }
            }

        } while (cn == 0 && n != 1);

        if (cn == 0 && c != 9) {
            do {
                x = (int) (Math.random() * 3);
                y = (int) (Math.random() * 3);
                if (m[x][y] == 0) {
                    cn = 1;
                }
            } while (cn == 0);
        }
        if (x == 0 && y == 0) {
            btn1.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[0][0] = 2;
            c++;
            btn1.setEnabled(false);
        }
        if (x == 1 && y == 0) {
            btn2.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[1][0] = 2;
            c++;
            btn2.setEnabled(false);
        }
        if (x == 2 && y == 0) {
            btn3.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[2][0] = 2;
            c++;
            btn3.setEnabled(false);
        }
        if (x == 0 && y == 1) {
            btn4.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[0][1] = 2;
            c++;
            btn4.setEnabled(false);
        }
        if (x == 1 && y == 1) {
            btn5.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[1][1] = 2;
            c++;
            btn5.setEnabled(false);
        }
        if (x == 2 && y == 1) {
            btn6.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[2][1] = 2;
            c++;
            btn6.setEnabled(false);
        }
        if (x == 0 && y == 2) {
            btn7.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[0][2] = 2;
            c++;
            btn7.setEnabled(false);
        }
        if (x == 1 && y == 2) {
            btn8.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[1][2] = 2;
            c++;
            btn8.setEnabled(false);
        }
        if (x == 2 && y == 2) {
            btn9.setIcon(new ImageIcon(o.getImage().getScaledInstance(100, 100, 100)));
            m[2][2] = 2;
            c++;
            btn9.setEnabled(false);
        }

        if (m[0][0] == m[0][1] && m[0][0] == m[0][2] && m[0][0] != 0) {
            fin = m[0][0];
        } else if (m[1][0] == m[1][1] && m[1][0] == m[1][2] && m[1][0] != 0) {
            fin = m[1][0];
        } else if (m[2][0] == m[2][1] && m[2][0] == m[2][2] && m[2][0] != 0) {
            fin = m[2][0];
        } else if (m[0][0] == m[1][0] && m[0][0] == m[2][0] && m[0][0] != 0) {
            fin = m[0][0];
        } else if (m[0][1] == m[1][1] && m[0][1] == m[2][1] && m[0][1] != 0) {
            fin = m[0][1];
        } else if (m[0][2] == m[1][2] && m[0][2] == m[2][2] && m[0][2] != 0) {
            fin = m[0][2];
        } else if (m[0][0] == m[1][1] && m[0][0] == m[2][2] && m[0][0] != 0) {
            fin = m[0][0];
        } else if (m[0][2] == m[1][1] && m[0][2] == m[2][0] && m[0][2] != 0) {
            fin = m[0][2];
        }

        if (fin != 0 || c == 9) {
            if (fin != 0) {
                if (fin == 1) {
                    jLabelResultado.setText("Ganador X");
                } else {
                    jLabelResultado.setText("Ganador O");
                }
                btn1.setEnabled(false);
                btn2.setEnabled(false);
                btn3.setEnabled(false);
                btn4.setEnabled(false);
                btn5.setEnabled(false);
                btn6.setEnabled(false);
                btn7.setEnabled(false);
                btn8.setEnabled(false);
                btn9.setEnabled(false);
            } else {
                jLabelResultado.setText("Empate");
            }
        }

    }

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new VentanaPrincipal().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton btn1;
    private javax.swing.JButton btn2;
    private javax.swing.JButton btn3;
    private javax.swing.JButton btn4;
    private javax.swing.JButton btn5;
    private javax.swing.JButton btn6;
    private javax.swing.JButton btn7;
    private javax.swing.JButton btn8;
    private javax.swing.JButton btn9;
    private javax.swing.JButton btnReiniciar;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabelResultado;
    // End of variables declaration                   
}

![2 3](https://user-images.githubusercontent.com/49033575/57345263-cd0adc80-710f-11e9-86d1-77859726c4d3.png) 

Cuenca GitHub: EdisonAmendano
URLs: 

•	Tres en Raya: https://github.com/EdisonAmendano/Interfaz-Grafica-de-Usuario-Tres-en-Raya.git


RESULTADO(S) OBTENIDO(S):

	Se aprendió a crear una interfaz gráfica de usuario en java. 
	La utilización correcta de las propiedades de la interfaz. 
CONCLUSIONES

	La interfaz de usuario en java es de gran utilidad ya que nos permite la interacción con el usuario de una manera más dinámica y menos confusa.


Nombre de estudiante: Edison Amendaño

Firma de estudiante: 
![Firma](https://user-images.githubusercontent.com/49033575/57345651-42c37800-7111-11e9-8c6b-5604f511feba.png)
