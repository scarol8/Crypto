cipher="IXSXVSXOPXLOQCHNXGSOIGJSVDIHEZQYFGAZOIVOBHZEGNX SQXLVFAXBYVLKHLBOISXXIRLBSXBQXVSZVJGOGCGSYRAVOXV JXLXSVAOIXGSQGCOIXAHFSVSQVLBOIXSXFQZVOHZCVEOGSHAQ ZGANXOIXSHBBAXOIVOLGEGLWXEORSXIVBFXXLVFAXOGBHNHLX"

original = input("enter what you want to replace: ")
replace = input("enter what you're replacing it with: ")

new = "";
for char in cipher:
        if(char == original):
                char = replace;
        new+=str(char);

print new;
