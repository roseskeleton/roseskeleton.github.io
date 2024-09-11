package pat_dzobo_karabo;

import javax.swing.JOptionPane;

/**
 *
 * @author Omphemetse
 */
public class PAT_Dzobo_Karabo {

    public static String isbn, newIsbn;
    public static void main(String[] args) {
        
        String confirm = "";
        
        do 
        {
            inputBooks();
            confirm = JOptionPane.showInputDialog("Are details enterd correct? (Enter yes or no)");
            
            if (confirm.equalsIgnoreCase("yes")) 
            {
                System.out.println();
            }
            else
            {
                System.out.println("Please re-enter details");
                inputBooks();
            }
            
        } while (!confirm.equalsIgnoreCase("Yes"));
        
        removeDash();
        
    }
    
    static void inputBooks()
    {
        String bookTitle = JOptionPane.showInputDialog("Enter title of book");
        String author = JOptionPane.showInputDialog("Enter author of book");
        int year = Integer.parseInt(JOptionPane.showInputDialog("Enter year the book was published"));
        String city = JOptionPane.showInputDialog("Enter city book was published in");
        isbn = JOptionPane.showInputDialog("Enter ISBN of book enterd");
        
        System.out.println("Author: \t" + author + "\nBook Title: \t" + bookTitle);
        System.out.println("City: \t\t" + city);
        System.out.println("Year Published: (" + year + ")" + "\nISBN: \t\t[ " + isbn + " ]");
    }
    
    static void removeDash()
    {
        newIsbn = "";
        for (int i = 0; i < isbn.length(); i++) 
        {
            char dash = isbn.charAt(i);
            if (dash != '-') 
            {
                newIsbn += dash;
            }
        }
        
        System.out.println("New ISBN: \t\t" + newIsbn);
    }
  
               
    }

