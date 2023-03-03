# algorithms
project.algo
ALGORITHM read_sentence         // "i love football."
VAR
    text:=STRING;
    i:=INTEGER;
    count : INTEGER := 0 ;
BEGIN
    write("Please enter the text");
    read text;
    FOR i FROM 0 TO text.length-1 STEP 1  DO

    count := count +1;

      write (count); 
    END_FOR
END
