function piso(nPiso, altura){
    let texto = "<p>"
    for (let i =0; i <altura-nPiso ; i++) {
       texto = texto +"&nbsp;";
    }
    for (let i =0; i <nPiso ; i++) {
        texto = texto +"#";
     }
     texto = texto+"&nbsp;"
     for (let i =0; i <nPiso ; i++) {
        texto = texto +"#";
     }
     texto=texto +"</p>";
     return texto 
}
let nPiso;
do{
    altura = parseInt(prompt("Ingrese un numero de pisos del 1 al 10"))
}
while(altura%1 !=0 || altura > 10 || altura<=0 )
let contenido = ""
for(let i =1; i <=altura; i++){
    contenido = contenido + piso(i, altura)
}
let contenedor = document.querySelector("#contenedor");
contenedor.innerHTML = contenido;