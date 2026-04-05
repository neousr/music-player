Reproductor Web de música


const t = "Hola";

console.log("Cantidad de palabras: " + countWords2(t));

function rmWhitespace(text) {
  return text.trim().replace(/\s\s+/g, " ");
}

function countWords(text) {
  text = rmWhitespace(text);
  let whitespaces = 0;
  for(let i = 0; i < text.length; i++) {
    if(text[i] === " "){
      whitespaces++;
    }
  }
  return whitespaces + 1;
}


function countWords2(text) {
  let count = 0;
  let inWord = false;
  // [WI FI]
  for (let i = 0; i < text.length; i++) {
    if (text[i] !== ' ' && text[i] !== '\t' && text[i] !== '\n') {
      if (!inWord) {
        count++;
        inWord = true;
      }
    } else {
      inWord = false;
    }
  }

  return count;
}


text = Hola Mundo

 O
/|\
/ \    ____ _____

contador = 0
estoyEncimaDeUnaTabla = falso

Para i desde 1 hasta 10 hacer:
    tabla = subir a tabla en posicion i
    si tabla es distinto de "vacio" entonces:
        si negamos estoyEncimaDeUnaTabla entonces:
            contador = contador + 1
            ¿estoyEncimaDeUnaTabla? = verdadero
    si no entonces:
        estoyEncimaDeUnaTabla = falso
Fin para











