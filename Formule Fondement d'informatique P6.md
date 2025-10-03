  
# Théorème 7

Implication 1, 2
> ( *p* $\implies$ *q* )  $\equiv$ ( $\neg$ *p* $\lor$  *q* )
> ( *p* $\implies$ *q* )  $\equiv$ $\neg$ ( *p* $\land$  $\neg$ *q* )

Équivalence 3

> ( *p* $\iff$ *q* )  $\equiv$  ( *p* $\implies$ *q* ) $\land$ ( *q* $\implies$ *p* )

Involution 4
>  $\neg$ $\neg$ *p* $\equiv$ *p*

Loi de  De Morgan 5, 6
> $\neg$  ( *p* $\lor$ *q* ) $\equiv$  ( $\neg$ *q* $\land$ $\neg$ *p* )
> $\neg$  ( *p* $\land$ *q* ) $\equiv$  ( $\neg$ *q* $\lor$ $\neg$ *p* )

Loi d'absorption 17, 18
> ( *p* $\land$ ( *p* $\lor$ *q* ) ) $\equiv$ *p*
> ( *p* $\lor$ ( *p* $\land$ *q* ) ) $\equiv$ *p*

Distributivité 23, 24
> ( *f* $\land$ ( *p* $\lor$ *q* ) ) $\equiv$  (  ( *f* $\land$ *p* ) $\lor$ ( *f* $\land$ *q* ) )
> ( *f* $\lor$ ( *p* $\land$ *q* ) ) $\equiv$  (  ( *f* $\lor$ *p* ) $\land$ ( *f* $\lor$ *q* ) )

Contraposé 25
> *p* $\implies$ *q*  $\equiv$  $\neg$ ( *q* ) $\implies$ $\neg$ ( *p* )

# Autre formule d'équivalence

Négation de l'implication
> $\neg$ ( *p* $\implies$ *q* )  $\equiv$   *p* $\land$ $\neg$ *q*

Ou-exclusif
> *p* $\oplus$ *q* $\equiv$ ( *p* $\lor$ *q* ) et $\neg$ ( *p* $\land$ *q* ) 

# Tableau sémantiques

Implication 

|  *a* $\implies$ *b* |
|        :---:       |
| $\neg$ *a*  \|  *b* |   

Conjonction

|*a* $\land$ *b*|
|    :---:     |
|     *a*      |
|     *b*      |

Négation de l'implication

| $\neg$ ( *a* $\implies$ *b* )|
|            :---:           |
|          &nbsp  *a*        |
|          $\neg$ *b*         |

Disjonction

| *a* $\lor$ *b*  |
|     :---:      |
|  *a*  \|  *b*  |

Négation d'une disjonction

| $\neg$ ( *a* $\lor$ *b* ) |
|         :---:           |
|       $\neg$ *a*         |
|      $\neg$ *b*          |

Négation d'une conjonction

| $\neg$ ( *a* $\land$ *b* ) &nbsp  |
|              :---:              |
| &nbsp $\neg$ *a*  \|  $\neg$ *b*  |

Si et seulement si

|   ( *a* $\iff$ *b* )   |
|        :---:          |
|   *a*   \|  $\neg$ *a* |
|   *b*   \|  $\neg$ *b* |

Négation du Si et seulement si

|    $\neg$ ( *a* $\iff$ *b* )     |
|              :---:             |
| &nbsp &nbsp *a*   \| $\neg$ *a* |
|  $\neg$ *b*  \|   *b*           |

Ou-exclusif

|    ( *a* $\oplus$ *b* )    |
|            :---:          |
|   *a*  \|  *b*            |
|  $\neg$ *b*  \| $\neg$ *a* |

Non Ou-exclusif

| $\neg$ ( *a* $\oplus$ *b* ) |
|            :---:          |
| $\neg$ *a*   \|   *a*      |
| $\neg$ *b*   \|   *b*      |


# Système de Hilbert - $\mathbb{H}$
### Schémas d'axiome et règle d'inférence

> $\mathbb{C}$*1* : ( *X* $\implies$ ( *Y* $\implies$ *X* ) )
> $\mathbb{C}$*2* : ( ( *X* $\implies$ ( *Y* $\implies$ *Z* ) ) $\implies$ ( ( *X* $\implies$ *Y* ) $\implies$ ( *X* $\implies$ *Z* ) ) )
> $\mathbb{C}$*3* : ( ( $\neg$ *Y* $\implies$ $\neg$ *X* ) $\implies$ ( ( $\neg$ *Y* $\implies$ *X* ) $\implies$ *Y* ) )

> MP : ( ( *X*, ( *X* $\implies$ *Y* ) ), *Y* )

### Autre définitions

Exemple 11 ( *Axiome* )
> ( *A* $\implies$ *A* )

Exemple 12
> ( ( ( *X* $\implies$ *Y* ), ( *Y* $\implies$) *Z* ) ), (*X* $\implies$ *Z* ) )

Exercice 11 
> ( ( ( *X* $\implies$ ( *Y* $\implies$ *Z* ) ), *Y* ), (*X* $\implies$ *Z* ) )

Exercice 12
> ( ( ( $\neg$ *Y* $\implies$ ( $\neg$ *X* $\implies$ *Z* ) ), ( $\neg$ *Y* $\implies$ $\neg$ *X* ) ), ( $\neg$ *Y* $\implies$ *Z* ) )

Exemple 14, 15 & Exercice 14, 15, 16, 17 ( *Axiome* )
> ( $\neg$ $\neg$ *X* $\implies$ *X* )
> ( *X* $\implies$ ( ( *X* $\implies$ *Y* ) $\implies$ *Y* ) )
> 

> ( ( ( *Y* $\implies$ *X* ) $\implies$ *Z* ) $\implies$ ( *X* $\implies$ *Z* ) )
> ( *X* $\implies$ $\neg$ $\neg$ *X* )
> ( ( $\neg$ *Y* $\implies$ $\neg$ *X* ) $\implies$ ( *X* $\implies$ *Y* ) )
> ( ( *X* $\implies$ *Y* ) $\implies$ ( $\neg$ *Y* $\implies$ $\neg$ *X* )  )

Exemple 16
> ( ( *X* $\implies$ *Y* ) $\implies$ ( ( $\neg$ *X* $\implies$ *Y* ) $\implies$ *Y* ) )

Exercice 18
> ( ( ( *P* $\implies$ *M* ), ( *N* $\implies$ *M* ), ( $\neg$ *P* $\implies$ ( *T* $\implies$ *N* ) ), *T* ), *M* )




