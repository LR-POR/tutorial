Some explanation on the files in thsi folder

out14b.txt: 
Grammar of choices14.txt applied to the test-sentences of this file.


out14c.txt: 
Manually modified grammar of choices14.txt applied to the same testfile. Inflectional rules in the irules.tdl file genrated by the Grammar Matrix were manually edited to cope with irregular morphology, see my-irules.tdl. To compile a parser with these new rules, load the lkb/my-script file instead of the usual lkb/script file.
Files irregs.tab contain irregular forms, which, , according to Copestake (2002:199-200), should prevent the parsing of incorrect forms such as "sleeped", provided the parameter setting (defparameter *irregular-forms-only-p* t) in the my-globals.lsp file. However, this didn't work. If you know how to fix this problem, please write to me (leonel.de.alencar@ufc.br).


out33.txt:
The grammar that generated these results was not released yet. Try to expand the grammar of choices14.txt to obtain these or better results. I will release this grammar in the near future.


Files whose names begin with "results" classify the output files in four categories: true and false positives and  true and false negatives.
