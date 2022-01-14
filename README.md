***WEEK ONE***

Watch this video about compilation and interpretation- DONE
Search and answer the question: Java language is compiled or interpreted? ** JAva is both a compiled and interpreted language.
Create an algorithm to calculate the equivalent of your local currencty to USD
    
    int localCurrency = 0;
    int roe = 0;
    int convertion =  localCurrency * roe;
    String foreingCurrencyName;
    String localCurencyName;
    
    System.out.println("What is the name of the local currency to be converted");
    localCurrencyName = Read.nextLine();
    System.out.println("What is the amount of local currency to be converted");
    localCurrency = Read.nextLine();
    System.out.println("What is the the rate of exchange");
    roe = Read.nextLine();
    System.out.println("What is the name of the foreign currecy");
    foreignCurrencyName = Read.nextLine();
    System.out.println(localCurrencyName + " converted to " + foreignCurrencyName + " equals " + convertion);
    
Read about Pseudocode here, you can also find some examples here
Anwser to the question: Why is pseudocode helpful? **I believe is useful as it grants flexibility, you don´t have to worry about syntax, is the fast way to solve the problem without thinking of the technical aspects of your code** 

Create a pseudocode to calculate the aproximated age of a user base on the year they born, (you can define a variable with the actual year if you need it, like for example i could define Y <-- 2022)

    thisYear = 2022
    yob = 0
    userYob = 0
    functionYourAge = thisYear - yob;

Read about flowcharts here
Answer to the question: Why are flowcharts important to us as developers? **I think flowcharts will give us as developers the chance to graphicly see the process that we are about to build, is a tangible way to determine the path for coding**
Search about High-level languages and Low-level languages, you can start with this video


**WEDNESDAY**
Learn about binary, decimal and hexadecimal numbers
Translate the year you where born to binary, decimal and hexadecimal
    My YOB 1983
    Binary: 11110111111
    Decimal:1983
    Hex: 7BF
Translate 51966 into hexadecimal and binary: LOL   CAFE
Use a Low-level language, for example MIPS aseembler, to do so, you will need to follow this guide. We recomend to check the guide first but also this presentation could be helpful.
![image](https://user-images.githubusercontent.com/94017302/149431712-2af7e8df-5803-464b-b84a-41da4fe02a5b.png)

Base on the examples and the guide of the low-level language: 5.1 Create a program to add two numbers given by the user 5.2 Create a program that display your name


**THURSDAY**

    Search for real word applications of Javascript:
    
        class Calculator {
      add(a, b) {
        return a + b;
      }

      sub(a, b) {
        return a - b;
      }

      mul(a, b) {
        return a * b;
      }

      div(a, b) {
        if (b == 0) throw new Error('div by 0 not allowed');
        return a / b;
      }
    }

    const a = 12;
    const b = 6;

    const cal = new Calculator();

    const AplusB = cal.add(a,b);
    const AminusB = cal.sub(a, b);
    const AtimesB = cal.mul(a, b);
    const AdivB = cal.div(a, b);

    const results = [AplusB, AminusB, AtimesB, AdivB];

    console.log(results);

(optional but great) Watch this video
(optional but great) Watch this video
Follow the github course, you can find it here

