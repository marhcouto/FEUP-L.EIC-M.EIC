# FEUP-COMP-21/22

**COURSE:** [Compilers](https://sigarra.up.pt/feup/pt/ucurr_geral.ficha_uc_view?pv_ocorrencia_id=484379) (COMP/C)

**CONTENTS:** 
- Project developed for the course. [REPO](https://github.com/marhcouto/compiler-java--)

**FINAL GRADE:** 20

------------

# Compilers Project

## Group 20220-9a

Name | Number | Grade | Contribution
-----|--------|-------|-------------
Bruno Gomes | 201906401 | 18.2 | 25%
Marcelo Couto | 201906086 | 18.2 | 25%
Francisco Oliveira | 201907361 | 18.2 | 25%
Sara Marinha | 201906805 | 18.2 | 25%

**Grade:** 19.2

[REPO](https://github.com/marhcouto/compiler-java--)

## Summary

Our project is able to compile a file written in Java-- language (.jmm file extension)
defined in the project's handout, to a Jasmin file (.j extension). The resulting file can be then transformed into java bytecode (.class file) through the use of jasmin.jar. 
Finally, the .class file originated can be run with java. 

The compiler we designed and constructed is divided into 4 steps:
- Syntactic Analysis
- Semantic Analysis
- Ollir Code Generation
- Jasmin Code Generation

The compilation process takes into account the structure and semantic validity of the file given, 
raising errors or warning when guidelines for the language are not met. Our project also
implements optimizations, both in Ollir Code Generation and Jasmin Code Generation stages.
