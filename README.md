# ANTLR4-
Bộ phân tích cú pháp antlr4
verions antlr-4.7.1

Cài đặt trên ubuntu :
    Tải các package cần thiết :
        
        - wget https://www.antlr.org/download/antlr-4.7.1-complete.jar
        
        - antlr4 grammar : https://github.com/antlr/grammars-v4/tree/master/cpp/CPP14.g4 
    
    Cài đặt trên máy :
    
        - java -jar antlr-4.7.1-complete.jar CPP.g4
        
        - javac -cp ./antlr-4.7.1-complete.jar *.java
        
        - java -cp .:antlr-4.7.1-complete.jar org.antlr.v4.gui.TestRig CPP14 translationunit -gui tenfile.cc 

    Run project :

    java -cp .:antlr-4.7.1-complete.jar org.antlr.v4.gui.TestRig CPP14 translationunit -gui example.cc  

Tham khảo chi tiết tại :
    
    https://github.com/antlr/antlr4/tree/98dc2c0f0249a67b797b151da3adf4ffbc1fd6a1/runtime/Cpp
    
    https://www.antlr.org/
    
    https://www.youtube.com/watch?v=tkDfxdoQw4I
