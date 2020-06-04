# VaSto Encoding Guidelines

Transedition and Diplomatic Edition encoding (useful for understand the pre-existing encoding)

## Enabling Images 

``` ```

## Categorise people, places and events (they are declared in TEI header)
```  <persName ref="#Torello">Lelio Torello</persName> ```

```<placeName ref="#Firenze">Firenze</placeName> ```

```<date when="1530">millecinquecentotrenta</date> ```

## Additions and deletions on the text
```<add hand=“#A2”>addition</add> ```
```<del hand= “#A3”>deleted text</del> ```

## Critical Edition (useful part for your work)
Normalisation from diplomatic to critical text
```<choice><orig>fù</orig><corr>fu</corr></choice> ```
be careful with spaces! EVT is sensitive to the spaces: please respect meticulously
 the space between the words (we suggest you to write all tags on a single line) 

## Variations between RC4 and RC4c
```<app><lem wit="#RC4" hand="#A1">testo autore</lem> <rdg cause="del" wit="#RC4c">Censura </rdg></app> ```
Please remember to declare the witness, the cause (add or del) and the hand
