# First Order AC-Unification
The formalisation of first-order AC-unification in PVS as presented in the paper "A Certified Algorithm for AC-Unification". 

OBS: In this repository we don't have the proof of how to remove hypothesis $\delta \subseteq V$ from the proof of completeness. 
However, the formalisation along with this proof can be found [here](https://github.com/gabriel951/first_order_ac_unification).

## Highlights 

### Major Theorems 
| Theorem | Location | PVS name |  
| ----    | ----     | ----     |  
| Soundness of Unification | `first_order_AC_unif@unification_alg` | `unify_alg_correct_cor` |  
| Completeness of Unification | `first_order_AC_unif@unification_alg` | `unify_alg_complete_cor` |   


# Contributors 
* [Mauricio Ayala-Rincón](https://www.mat.unb.br/ayala/), University of Brasília, Brazil
* [Maribel Fernández](https://www.kcl.ac.uk/people/maribel-fernandez), King's College London, UK 
* [Gabriel Ferreira Silva](https://gabriel951.github.io/), University of Brasília, Brazil
* [Daniele Nantes-Sobrinho](https://www.mat.unb.br/dnantes/), University of Brasília, Brazil 
