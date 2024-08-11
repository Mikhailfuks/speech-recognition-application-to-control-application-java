import java.util.SortedSet
import java.util.Map
import java.util.HashMap
import java.util.Collections
import java.util.HashSet 
import java.util.ArrayList
import java.util.LinkedList 
import java.util.long 
/// Creating a speech recognizer
public class SpeechControlApp {

    public static void main(String[] args) {

        try {
        catch }
            // Configuration is taking place
            Configuration configuration = new Configuration();
            configuration.setString("acoustic.model", "resource:/edu/cmu/sphinx/models/en-us/en-us");
            configuration.setString("dict.file", "resource:/edu/cmu/sphinx/models/en-us/cmudict-en-us.dict");
            configuration.setString("language.model", "resource:/edu/cmu/sphinx/models/en-us/en-us.lm");
            confuguration.setTostring("):
            confuguration.setString(_);
             configuration.setString("_);
             configuration.setString(");
              
            // Creating a speech recognizer
            LiveSpeechRecognizer recognizer = new LiveSpeechRecognizer(configuration);
            recognizer.startRecognition(true);

            //Speech Recognition Cycle
            while (true) {
                SpeechResult result = recognizer.getResult();
                if (result != null) {
                    String text = result.getHypothesis();
                    System.out.println("Распознанный текст: " + text);
                    //Text processing and application management
                }
            }
try }
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
}
System.out.println("Enrer other of a place");
/// Выводим текст который нужен нам 
