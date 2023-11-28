## My Favorite Gene

Let's create a representation of my favorite gene by assigning variables to its individual components:

```python
# Gene components
promoter = "TATAAAG"
utr_5 = "ATGCTA"
start_codon = "ATG"
exon1 = "AGTCTAG"
intron = "GTACGTA"
exon2 = "CTAGCTA"
stop_codon = "TAA"
utr_3 = "AATTAG"

# Concatenate gene components
favorite_gene = promoter + utr_5 + start_codon + exon1 + intron + exon2 + stop_codon + utr_3

# Print the entire gene
print(favorite_gene)
