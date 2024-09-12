# Pro-RNA
 
Supplementary material for the article "A strategy for refining the calculation of contacts in protein-RNA complexes".


## Atom types

The following table presents the atom type classifications made by Luna (https://luna.readthedocs.io/en/latest/getting_started.html) for RNA and the classifications extracted from nApoli (https://ieeexplore.ieee.org/document/8606950) for amino acids.


<table>

<tr>
	<th>Atom type </th>
	<th>Amino acids (atoms)</th> 
	<th>RNA (atoms)</th>
</tr>
<tr>
	<td>Acceptor</td>
	<td>A (O), R (O), N (O, OD1), D (O, OD1,
OD2), C (O), Q (O, OE1), E (O, OE, OE2),
G (O), H (O), I (O), L (O), K (O), M (O),
F (O), P (O), S (O), T (O), W (O), Y (O),
V (O)</td>
<td>a:O3’, a:O2’, a:OP1, a:OP2, a:N7, a:N3,
a:N1, c:O5’, c:O4’, c:O3’, c:O2’, c:OP1,
c:OP2, c:N3, c:O2, g:O5’, g:O4’, g:O3’,
g:O2’, g:OP1, g:OP2, g:C6, g:N1, g:O6,
u:O5’, u:O4’, u:O3’, u:O2’, u:OP1, u:OP2,
u:N3, u:O4, u:O2</td>
</tr>
<tr>
<td>Aromatic </td>
	<td>H (CD2, CE1, CG, ND1, NE2), F (CD1,
CD2, CE1, CE2, CG, CZ), W (CD1, CD2,
CE2, CE3, CG, CH2, CZ2, CZ3, NE1), Y
(CD1, CD2, CE1, CE2, CG, CZ)</td>
<td>a:C8, a:C6, a:C5, a:C4, a:C2, a:N9, a:N7,
a:N3, a:N1, c:C2, c:C4, c:C5, c:C6, c:N1,
c:N3, g:C8, g:C6, g:C5, g:C4, g:C2, g:N9,
g:N7, g:N3, g:N1, u:C6, u:C5, u:C4, u:C2,
u:N3, u:N1</td>
</tr>
<tr>
<td>Donor </td>
	<td>A (N), R (N, NE, NH1, NH2), N (N, ND2,
OD1), D (N), C (N), Q (N), E (N), G (N), H
(N, ND1, NE2), I (N), L (N), K (N, NZ), M
(N), F (N), P (N), S (N, OG), T (N, OG1),
W (N, NE1), Y (N, OH), V (N)</td>
<td>a:O2’, a:N6, c:O2’, c:N4, g:O2’, g:C2,
g:N2, g:N1, u:O2’, u:N3</td>

</tr>
<tr>
<td>Hydrophobic </td>
	<td>A (CB), R (CB, CD, CG, CZ), N (CB, CG),
D (CB, CG), C (CB), Q (CB, CD, CG), E
(CB, CD, CG), H (CB, CD2, CE1, CG), I
(CB, CD1, CG1, CG2), L (CB, CD1, CD2,
CG), K (CB, CD, CE, CG), M (CB, CE,
CG, SD), F (CB, CD1, CD2, CE1, CE2,
CG, CZ), P (CB, CD, CG), S (CB), T (CB,
CG2), W (CB, CD1, CD2, CE2, CE3, CG,
CH2, CZ2, CZ3), Y (CB, CD1, CD2, CE1,
CE2, CG, CZ), V (CB, CG1, CG2)</td>
<td>c:C6, u:C5</td>
</tr>
</table>