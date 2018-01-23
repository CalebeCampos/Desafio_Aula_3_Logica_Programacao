
<meta charset="UTF-8">
<script>

/*
1 sorrisoMaroto
2 zecaPagodinho
3 exaltaSamba
4 charlieBrownJr
5 cpm22 
6 acdc
7 racionais
8 triboDaPeriferia
9 hungria
10 chimarruts 
11 natiruts
12 maskavo
*/

function pularLinha() {
	document.write('<br>');
}

function mostrar(frase) {
	document.write(frase);
	pularLinha();
}

// bandas categoria samba
var sorrisoMaroto = 0;
var zecaPagodinho = 0;
var exaltaSamba = 0;
// bandas categoria rock
var charlieBrownJr = 0;
var cpm22 = 0;
var acdc = 0;
// bandas categoria rap
var racionais = 0;
var triboDaPeriferia = 0;
var hungria = 0;
// bandas categoria reggae
var chimarruts = 0;
var natiruts = 0;
var maskavo = 0;
// categorias
var melhorCategroriaSamba = 0
var melhorCategroriaRock = 0
var melhorCategroriaRap = 0
var melhorCategroriaReggae = 0

// pontuacao melhor categoria samba
while(melhorCategroriaSamba != 99) {
	
	melhorCategroriaSamba = parseInt(prompt('Qual a melhor banda da categoria Samba? Digite o número correspondente: 1-Sorriso Maroto, 2-Zeca Pagodinho, 3-Exalta Samba, 99-Próxima Categoria'));
	
	if (melhorCategroriaSamba == 1) {
		sorrisoMaroto = sorrisoMaroto + 1;
	}

	if (melhorCategroriaSamba == 2) {
		zecaPagodinho = zecaPagodinho + 1;
	}

	if (melhorCategroriaSamba == 3) {
		exaltaSamba = exaltaSamba + 1;
	}
}

// pontuacao melhor categoria rock
while(melhorCategroriaRock != 99) {

	melhorCategroriaRock = parseInt(prompt('Qual a melhor banda da categoria Rock? Digite o número correspondente: 4-Charlie Brown Jr., 5-CPM22, 6-ACDC, 99-Próxima Categoria'));

	if (melhorCategroriaRock == 4) {
		charlieBrownJr = charlieBrownJr + 1;
	}

	if (melhorCategroriaRock == 5) {
		cpm22 = cpm22 + 1;
	}

	if (melhorCategroriaRock == 6) {
		acdc = acdc + 1;
	}
}	
// pontuacao melhor categoria rap
while(melhorCategroriaRap != 99) {
	
	melhorCategroriaRap = parseInt(prompt('Qual a melhor banda da categoria Rap? Digite o número correspondente: 7-Racionais, 8-Tribo da Periferia, 9-Hungria, 99-Próxima Categoria'));

	if (melhorCategroriaRap == 7) {
		racionais = racionais + 1;
	}

	if (melhorCategroriaRap == 8) {
		triboDaPeriferia = triboDaPeriferia + 1;
	}

	if (melhorCategroriaRap == 9) {
		hungria = hungria + 1;
	}	
}
// pontuacao melhor categoria reggae
while(melhorCategroriaReggae != 99) {
	
	melhorCategroriaReggae = parseInt(prompt('Qual a melhor banda da categoria Forro? Digite o número correspondente: 10-Chimarruts, 11-Natiruts, 12-Maskavo, 99-SAIR'));

	if (melhorCategroriaReggae == 10) {
		chimarruts = chimarruts + 1;
	}

	if (melhorCategroriaReggae == 11) {
		natiruts = natiruts + 1;
	}

	if (melhorCategroriaReggae == 12) {
		maskavo = maskavo + 1;
	}
}

mostrar('Melhor da Categoria Samba:');
mostrar('Sorriso Maroto: ' + sorrisoMaroto);
mostrar('Zeca Pagodinho: ' + zecaPagodinho);
mostrar('Exalta Samba: ' + exaltaSamba);
pularLinha();
pularLinha();
pularLinha();
mostrar('Melhor da Categoria Rock:');
mostrar('Charlie Brown Jr: ' + charlieBrownJr);
mostrar('CPM22: ' + cpm22);
mostrar('ACDC: ' + acdc);
pularLinha();
pularLinha();
pularLinha();
mostrar('Melhor da Categoria Rap:');
mostrar('Racionais: ' + racionais);
mostrar('Tribo da Periferia: ' + triboDaPeriferia);
mostrar('Hungria: ' + hungria);
pularLinha();
pularLinha();
pularLinha();
mostrar('Melhor da Categoria Reggae:');
mostrar('Chimarruts: ' + chimarruts);
mostrar('Natiruts: ' + natiruts);
mostrar('Maskavo: ' + maskavo);

</script>
