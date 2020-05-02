STORE "angka[1]" with any value
STORE "angka[2]" with any value
STORE "angka[3]" with any value
STORE "count" with 1

STORE "max" with "angka[1]"
WHILE "count" <= 3
    IF "max" < "angka[count]"
        STORE "max" with "angka[count]"
    ADD "count" by 1

DISPLAY "max"