# genome_tools
NYAS workshop, genomic scripts

Example usage:

```
echo "name,account"
for fasta in data/*.fa; do
  count=$( bash data/countseq.fa $fasta )
  echo "$fasta,$count"
 done >> my_file.csv
  ```
  
