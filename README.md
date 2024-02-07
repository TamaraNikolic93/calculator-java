Start fajl: ciklomatska složenost 3
Calculator fajl:

operations: složenost 1
operations toString složenost 1
run složenost 1
evaluateExpression složenost 12
calculate složenost 12

ukupan LOC za oba fajla je 134+19=153


Calculator fajl:

import java.util.List; bilo bi poželjno da se stavi u imenovani package
Metoda ToString() treba malim početnim slovom da se napiše
public class Calculator treba da bude private class
Metoda Run() ima prazan izraz i nastaće greška ako se tako prosledi i isto treba malim slovom
Metoda Calculate treba malim slovom i trebalo bi dodati proveru da li su liste prazne da ne dođe do greške ako se prazna lista prosledi
u metodi evaluateExpression() može da dođe do greške ako se proslede nedozvoljeni karakteri ili izraz sa uzastopnim operatorima

 String textResult = Float.toString(finalResult);
        return textResult;
može da se drugačije napiše i da se odradi return direktno, npr:
return Float.toString(finalResult);
return posle calculate je suvišan?


Start fajl:
za System.out.println u oba slučaja može da se importuje logger
metoda Expression() treba malim slovom da se napiše
