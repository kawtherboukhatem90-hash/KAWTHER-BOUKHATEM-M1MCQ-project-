# KAWTHER-BOUKHATEM-M1MCQ-project- 
#Boukhatem kawther ,m1 microbiologie et controle de qualite,06/12/2025
#Bouchenafa Hadil
#Boudjema sanaa
#Ghennou nada
#Gheraz meryem ghizlene 


import pandas as pd 

# Donneès:sèquences ADN ,longueur,pourcentage de GC 
data ={
     "sèquences":["ATGCGTACGTA", "GCTAGCTAGGCC", "ATGCGCGTAAGT", "TACGATCGTA", "ATGAAAGGCTT", "CGTACGTAGC", "TTAACCGGAT"],
     "longueur":[12 , 12 , 12 , 10 , 11 , 10 , 10 ],
     "pourcentage_GC":[50 , 66.67 , 58.33 , 40 , 45.45 , 60 , 60 ]
}
# crèation d`un DataFrame (tableau pandas)
df = pd.DataFrame(data)
print("******************crèation et affichage***************")

#affichage du tableau
print("tableau des sèquences ADN :")
print(df)

 #opèrations sur les tableaux :
print("****************opèrations***********")
#1) sèlectionner la colonne "longueur"
longueur = df ["longueur"]
print(longueur)
