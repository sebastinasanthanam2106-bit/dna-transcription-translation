# DNA Transcription and Translation Using Python

## Project Overview

This project simulates the basic steps of molecular biology by transcribing a DNA coding sequence into mRNA and translating the mRNA into an amino acid sequence.

## Objectives

* Accept a DNA coding sequence as input.
* Validate nucleotide characters.
* Transcribe DNA into mRNA.
* Identify the AUG start codon.
* Divide the sequence into triplet codons.
* Translate codons using the standard genetic code.
* Stop translation at the first in-frame stop codon.
* Display the predicted amino acid sequence.

## Tools

* Python 3
* Google Colab
* GitHub

## Biological Concepts

DNA transcription, mRNA, codons, the genetic code, translation, start codons, stop codons, and protein sequence prediction.

## Example

DNA coding sequence: ATGGCTTAA

mRNA sequence: AUGGCUUAA

Codons: AUG, GCU, UAA

Predicted protein sequence: MA

Amino acids: Methionine, Alanine

## Limitations

This is a simplified educational translation program. It searches for the first AUG, translates in that reading frame, and stops at the first in-frame stop codon. It does not identify all open reading frames, scan both DNA strands, or experimentally confirm protein expression.

## Future Improvements

* Support FASTA file input.
* Use Biopython for sequence translation.
* Identify multiple open reading frames.
* Analyse both DNA strands.
* Add a graphical representation of codons and amino acids.

##Author
M.Sebastinamary
MSc Bioinformatics Student

This project was developed as part of my learning in Python programming and Molecular Biology .
