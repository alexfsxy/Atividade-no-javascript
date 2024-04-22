/*Escreva um algoritmo para ler o número total de eleitores de
um município, o número de votos brancos, nulos e válidos. Calcular e escrever
o percentual que cada um representa em relação ao total de eleitores.*/

let eleitores = 500
let vbrancos = 10
let vnulos = 20
let vvalidos = 180

vbpercentual = (100 * vbrancos) / eleitores
vnpercentual = (100 * vnulos) / eleitores
vvpercentual = (100 * vvalidos) / eleitores

console.log('Votos em Branco: ', vbpercentual)
console.log('Votos Nulos: ', vnpercentual)
console.log('Votos Válidos: ', vvpercentual)
