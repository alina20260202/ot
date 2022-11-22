# ot
Министерство образования Калининградской области
государственное бюджетное учреждение Калининградской области
профессиональная образовательная организация 
«Колледж информационных технологий и строительства»
(ГБУ КО ПОО «КИТиС»)






Отчет по учебной практике
УП.01 Разработка модулей программного обеспечения для компьютерных систем
по ПМ.01 Разработка модулей программного обеспечения для компьютерных систем

Специальность09.02.07 «Информационные системы и программирование»

Сроки прохождения практики:
с «12» октября 2022 г. по «01» ноября 2022 г. 

Место практикиГБУ КО ПОО «КИТиС»


Выполнил:	Студентка 4 курса, 
группы ИСп19-2к
Прокофьева Алина Сергеевна
_________________
            (подпись)
Проверила:	Большакова-Стрекалова Анна Викторовна
_________________
            (оценка)
_________________
      (подпись, дата)



Калининград, 2022
Содержание

1.Введение                                                                                                      3стр
2.Обзор на языки Java и C++                                                                        4стр
3.Индивидуальное задание6стр
           3.1 задача 1                                                                                          6стр
           3.2 задача 2                                                                                         10стр
           3.3 задача 3                                                                                         21стр
           3.4 задача 4                                                                                         34стр	
           3.5 задача 5                                                                                         39стр
4 Задачи на Си                                                                                              43стр























Введение
Учебная практика проходила в колледже КИТиС. С 12 октября по 1 ноября 2022г.
Основной целью учебной практики было, показать свои знанию в данной сфере.















	









Обзор на языки Java и C++
Java — язык программирования общего назначения. Относится к объектно-ориентированным языкам программирования, к языкам с сильной типизацией.
Создатели реализовали принцип WORA: writeonce, runanywhere или «пиши один раз, запускай везде». Это значит, что написанное на Java приложение можно запустить на любой платформе, если на ней установлена среда исполнения Java (JRE, Java Runtime Environment).
Эта задача решается благодаря компиляции написанного на Java кода в байт-код. Этот формат исполняет JVM или виртуальная машина Java. JVM — часть среды исполнения Java (JRE). Виртуальная машина не зависит от платформы.В Java реализован механизм управления памятью, который называется сборщиком мусора или garbagecollector. Разработчик создаёт объекты, а JRE с помощью сборщика мусора очищает память, когда объекты перестают использоваться. 
Язык C++ — это ключ к современному объектно-ориентированному программированию. Он создан для разработки высокопроизводительного программного обеспечения и чрезвычайно популярен среди программистов. Сегодня быть профессиональным программистом высокого класса означает быть компетентным в C++. Этот язык не просто популярен. Он обеспечивает концептуальный фундамент, на который опираются другие языки программирования и многие современные средства обработки данных. Не случайно ведь потомками C++ стали такие почитаемые языки, как C# и Java. Поскольку язык C++ предназначен для профессионального программирования, для изучения он не самый простой; тем не менее, C++ — самый лучший язык для изучения. Освоив C++, вы сможете писать профессиональные высокопроизводительные программы. Кроме того, вы сможете легко изучить такие языки программирования, как C# и Java, поскольку они используют тот же базовый синтаксис и те же принципы разработки



























Индивидуальное задание
На java
Задача 1
задача на странице 50 номер 2:
Упорядочить и вывести числа в порядке возрастания (убывания) значений
ихдлины.
Код:
package by.baltkrievs;

import java.io.BufferedReader;
import java.io.IOException;
import java.util.Arrays;
import java.util.Objects;

