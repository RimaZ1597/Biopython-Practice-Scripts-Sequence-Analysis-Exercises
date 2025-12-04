# Biopython Practice Scripts & Sequence Analysis Exercises

This repository contains a collection of small Python scripts created while learning and practising **Biopython** and fundamental bioinformatics operations. Each script focuses on a specific task—such as reading FASTA files, parsing GenBank records, translating sequences, computing nucleotide frequencies, retrieving sequences from NCBI Entrez, and more.

These scripts are ideal for beginners, students, or anyone wanting hands-on practice with sequence analysis using Python.

---

## Features

✔ Read and parse FASTA files  
✔ Read and process GenBank files  
✔ Work with Seq and SeqRecord objects  
✔ Translate DNA → Protein  
✔ Extract ORFs and codon frames  
✔ Retrieve sequences using NCBI Entrez API  
✔ Calculate GC content, nucleotide frequencies  
✔ Work with multiple FASTA files  
✔ Simple search and filtering operations  
✔ Practice scripts for fundamental bioinformatics logic  

---

## 📁 Repository Structure

Below are examples of what the scripts do (based on filenames):

| File Name | Description |
|----------|-------------|
| `1.Bio.Seq.py` | Basic Seq object operations |
| `10.SeqRecord.py` | Creating and modifying SeqRecord objects |
| `11.seq_record.py` | Working with metadata in SeqRecord |
| `12.fasta_read.py` | Reading FASTA files with Biopython |
| `13.Read.py` | General file reading practice |
| `14.SeqIO_read_genbank.py` | Parse GenBank files using SeqIO |
| `15.seqread.py` | Simple sequence reading |
| `16.Genbank_features_annotations.py` | Extract features/annotations from GenBank |
| `17.fasta_process_read.py` | Process FASTA records |
| `18.multi_fasta.py` | Read multi-FASTA files |
| `19.multi_fasta_processing.py` | Filter/query multi-FASTA |
| `20multifasta.py` | Additional multi-FASTA handling |
| `21.fasta_file.py` | File I/O examples |
| `22.Entrez_einfo.py` | Use Entrez E-utilities |
| `22.average_length_fastq.py` | Calculate average read length |
| `23.Esearch.py` | NCBI ESearch examples |
| `24.Efetch.py` | Retrieve sequence using Entrez efetch |
| `25.fetch_genbank.py` | Fetch GenBank record from NCBI |
| `26.retrive_id_and_seq.py` | Fetch sequence by accession |
| `27.py` | Miscellaneous practice |
| `28.esummary.py` | Entrez esummary usage |
| `3.rna_seq1.py` | RNA → Protein transformations |
| `4.translate.py` | DNA translation |
| `5.translate_multiline.py` | Translate multi-line sequences |
| `6.open_read_frames.py` | Identify ORFs and reading frames |
| `7multiline_orf.py` | ORF extraction for multi-line DNA |
| `8.SeqUtils.py` | Using Biopython SeqUtils |
| `9.SeqUtils.py` | GC content, molecular weight, etc. |
| `nucleotide_occupance.py` | Nucleotide frequency/counts |

---

## 🧬 What You Can Learn Here

By exploring these scripts, you will learn how to:

- Handle biological sequences using Python  
- Parse FASTA/FASTQ/GenBank formats  
- Use Biopython’s Seq, SeqRecord, and SeqIO modules  
- Access NCBI databases programmatically  
- Translate, reverse complement, and manipulate sequences  
- Identify ORFs and coding regions  
- Compute biological statistics (GC content, length, codon usage)

---

## 🛠 Requirements

Install Biopython:

```bash
pip install biopython
