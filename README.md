# cifradecesar.js

function criptografar(frase, chave){
    const alfabeto = "ABCDEFGHIJKLMNOPQRSTUVWXYZ".split("");
    let resultado = "";

    // Transformar a chave em um deslocamento
    chave = chave.toUpperCase();
    const deslocamento = alfabeto.indexOf
    (chave);

frase = frase.toUpperCase();

//Percorrer cada caractere da frase
for(let i = 0; i < frase.lentgh; i++){
    const char = frase[i];

    // Verificar se o caractere está no alfabeto
   if (alfabeto.includes(char)){
    const index = alfabeto.indexOf
    (char);
    const novoIndex = (index = deslocamento)
   }

}

}