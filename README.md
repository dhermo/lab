# Informe de Laboratorio 01
## Bases de Datos Biológicas

### Enfermedades Genéticas y Genes

 Síndrome de Progeria Hutchinson-Gilford
Es una enfermedad genética provocada por la mutación heterocigótica del gen de Laminina A (LMNA) ubicado en el cromosoma 1q22. Las personas que padecen de esta enfermedad son jovenes con la apariencia de ancianos; baja estatura, caida prematura del cabello, osteólisis, scleroderma, entre otros. Pero son los problemas cardíacos los que generan una prematura muerte de estos individuos.
> El gen es denominado oficialmente *lamin A/C*

#### Responde
¿Tiene nombres alternativos el gen?
  
  - FPL; IDC; LFP; CDDC; EMD2; FPLD; HGPS; LDP1; LMN1; LMNC; MADA; PRO1; CDCD1; CMD1A; FPLD2; LMNL1; CMT2B1; LGMD1B
	
¿En qué cromosoma está? ¿Cuántos exones tiene? ¿Cuántas isoformas de transcritos?
  
  - Se encuentra en el cromosoma 1. Tiene 17 exones. Y tiene 9 isoformas. 
    
¿Qué tipo de proteina es codificada por este gen? ¿Cuál es su número EC?
  
  - Codifica para proteínas estructurales. 
    
¿Qué genes están inmediatamente río arriba/abajo?
  
  - Río arriba se encuentran los genes RAB25 y MEX3A, y río abajo SEMA4A y SLC25A44
    
#### Este gen posee 635 variaciones génicas
Algunas de ellas son:

1 LMNA, 3B, producida por una deleción 94 AAG
	
2 NM_170707.3(LMNA):c.178C>G que resulta en el cambio de una arginina por una glicina en la proteína resultante

3 NM_170707.3(LMNA):c.11C>G donde se combia una prolina en la posicion 4 por una arginina.

#### Responde

¿Cuál es la longitud de tu gen?

  - mi gen mide 57,544 pb.
  
¿Las sustituciones corresponden a cambios sinónimos o no sinónimos?  

  - Existen cambios tanto sinónimos como no sinónimos.
	  
¿Existen ortólogos de tu gen en otras especies? ¿Cuántos?  

  - 193 organismos tienen ortólogos con el gen humano de LMNA.
  
¿Y paralógos? ¿Hay pseudogenes? ¿Cuántos?

  - No se han reportado paralógos, tampoco pseudogenes.
  
  
### Rutas y procesos metabólicos
  
#### Responde
  
Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por Kegg? ¿Cuáles?

  - No hay diferencias entre los nombres reportados por NCBI versus Kegg.
  
¿En qué rutas metabólicas participa la proteina codificada por tu gen?

  - La proteína codificada por el gen LMNA participa en las vías: *Apoptosis*, *Hypertrophic cardiomyopathy (HCM)*, *Arrhythmogenic right ventricular cardiomyopathy (ARVC)*, *Dilated cardiomyopathy (DCM)*
  
¿Cuál es el número de identificación de tu gen (entry number)?

  - 4000

En general, cada unidad dentro de una base de datos tiene un número o código de identificación único. De esta forma, uno puede obtener exactamente lo que quiere dentro de un oceano de otras cosas ¿En qué otras bases de datos está tu gen presente y cuáles son sus números de acceso? 

  - NCBI-GeneID: 4000
  - NCBI-ProteinID: NP_733821
  - OMIM: 150330
  - HGNC: 6636
  - Ensembl: ENSG00000160789
  - Vega: OTTHUMG00000013961
  - Pharos: P02545(Tbio)
  - UniProt: P02545

