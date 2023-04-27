# string_inversa
function reverseString(str)

Escreva um programa que inverta os caracteres de um string

function reverseString(str) {
    // Passo 1. Crie uma string vazia que vai receber a nova string criada
    var newString = "";

   // Step 2. Crie o laço FOR
for (var i = str.length - 1; i >= 0; i--) { 
        newString += str[i]; // ou newString = newString + str[i];
    }

// Passo 3. Retorne a string invertida
    return newString; // "olleh"
}
 
reverseString('hello');
