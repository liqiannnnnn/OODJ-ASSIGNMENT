package Test;

import java.io.*;

public class CsvReader {
    public static void main(String[] args) throws IOException{
        String Filename = "src/main/resources/course_assessment_information.csv";
        
    try(
        BufferedReader reader = new BufferedReader (new FileReader(Filename))){
        System.out.println("Its here");
    }
    
    }
}
