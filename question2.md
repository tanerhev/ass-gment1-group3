#Omer's Answer to Question 2

**Q2.** Question 2: Please assign variables to the individual components of your favorite gene! (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene
by using the string concatenation operator, on the standard output! Note: Feel free to create a
fictional gene sequence by randomly filling in the gene components by the characters
corresponding to individual nucleotide bases.

...
promoter = "TAGTGCTAGCTCGGGG"
five_prime_UTR = "GTACGTACGAGAGAA"
start_codon = "AAG"
exon1 = "CCCGAAAATTTTC"
intron = "AGTGCCCAAAA"
exon2 = "AGCGCGCGCTT"
stop_codon = "GAT"
three_prime_UTR = "ATTTTTTTTTTGCGCGACATCACAA"

my_fav_gene = promoter + five_prime_UTR + start_codon + exon1 + \
              intron + exon2 + stop_codon + three_prime_UTR

print("My favourite gene sequence is as follows:")
print(my_fav_gene)
...
