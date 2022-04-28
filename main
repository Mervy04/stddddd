package com.company;

import java.io.*;
import java.util.Scanner;
import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;
public class Main {

    public static void main(String[] args) throws Exception {

        List<List<String>> lines = new ArrayList<>();
        Scanner inputStream;
        // parsing the CSV file into Scanner class constructor

        System.out.println("\n STD negative values without \n");
        Scanner sc = new Scanner(new File("STDnegative.csv"));
        sc.useDelimiter(","); // sets delimiter pattern
        while (sc.hasNext()) // returns a boolean
        {
            System.out.print(sc.next()); // find and returns the next complete token from this scanner
        }
        sc.close();; // close the scanner

        try{
            System.out.println(" \n STD negative values with array \n ");
            Scanner s = new Scanner(new File("STDnegative.csv"));

            while(s.hasNext()){
                String line= s.next();
                String[] values = line.split(",");
                // this adds the currently parsed line to the 2-dimensional string array
                lines.add(Arrays.asList(values));
            }

            s.close();
        }catch (FileNotFoundException e) {
            e.printStackTrace();
        }

        // the following code lets you iterate through the 2-dimensional array
        int lineNo = 1;
        for(List<String> line: lines) {
            int columnNo = 1;
            for (String value: line) {
                System.out.println("Line " + lineNo + " Column " + columnNo + ": " + value);
                columnNo++;
            }
            lineNo++;
        }

        // STD positive

        // parsing the CSV file into Scanner class constructor

        System.out.println("\n\t STD positve values without array \n ");
        Scanner st = new Scanner(new File("STDpositive.csv"));
        st.useDelimiter(","); // sets delimiter pattern
        while (st.hasNext()) // returns a boolean
        {
            System.out.print(st.next()); // find and returns the next complete token from this scanner
        }
        st.close();; // close the scanner

        try{
            System.out.println(" \n STD positive values with array \n");
            Scanner ss = new Scanner(new File("STDpositive.csv"));

            while(ss.hasNext()){
                String line= ss.next();
                String[] values = line.split(",");
                // this adds the currently parsed line to the 2-dimensional string array
                lines.add(Arrays.asList(values));
            }

            ss.close();
        }catch (FileNotFoundException e) {
            e.printStackTrace();
        }

        // the following code lets you iterate through the 2-dimensional array
        int lineNom = 1;
        for(List<String> line: lines) {
            int columnNom = 1;
            for (String value: line) {
                System.out.println("Line " + lineNom + " Column " + columnNom + ": " + value);
                columnNom++;
            }
            lineNom++;
        }
    }

}



