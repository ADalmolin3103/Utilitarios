# Utilitários
Utilitários para programação
Aqui tem snippets,para facilitar o uso das seguintes classes:
+ Scanner
+ DecimalFormat
+ Locale
+ JOptionPane

Com a seguinte sintaxe:
### Snippets para importação (imp)
Todas as classes que necessitam de importação para funcionarem *(DecimalFormat, JOptionPane, Scanners etc)* possuem um snippet para toda a sintaxe de importação seja feita automaticamente:


> imp[Classe]


Com excessão do JOptionPane (impPopUp), que importa um conjunto de classes.
A lista:
+ impScanner
+ impDf
+ impLocale
+ impPopUp (se completa para "*import javax.swing.**" que contém as classes para fazer janelas e, de forma sugestivas, popUp).

### Snippet para construtores (build)
As classes que necessitam construtor, seguem lógica idêntica à de antes:
> build[classe]

A lista:
+ buildScan
+ buildScanLoc (Tem Locale no final ;D)
+ buildDf
+ buildLocale (usar no fim do buildScan)
+ buildPop

#### Snippets de DecimalFormat:

+ dfForm: Coloca a sintaxe para formatar um número em uma variável:
    > formatar.format($0);

#### Snippets de popUp:

+ popPrint: Cria uma saída aos moldes de sout:
    > JOptionPane.showMessageDialog(popUp, $0 );  

+ popScanString: Argumento de pop up para entrada de dados tipo string:
    > JOptionPane.showInputDialog(popUp, $0 );  

+ popScanInt: Argumento de pop up para entrada de dados tipo int:
    > Integer.parseInt(JOptionPane.showInputDialog(popUp, $0 ));  

+ popScanDouble: Cria uma saída de pop up para entrada de dados tipo Double:
    > Double.parseDouble(JOptionPane.showInputDialog(popUp, $0 ));
