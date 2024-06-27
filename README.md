# Proyecto-Final
    1  cd Desktop
    2  cd MedusasProyectoFinal
    3  ls
    4  cd muscle5.1.win64.exe
    5  cd muscle5.1.win64
    6  ./ muscle5.1.win64
    7  ./muscle5.1.win64.exe
    8  ls
    9  mus
   10  ./muscle3.8.31_i86linux64 ^C
   11  cd BRCA1_refseq_transcript (1).fasta
   12  cd 'BRCA1_refseq_transcript (1).fasta'
   13  ls
   14  ls
   15  cd GENES
   16  cat GENES.fasta
   17  cd GENES.fasta
   18  ls
   19  cd genes
   20  ls
   21  mus
   22  ls muscle5.1.win64.exe
   23  ls
   24  ./muscle5.1.win64.exe -align "GENES.fasta" -output aln.afa
   25  ./muscle5.1.win64.exe
   26  echo "# MedusasProyectoFinal" >> README.md
   27  git init
   28  git add README.md
   29  git commit -m "first commit"
   30  git branch -M main
   31  git remote add origin git@github.com:VanessaVallejoR/MedusasProyectoFinal.git
   32  git push -u origin main
   33  raxmlHPC -s aligned.fasta -n output_tree -m GTRGAMMA -p 12345
   34  clustalw -INFILE=input.fasta -OUTFILE=aligned.aln -OUTPUT=FASTA
   35  clustalw -INFILE=GENES.fasta -OUTFILE=aln.afa -OUTPUT=FASTA
   36  cd..
   37  cd ..
   38  cd ..
   39  ls
   40  cd iqtree-2.3.4-Windows
   41  ls
   42  cd bin
   43  ls
   44  pwd
   45  export IQTREE= /c/Users/Vane/Desktop/iqtree-2.3.4-Windows/bin
   46  export IQTREE=/c/Users/Vane/Desktop/iqtree-2.3.4-Windows/bin
   47  export IQTREE=/c/Users/Vane/Desktop/iqtree-2.3.4-Windows/bin/iqtree2
   48  $IQTREE
   49  cd ..
   50  cd ..
   51  cd MedusasProyectoFinal
   52  ls
   53  cd genes
   54  $IQTREE -s aln.afa -B 1000
   55  history 100000 > GitHUB.txt