![Imagén 1](http://www.kegg.jp/tmp/mark_pathway150275328130820/hsa05410.png)
Imagén 1: Hypertrophic cardiomyopathy (HCM) pathaway.

#### Responde

¿En qué otras rutas metabólicas está involucrado tu gen?

  - También forma parte de las rutas de apoptosis, *Hypertrophic cardiomyopathy (HCM), Arrhythmogenic right ventricular cardiomyopathy (ARVC),Dilated cardiomyopathy (DCM)*
  
¿Qué significan los cuadros verdes en el diagrama?

  - Los cuadrados verdes son hipervínculos a las entradas de *GENES*, convirtiendo números K(KO identifiers) a identificadores de genes en las rutas de referencia, mostrando la precencia de genes en el genoma y cuan completo esta la vía.
  
¿Con qué rutas se cruza la ruta metabólica?

  - La ruta se cruza con: la interacción *ECM-receptor*, la contracción muscular cardiaca, el sistema renina-angiotensina, la vía de señalización *Jak-STAT*, y la vía de señalización TGF-beta.
  
¿Cuántos "dominios" forman la anotación GO?

  - la anotacion GO tiene tres dominios o funciones; 1- *Molecular function*, 2- *Cellular component* y 3- *Biological process*.

Ve a "Tools" --> "AmiGO 2" y escribe en la casilla de búsqueda GO:0006096  
¿A qué corresponde este término y qué información te entrega la página?

  - Este término corresponde a información específica sobre el proceso glicolítico. Nos entrega información detallada en el primer link, anotaciones directas o indirectas de este proceso en el segundo link, y en el tercer link nos entregan todos los genes y productos de genes asociados.
  
Haz clic en "Graph Views" y examina el gráfico. Anota 10 sub-categorías GO a la cual GO:0006096 pertenece

  - Proceso metabólica de ADP, proceso metabólica de ATP, proceso metabólico de coenzimas, metabólismos de organofosfatos, procesamiento metabólico de ácidos organicos, catabolismo de organismos simples, metabólismo de componentes glicosílicos, metabólismo de fosforo, metabolismo de nucleotidos nicotinamida y fosforilación nucleotidica.
  
  ### Descargando secuencias, convirtiendo formatos
  
  #### Responde
  
¿Cuántos items fueron encontrados? ¿cuántos en animales?

  - Encontre 86,453 resultados para secuencias de DNA y RNA. De las cuales 12,034 fueron relacionadas con animales.
  
Probablemente tus resultados fueron una mezcla de fragmentos de genes, regiones codificantes parciales, genes completos, etc. Filtra tus datos por mRNA, animales, RefSeq.
Haz clic en la entrada para la secuencia de GAPDH de gallina. 
¿Cuál es la longitud del gen? 

  - La longitud es de 1,288 pb
  
¿Cuál es la referencia bibliográfica más reciente? 

  - 9 de Julio del 2017
  
¿Cuál es el número de acceso?

  - NM_204305.1
  
Descarga la secuencia en formato fasta y agrégala a tu informe

   Formato FASTA
   
           >NM_204305.1 Gallus gallus glyceraldehyde-3-phosphate dehydrogenase (GAPDH), mRNA
           ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAAAGGCGAGATGGTGAAAGTCG
           GAGTCAACGGATTTGGCCGTATTGGCCGCCTGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGT
           GGTGGCCATCAATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGATTCTACACAC
           GGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAACTTGTGATCAATGGGCACGCCATCACTATCT
           TCCAGGAGCGTGACCCCAGCAACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG
           TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTAAGCGTGTTATCATCTCAGCT
           CCCTCAGCTGATGCCCCCATGTTTGTGATGGGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTG
           TCAGCAATGCATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACAACTTTGGCAT
           TGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCCACACAGAAGACGGTGGATGGCCCCTCTGGG
           AAGCTGTGGAGAGATGGCAGAGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG
           TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTCCGTGTGCCAACCCCCAATGT
           CTCTGTTGTTGACCTGACCTGCCGTCTGGAGAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAG
           GCTGCTGCTGATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCCTGTGACTTCA
           ATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGGCATTGCACTGAATGACCATTTCGTCAAGCT
           TGTTTCCTGGTATGACAATGAGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC
           AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACCCTTTGTTGGAGCCCCTGCTC
           TTCACCACCGCTCAGTTCTGCATCCTGCAGTGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCT
           CCAATTTCTTCCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTGTACCACCTTA
           CATCAATAAAAGTGTTCACCATCTGAAG

   Formato NEXUS
   
           #NEXUS
       [TITLE: Written by EMBOSS 15/08/17]

       begin data;
       dimensions ntax=1 nchar=1288;
       format interleave datatype=DNA missing=N gap=-;

       matrix
       NM_204305.1          ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAA

       NM_204305.1          AGGCGAGATGGTGAAAGTCGGAGTCAACGGATTTGGCCGTATTGGCCGCC

       NM_204305.1          TGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGTGGTGGCCATC

       NM_204305.1          AATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGA

       NM_204305.1          TTCTACACACGGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAAC

       NM_204305.1          TTGTGATCAATGGGCACGCCATCACTATCTTCCAGGAGCGTGACCCCAGC

       NM_204305.1          AACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG

       NM_204305.1          TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTA

       NM_204305.1          AGCGTGTTATCATCTCAGCTCCCTCAGCTGATGCCCCCATGTTTGTGATG

       NM_204305.1          GGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTGTCAGCAATGC

       NM_204305.1          ATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACA

       NM_204305.1          ACTTTGGCATTGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCC

       NM_204305.1          ACACAGAAGACGGTGGATGGCCCCTCTGGGAAGCTGTGGAGAGATGGCAG

       NM_204305.1          AGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG

       NM_204305.1          TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTC

       NM_204305.1          CGTGTGCCAACCCCCAATGTCTCTGTTGTTGACCTGACCTGCCGTCTGGA

       NM_204305.1          GAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAGGCTGCTGCTG

       NM_204305.1          ATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCC

       NM_204305.1          TGTGACTTCAATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGG

       NM_204305.1          CATTGCACTGAATGACCATTTCGTCAAGCTTGTTTCCTGGTATGACAATG

       NM_204305.1          AGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC

       NM_204305.1          AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACC

       NM_204305.1          CTTTGTTGGAGCCCCTGCTCTTCACCACCGCTCAGTTCTGCATCCTGCAG

       NM_204305.1          TGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCTCCAATTTCTT

       NM_204305.1          CCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTG

       NM_204305.1          TACCACCTTACATCAATAAAAGTGTTCACCATCTGAAG
       ;

       end;
       begin assumptions;
       options deftype=unord;
       end;
       
### Buscando artículos científicos en linea

![Imagén 2](https://raw.githubusercontent.com/dhermo/lab/master/alerta%20ncbi.png)
Imagén 2: Alerta NCBI

![Imagén 3](https://raw.githubusercontent.com/dhermo/lab/master/mail%20nature.png)
Imagén 3: Mail de Nature

#### Responde

¿Son los resultados idénticos o no?

  - No, los resultados con comillas fueron más acotados.
  
¿En qué cambiaron los resultados de la búsqueda?

  - Cambio en el final de la frase, donde se añadio una palabra más.
  
¿Qué encuentras en los resultados? Prueba sin el rango también

  - Al aumentar un rango, aumenta los resultados en google.
  
Para buscar artículos científicos también es útil restringir los resultados de búsqueda a tipos de archivo. Prueba con "human microbiome" filetype:pdf Describe tus resultados