public class Main {

public static void main(String[] args) throws IOException, InterruptedException {

// read line from console
BufferedReader Utils;
Utils = null;
String rString = Utils.readLine();
// try parse string to integer array and return it
int[] intArray = new int[0];
Utils.mark(Integer.parseInt(rString));
// instance of Group A
TaskAtaskA = new TaskA();

taskA.findLongestAndShortestElement(intArray);


taskA.showNumbersLessThanAverage(intArray);

taskA.showFirstDifferentNumber(intArray);

taskA.showPalindrome(intArray);


TaskBtaskB = new TaskB();

        int[] interval = {-1, 4};
        int valueToCheck = 3;
booleanisBelongs = taskB.isBelongsToInterval(valueToCheck, interval);
        if (isBelongs){
System.out.println("Value " + valueToCheck +
" belongs to interval " + Arrays.toString(interval));
}else{
System.out.println("Value " + valueToCheck +
" doesn't belong to interval " + Arrays.toString(interval));
}


taskB.showMatrix(26);

        double a = (double)Integer.valueOf(args[0]);
        double b = (double)Integer.valueOf(args[1]);
        double c = (double)Integer.valueOf(args[2]);
taskB.solveQuadraticEquation(a, b, c);

taskB.printMonth(12);

TaskCtaskC = new TaskC();
Object Matrix;
Matrix = null;
        double[][] matrix = getDoubles(Matrix);
Objects.equals(Matrix, matrix);
System.out.println(" 1");

taskC.getSumOfELementsInPositiveRange();
System.out.println("65");

        double[][] tMatrix = taskC.transposeMatrix();
Matrix.equals(tMatrix);
System.out.println("67");

Matrix.equals(taskC.turnMatrix());
System.out.println("15");


Object o = taskC.turnMatrix(matrix);
taskC.turnMatrix(matrix);
System.out.println("46");

Matrix.equals(taskC.deleteMaxRowsCols());
}

private static double[][] getDoubles(Object matrix) {
double[][] doubles = new double[0][];
        return doubles;
}


}


 



Таблица индикаторов



Наименования переменных	Тип данных 	Назначение
Double a	double	Приближенное число 
int	int	число
		














Блок схема


 











Задача 2

Стрсница 87 Номер 6

House: id, Номер квартиры, Площадь, Этаж, Количество комнат, Улица, Тип здания, Срок эксплуатации.



