---
title: Definición de consultas a RegulonDB
author: Carmina Barberena, Emiliano Fonseca, José Alquicira
---


# Resumen
Este documento tiene como objetivo listar todas las consultas más
importantes y de interés de objetos, atributos e interacciones biológicas.


# Lista de tipos de consultas de interés

## Consultas por TF
###Entrada
- Genes regulados por un factor de transcripción
- Genes que regulan al factor
- Promotores asociados 
- TU asociadas 
- Operónes asociados
###Salida
-TF
-Matriz 

## Consultas por promotor
- Genes asociados a un promotor
- TF asociados 
- TU asociadas 
- Operónes asociados 

## Consultas por TU
- Genes asociados a una unidad de transcripción
- Promotores asociados 
- TF asociados
- Operónes asociados 

## Consultas por operón
- Genes asociados a un operón
- Promotores asociados 
- TU asociadas 
- Operónes asociados 

## Consutas por terminador 
- Genes asociados a un terminador
- Promotores asociados 
- TF asociadas
- TU asociadas 
- Operónes asociados

##Consulta por gen 
### Entradas

### Salidas
- Promotores asociados 
- TF asociadas
- TU asociadas 
- Operónes asociados
- Secuencia 

##Por región genoma 

## GU 
###Entrada
-Gen 
-TF
-Efector
-Condición(Checar)
-Metbolitos
###Salida
-Gen 
-TF
-Efector
-Condición(Checar)
-Metbolitos
-GU 

##Consulta por  validación (Filtro*)
-Tipo 
-Confianza 
##Consulta por experimentos HT

##Consulta por condiciones de crecimiento

#Visualización de datos 

##


FNS
If I have a gene, how can I get all what is known about its regulation and operon organization of melA? 
If we have a set of genes coming from a ChIP-chip experiment with LexA, how can we discover the transcription factor DNA-binding sites (TFDBSs) common to a regulon obtained from RegulonDB?


# Notas

> Incluir id y nombre de objeto como entrada de la búsqueda

> Evaluar incluir búsquedas tipo *google-like* (Search all text)




Atributos

1. Gene identifier assigned by RegulonDB
2. Gene name (bnumber)
3. Gene left end position in the genome
4. Gene right end position in the genome
5. DNA strand where the gene is coded
6. Product type
7. Product name
8. Start codon sequence
9. Stop codon sequence
10. Gene sequence
11. RBS (ribosome binding site)
