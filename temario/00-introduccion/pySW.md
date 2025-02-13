# Algunos proyectos de software

## 1997 - [pySigHor](https://github.com/mmasias/pySigHor)

```
   cloc pySigHor/
      36 text files.
      19 unique files.                              
      59 files ignored.

github.com/AlDanial/cloc v 1.98  T=0.02 s (1203.4 files/s, 204964.8 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Visual Basic                     8            326            183           1916
Markdown                         5            112              0            340
PlantUML                         2             18              0            219
INI                              2              9              0            111
SVG                              2              0              0              2
-------------------------------------------------------------------------------
SUM:                            19            465            183           2588
-------------------------------------------------------------------------------
```

## HerramientasFinancieras

### 1997 - [Versión 1](https://github.com/mmasias/HerramientasFinancierasV1)

```
   cloc HerramientasFinancierasV1/
     121 text files.
     119 unique files.                                          
     540 files ignored.

github.com/AlDanial/cloc v 1.98  T=0.04 s (2720.3 files/s, 369459.0 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Visual Basic                    36           2215           1381           6888
HTML                            79            705             11           4823
Text                             3             24              0            103
Markdown                         1              6              0              6
-------------------------------------------------------------------------------
SUM:                           119           2950           1392          11820
-------------------------------------------------------------------------------

```

### 1999 - [Versión 2](https://github.com/mmasias/HerramientasFinancieras)

```
   cloc HerramientasFinancieras
      33 text files.
      30 unique files.                              
      36 files ignored.

github.com/AlDanial/cloc v 1.98  T=0.02 s (1240.1 files/s, 468996.2 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Visual Basic                    29           3047            990           7281
Markdown                         1              9              0             19
-------------------------------------------------------------------------------
SUM:                            30           3056            990           7300
-------------------------------------------------------------------------------

```

## 2003 - [NutrIber](https://github.com/mmasias/NutrIber)

```
   cloc NutrIber/
     124 text files.
      99 unique files.                              
    1058 files ignored.

github.com/AlDanial/cloc v 1.98  T=0.13 s (774.7 files/s, 739282.5 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Visual Basic                    77          10571          54527          26376
HTML                            19            318              0           2435
CSS                              1             40              2            207
DOS Batch                        1              0              0              1
Markdown                         1              0              0              1
-------------------------------------------------------------------------------
SUM:                            99          10929          54529          29020
-------------------------------------------------------------------------------

```



## 2007 - [QualityCourses](https://github.com/mmasias/pyQualityCourses)

```
   cloc pyQualityCourses/
     534 text files.
     483 unique files.                                          
     256 files ignored.

github.com/AlDanial/cloc v 1.98  T=0.21 s (2318.4 files/s, 509942.7 lines/s)
---------------------------------------------------------------------------------
Language                       files          blank        comment           code
---------------------------------------------------------------------------------
JavaScript                       201           7088           9585          43617
HTML                             101           1531           2603          16064
PHP                               80           1203           1372           5238
CSS                               20           1271            480           3217
ColdFusion                        23            369            658           1961
Perl                              15            302            632           1576
ColdFusion CFScript                3            236             42           1551
ASP                               14            274            326           1288
Text                               3            210              0           1138
Python                            12            242            466            767
XML                                4             34            105            373
SQL                                1             48             24            122
ASP.NET                            3             14             84             67
Markdown                           1              4              0              5
DOS Batch                          2              6             42              4
---------------------------------------------------------------------------------
SUM:                             483          12832          16419          76988
---------------------------------------------------------------------------------

```

## Como diría ChatGPT: "en resumen..."

|Año|Proyecto|VB LOC|HTML LOC|Otros LOC|Total LOC|Comentarios|Ratio código/comentarios|Páginas código|Páginas comentarios|
|-|-|-|-|-|-|-|-|-|-|
|1997|pySigHor|1,916|-|672|2,588|183|10.47|43|3
|1997|HerramientasFinancieras V1|6,888|4,823|109|11,820|1,381|4.99|197|23
|1999|HerramientasFinancieras V2|7,281|-|19|7,300|990|7.35|122|17
|2003|NutrIber|26,376|2,435|209|29,020|54,527|0.48|484|909
|2007|QualityCourses|-|16,064|60,924|76,988|16,419|4.69|1283|274

Notas:

- En "Otros LOC" para QualityCourses se incluye principalmente JavaScript (43,617 líneas) y otras tecnologías.
- El ratio código/comentarios es calculado dividiendo el total de líneas de código entre el número de comentarios.
- Un ratio menor que 1 (como en NutrIber) indica más comentarios que código.
- Un ratio mayor indica más código que comentarios.
- Basados en 60 líneas por página.
