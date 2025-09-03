Project: book-exercise
Authors: To be set.

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: This project forms the basis of a set of exercises
                    that can be found in Chapter 2.
How to start this project: Create one or more Book instances.

USER INSTRUCTIONS: Complete the exercises in Chapter 2.

Lab (Book project, a = question, b = answer)


20a.Do you think the values of the constructor’s parameters will need 
to be stored somewhere persistent? Can you guess what types some of 
the Book class’s fields might be, from the parameters in its constructor? 
Can we know anything for sure about the names of its fields?

20b.I ca guess String for both bookTitle and bookAuthor. Yes, the words Title
and Author are both put before the word "book", meaning that the variables in
this program's fields are related or named "Author" and "Title"

21a.Suppose that the class Pet has a field called name that is of type 
String. Write an assignment statement in the body of the following 
constructor so that the name field will be initialized with the value 
of the constructor’s parameter.
 public Pet(String petsName)
 {
   ...
 }
  
21b. ... = String petsName = name;
  
22a.Challenge exercise : The following object creation will result in the 
constructor of the Date class being called. Can you write the 
constructor’s header? Try to give meaningful names to the parameters.
 new Date("March", 23, 1861)

22b.
public class Date
{
    //the fields.
    private String month;
    private int day;
    private int year;
    
    /**
     *Set the month, day and year fields when this object 
     *is constructed.
     */
    public Date(String presentMonth, int presentDay, int presentYear)
    {
        presentMonth = month;
        presentDay = day;
        presentYear = year;
    }
}
