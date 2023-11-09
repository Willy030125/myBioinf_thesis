# Bioinformatics (Bachelor Thesis) Project
This is my Thesis Project:<br>
Virus Classification based on DNA and Protein (Amino Acid) Sequences using:
- Temporal Convolutional Networks (TCN) built from scratch
- Gated Recurrent Unit (GRU)
- Long Short-Term Memory (LSTM)
- Regular RNN (Vanilla RNN in Tensorflow)
- Bidirectional GRU (additional seperate script for academic papers)

Feature Extraction used for DNA Sequences:<br>
- Index-based Encoding
- Index-based Encoding (with Embeddings)
- N-mers Frequency
- N-mers Frequency (with Embeddings)


Feature Extraction used for Protein (Amino Acid) Sequences:<br>
- Conjoint Triad
- Conjoint Triad (with Embeddings)


Dataset acquired from:<br>
- <i>National Center of Biotechnology Information (NCBI)</i>

Type of Viruses:<br>
- SARS-CoV-2 (COVID-19) => 20 FASTA of DNA + 20 FASTA of Protein Sequences
- Ebolavirus  => 20 FASTA of DNA + 20 FASTA of Protein Sequences
- Zika virus  => 20 FASTA of DNA + 20 FASTA of Protein Sequences
- MERS-CoV  => 20 FASTA of DNA + 20 FASTA of Protein Sequences
- Adenovirus  => 20 FASTA of DNA + 20 FASTA of Protein Sequences
- Parainfluenza virus  => 20 FASTA of DNA + 20 FASTA of Protein Sequences
- Rhinovirus  => 20 FASTA of DNA + 20 FASTA of Protein Sequences


Additional method:<br>
- Using Stratified K-Fold Cross Validation for training data
