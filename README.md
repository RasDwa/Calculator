# Calculator

import javax.swing.JFrame;
import java.awt.*;
import java.awt.event.;


public class Solution {
    public static void main(String[] args) {
        Reader r = new Reader("Калькулятор");
        r.setVisible(tru);
        r.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        r.setSize(700,200);
        r.setResizable(false);
        r.setLocationRelativeTo(null);
        
        
    }
}
    public class Reader extends JFrame {
        JButton a1, a2, a3, a4, a5, a6, a7, a8, a9, a0, plus, minus, delenie, umnozenie, obnulit, ravno, znak;
        JTextField t;
        eHender hendler = new eHender();
        
        public Reader(String s){
            super(s);
            setLayout(new FlowLayout());
            a1 = new JButton("1");
            a2 = new JButton("2"); 
            a3 = new JButton("3"); 
            a4 = new JButton("4");
            a5 = new JButton("5"); 
            a6 = new JButton("6"); 
            a7 = new JButton("7"); 
            a8 = new JButton("8"); 
            a9 = new JButton("9"); 
            a0 = new JButton("0"); 
            plus = new JButton("+"); 
            minus = new JButton("-"); 
            delenie = new JButton("/");
            umnozenie = new JButton("*");
            obnulit = new JButton("CE");
            ravno = new JButton("=");
            znak = new JButton("±");
            add(a1);
            add(a2);
            add(a3);
            add(a4);
            add(a5);
            add(a6);
            add(a7);
            add(a8);
            add(a9);
            add(a0);
            add(plus);
            add(minus);
            add(delenie);
            add(umnozenie);
            add(obnulit);
            add(ravno);
            add(znak);
            plus.ActionListener(hendler);
        }
        public class eHandler implements ActionListener (){
            public void actionPerformed(ActionEvent e) {
            if (e.getSourse()==plus) {
            
        }
       
        
    }