Код
package haus;
import java.util.Date; 
/**
*
* @author USER
*/
public class Main {
/**
* @param args the command line arguments
*/
public static void main(String[] args) {
haus[] hau = new haus[4];
hau[0] = new haus(1, "kv№123", "100, "7", 2, "Korolya", 3, "8 let");
hau[1] = new haus(2, "kv№124", "120, "4", 3, "Prityzkogo", 4, "17 let");
hau[2] = new haus(3, "kv№125", "150, "4", 2, "Kolobka", 2, "12 let");
hau[3] = new haus(4, "kv№126", "200, "6",1, "Lenina", 3, "5 let");
 
for (int i = 0; i<= 3; i++) {
hau[i].show();
}
//выводнаекран
System.out.println();
for (int i = 0; i<= 3; i++) {
hau[i].uliza();
}
System.out.println();
for (int i = 0; i<= 3; i++) {
hau[i].tip();
}
System.out.println();
for (int i = 0; i<= 3; i++) {
hau[i].ploch(p);
}
System.out.println();
for (int i = 0; i<= 3; i++) {
hau[i].srok();
}
 
 
// TODO code application logic here
}
}
// создаемкласс
class haus {
 
public int id;
public String name;
public int ploch;
public String komnat;
public int uliza;
public String uliza;
public int tip;
public String srok;
 
public haus() {
}
 
public haus(int id String name, int ploch, String komnat, int uliza, String uliza, int tip, String srok) {
this.id = id;
this.name = name;
this.ploch = ploch;
this.komnat = komnat;
this.uliza = uliza;
this.uliza = uliza;
this.tip = tip;
this.srok = srok;
}
 public String getkomnat() {
return komnat;
}
 public int getploch() {
return ploch;
}
 
public String getuliza() {
return uliza;
}
 public String getsrok() {
return srok;
}
 public int getId() {
return id;
}
 public int gettip() {
return tip;
}
public String getName() {
return name;
}
public int getuliza() {
return uliza;
}
 public void setkomnat(String komnat) {
this.komnat = komnat;
}
public void setplochintploch) {
this.ploch = new Date(100);
}
 public void setuliza(String uliza) {
this.uliza = uliza;
}
 public void setsrok(String srok) {
this.srok = srok;
}
public void setId(int id) {
this.id = id;
}
public void settip(int tip) {
this.tip = tip;
}
public void setName(String name) {
this.name = name;
}
public void setuliza(int uliza) {
this.uliza = uliza;
}
public void show() {
System.out.println("id: " + getId());
System.out.println("kvartira " + getName());
System.out.println("ploch: " + getploch();
System.out.println("komnat: " + getkomnat());
System.out.println("uliza: " + getuliza());
System.out.println("uliza: " + getuliza());
System.out.println("tip: " + gettip());
System.out.println("srok: " + getsrok()); 
}
// список квартир, имеющих заданное число комнат; 
publicvoidkomnat() {
if ((this.getpkomnat()).equals("tip")) {// Тут не правильно - нужно подправить
System.out.println("id: " + getId());
System.out.println("kvartira " + getName());
System.out.println("ploch: " + getploch();
System.out.println("komnat: " + getkomnat());
System.out.println("uliza: " + getuliza());
System.out.println("uliza: " + getuliza());
System.out.println("tip: " + gettip());
System.out.println("srok: " + getsrok());
 
}
 
}
// список квартир, имеющих заданное число комнат и расположенных на этаже, который находится в заданном промежутке; 
public void tip() {
if (((this.getkomnat()).equals("Ekonomicheskiy")) && (this.getetag() == 3)) {
System.out.println("id: " + getId());
System.out.println("kvartira " + getName());
System.out.println("ploch: " + getploch();
System.out.println("komnat: " + getkomnat());
System.out.println("uliza: " + getuliza());
System.out.println("uliza: " + getuliza());
System.out.println("tip: " + gettip());
System.out.println("srok: " + getsrok());
}
}
//список квартир, имеющих площадь, превосходящую заданную.
public void ploch(Date p){
if ((this.getploch() > (p.getPloch())){
System.out.println("id: " + getId());
System.out.println("kvartira " + getName());
System.out.println("ploch: " + getploch();
System.out.println("komnat: " + getkomnat());
System.out.println("uliza: " + getuliza());
System.out.println("uliza: " + getuliza());
System.out.println("tip: " + gettip());
System.out.println("srok: " + getsrok());
}
}
 
}
}



 



	Таблица индификаторов


Наименование переменной	Тип данных 	Назначение
String	String	строка


	Блок схема
 





Задача 3
страница 125 номер 18
Создать объект класса Пианино, используя классы Клавиша, Педаль. Методы: настроить, играть на пианино, нажимать клавишу
packagecom.company;
 
import javax.swing.*;
import java.awt.*;
import java.awt.event.KeyAdapter;
import java.awt.event.KeyEvent;
importjava.io.IOException;
 
public class Interf extends JFrame  {
    private JButton create;
    private JButton play;
    private JButtonperedati;
    private JButtonpriem;
    private JButton stop;
 
    public JRadioButton r1,r2,r3;
    public ButtonGroupbg = new ButtonGroup();
 
    Interf()
    {
        super("Пианино");
        setDefaultCloseOperation(EXIT_ON_CLOSE);
        setSize(570, 570);
 
        r1 = new JRadioButton("1");
        r1.setBounds(400,10,50,20);
        r2 = new JRadioButton("1/2");
        r2.setBounds(400, 30, 50, 20);
        r3 = new JRadioButton("1/4");
        r3.setBounds(400, 50, 50, 20);
        //обавляем в группу
        bg.add(r1);
        bg.add(r2);
        bg.add(r3);
        //указываемобработчик
        r1.setSelected(true);
 
        create = new JButton("Создан");
        create.setBounds(10, 450, 100, 30);
        play = new JButton("Воспроизведение");
        play.setBounds(120, 450, 100, 30);
        peredati = new JButton("Передача");
        peredati.setBounds(230, 450, 100, 30);
        priem = new JButton("Прием");
        priem.setBounds(340, 450, 100, 30);
        stop = new JButton("Стоп");
        stop.setBounds(450, 450, 100, 30);
 
        final JPanel piano = new JPanel();
        piano.setLayout(null);
        final JLabel keybut1 = new JLabel(new ImageIcon("key3.gif"));
        keybut1.setBounds(13, 0, 34, 288);
        final JLabel blackey1 = new JLabel(new ImageIcon("key4.gif"));
        blackey1.setBounds(35, 0, 28, 149);
        final JLabel keybut2 = new JLabel(new ImageIcon("key2.gif"));
        keybut2.setBounds(51, 0, 34, 288);
        final JLabel keybut3 = new JLabel(new ImageIcon("key1.gif"));
        keybut3.setBounds(99, 0, 34, 288);
        final JLabel keybut4 = new JLabel(new ImageIcon("key1.gif"));
        keybut4.setBounds(134, 0, 34, 288);
        final JLabel keybut5 = new JLabel(new ImageIcon("key1.gif"));
        keybut5.setBounds(169, 0, 34, 288);
        final JLabel keybut6 = new JLabel(new ImageIcon("key1.gif"));
        keybut6.setBounds(203, 0, 34, 288);
        final JLabel keybut7 = new JLabel(new ImageIcon("key1.gif"));
        keybut7.setBounds(238, 0, 34, 288);
        final JLabel keybut8 = new JLabel(new ImageIcon("key1.gif"));
        keybut8.setBounds(273, 0, 34, 288);
        piano.add(keybut1);
        piano.add(blackey1);
        piano.add(keybut2);
        piano.add(keybut3);
        piano.add(keybut4);
        piano.add(keybut5);
        piano.add(keybut6);
        piano.add(keybut7);
        piano.add(keybut8);
 
      /*  piano.add(create);
        piano.add(play);
        piano.add(peredati);
        piano.add(priem);
        piano.add(stop);
 
        piano.add(r1);
        piano.add(r2);
        piano.add(r3);*/
 
        setContentPane(piano);
        
 
        addKeyListener(new KeyAdapter() {
            booleanFSoundKey = true;
            @Override
            public void keyPressed(KeyEventevt) {
                int x = 0, y = 0;
                switch (evt.getKeyCode()) {
                    case KeyEvent.VK_A:
                        if (FSoundKey == true){
                            x = keybut1.getX() + 2;
                            y = keybut1.getY() + 9;
                            keybut1.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                    case KeyEvent.VK_S:
                        if (FSoundKey == true) {
                            x = keybut2.getX() + 2;
                            y = keybut2.getY() + 9;
                            keybut2.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                    case KeyEvent.VK_D:
                        if (FSoundKey == true) {
                            x = keybut3.getX() + 2;
                            y = keybut3.getY() + 9;
                            keybut3.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                    case KeyEvent.VK_F:
                        if (FSoundKey == true) {
                            x = keybut4.getX() + 2;
                            y = keybut4.getY() + 9;
                            keybut4.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                    case KeyEvent.VK_G:
                        if (FSoundKey == true) {
                            x = keybut5.getX() + 2;
                            y = keybut5.getY() + 9;
                            keybut5.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                    case KeyEvent.VK_H:
                        if (FSoundKey == true) {
                            x = keybut6.getX() + 2;
                            y = keybut6.getY() + 9;
                            keybut6.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                    case KeyEvent.VK_J:
                        if (FSoundKey == true) {
                            x = keybut7.getX() + 2;
                            y = keybut7.getY() + 9;
                            keybut7.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                    case KeyEvent.VK_K:
                        if (FSoundKey == true) {
                            x = keybut8.getX() + 2;
                            y = keybut8.getY() + 9;
                            keybut8.setLocation(x, y);
                            FSoundKey = false;
                        }
                        break;
                }
            }
            @Override
            public void keyReleased(KeyEvent e) {
                int x = 0, y = 0;
                switch (e.getKeyCode()){
                    case KeyEvent.VK_A:
                        x = keybut1.getX() - 2;
                        y = keybut1.getY() - 9;
                        keybut1.setLocation(x,y);
                        FSoundKey = true;
                        break;
                    case KeyEvent.VK_S:
                        x = keybut2.getX() - 2;
                        y = keybut2.getY() - 9;
                        keybut2.setLocation(x, y);
                        FSoundKey = true;
                        break;
                    case KeyEvent.VK_D:
                        x = keybut3.getX() - 2;
                        y = keybut3.getY() - 9;
                        keybut3.setLocation(x, y);
                        FSoundKey = true;
                        break;
                    case KeyEvent.VK_F:
                        x = keybut4.getX() - 2;
                        y = keybut4.getY() - 9;
                        keybut4.setLocation(x, y);
                        FSoundKey = true;
                        break;
                    case KeyEvent.VK_G:
                        x = keybut5.getX() - 2;
                        y = keybut5.getY() - 9;
                        keybut5.setLocation(x, y);
                        FSoundKey = true;
                        break;
                    case KeyEvent.VK_H:
                        x = keybut6.getX() - 2;
                        y = keybut6.getY() - 9;
                        keybut6.setLocation(x, y);
                        FSoundKey = true;
                        break;
                    case KeyEvent.VK_J:
                        x = keybut7.getX() - 2;
                        y = keybut7.getY() - 9;
                        keybut7.setLocation(x, y);
                        FSoundKey = true;
                        break;
                    case KeyEvent.VK_K:
                        x = keybut8.getX() - 2;
                        y = keybut8.getY() - 9;
                        keybut8.setLocation(x, y);
                        FSoundKey = true;
                        break;
                }
            }
 
        });
    }
}


 



	Таблица индикикаторов


Наименование переменной	Тип данных 	Назначение
int	Int	Целое число 










	Блок схема





 


















		Задача 4
Страница 147 номер 18
Создать класс Программа Передач с внутренним классом, с помощью объектов которого можно хранить информацию о названии телеканалов и программ
package bilet7;
import java.util.Scanner;
publicclass Department {
publicstatic Scanner ob=new Scanner(System.in);
public info info;
public String city;
public Department(){
System.out.print("введитеназваниеотделафирмы");
setDepartment(ob.next());
info=new info();
}
public String getDepartment(){
returncity;
}
publicvoidsetDepartment(String city){
this.city=city; 
}
publicclassinfo{
intpr,st,sq;
publicinfo(){
System.out.print("введите количество должностей отдела:");
setPr(ob.nextInt());
System.out.print("количество сотрудников:");
setSt(ob.nextInt());
System.out.print("введите количество филиалов:");
setSq(ob.nextInt());    
}
publicintgetPr(){
returnpr;
}
publicvoidsetPr(int pr){
this.pr=pr;
}
publicintgetSt(){
returnst;
}
publicvoidsetSt(int st){
this.st=st;
}
publicintgetSq(){
returnsq;
}
publicvoidsetSq(int sq){
this.sq=sq;
}
publicvoidprint(){
System.out.print("Нафирме"+" "+getDepartment()+""+getPr()+"сотрудников"+getSt()+"должностей"+getSq()+"филиалов");
}
}
staticpublicvoidmain(String[]args){
Department ct=new Department();
ct.info.print();
}
}

 


	Таблица индикаторов
Наименование переменной	Тип данных	назначение
		









Блок схема
	 













Задача 5
	Страница 195 номер 18
 В тексте определить все согласные буквы, встречающиеся не более чем в двух словах.

import java.util.ArrayList;
import java.util.Scanner;

public class Test {

        public static void main(String args[]){
            String str = new String("Тестоваястрока!");
            Scanner scan = new Scanner(System.in);
System.out.println("Введите строку дял проверки гласных букв: ");
str =  scan.nextLine();
            String tmp1;
            String tmp2;
            int VowelsSound =0;

ArrayList<Character>arr = new ArrayList<Character>();
arr.add('а');
arr.add('е');
arr.add('ё');
arr.add('и');
arr.add('о');
arr.add('у');
arr.add('ы');
arr.add('э');
arr.add('ю');
arr.add('я');
for(int i=0; i<=arr.size()-1; i++){
                tmp2=String.valueOf(arr.get(i));
for(int j =0 ; j<=str.length()-1; j++){
                    tmp1=String.valueOf(str.charAt(j));
if(tmp2.equals(tmp1))
VowelsSound++;
                }
            }
System.out.println("Встроке "+VowelsSound+" гласныхбукв!"); 
}
}
 

	Таблица индификаторов
Наименование  переменной	Тип данных	назначение
int	int	Целое число








	Блок схема
 





	




Индивидуальное задание
На C++
Вариант 1
 

#include <iostream>
 
 // сумма
 int add( int x, int y )
 {
     if( y == 0 )
        return x;
     else
        return add( x ^ y, (x & y) << 1 );
 }
 
 // разность
 int subtr( int x, int y )
 {
    returnadd( x, -y );
 }
 
 // произведение
 int mult( int x, int y )
 {
     if( y == 0 )
        return 0;
     if ( y> 0 )
        return ( x + mult( x, subtr( y, 1 ) ) );
     if ( y< 0 )
    return -mult( x, -y );
 }
 
 // целочисленное деление
 int _div( int x, int y )
 {
   int sign = ( (x < 0) ^ (y < 0) ) ? -1 : 1;
   x = std::abs( x );
   y = std::abs( y );
   int q = 0;
       while( x>= y )
       {
          x = subtr( x, y );
          q = add( q, 1 );
       }
   return sign * q;
 }
 
 int main()
 {
   int a = 100;
   int b = 15;
   std::cout<< a << " + " << b << " = " << add  ( a, b ) << "\n";
   std::cout<< a << " - " << b << " = " <<subtr( a, b ) << "\n";
   std::cout<< a << " * " << b << " = " <<mult ( a, b ) << "\n";
   std::cout<< a << " / " << b << " = " << _div ( a, b ) << "\n";
   return 0;
 }
 
