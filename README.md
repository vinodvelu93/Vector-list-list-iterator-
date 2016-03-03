# Vector-list-list-iterator-
package javabasics;
import java.util.*;
//import java.util.Enumeration;
import java.util.Vector;

public class Vectorsample {

	public static void main(String[] args) {
		Vector v= new Vector();
		v.add("PAYILAGAM");
		v.add("Software training");
		//System.out.println(v);
		/*Enumeration e= v.elements();
		while(e.hasMoreElements()){
			System.out.println(e.nextElement());
		}*/
		ListIterator l=v.listIterator();
		while(l.hasNext()){
			System.out.println(l.next());
		}
		while(l.hasPrevious()){
			System.out.println(l.previous());
		}
	

	}

}
OUTPUT:
PAYILAGAM
Software training
Software training
PAYILAGAM
