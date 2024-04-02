# prova-ted Danilo Nunes Murilo Moret gabriel Gonçalves

//Crie uma função criarFila() que caso não receba um tamanho, use um tamanho padrão:
export function criarFila(tamanho=2) { 
    return [... new Array(tamanho)]
}
//Crie uma função inserirFila(), e faça uma verificação que, caso não receba item ou fila, não faça nada e retorne uma mensagem de erro:

 export function InserirFila(fila={}) {
 if (fila.includes(undefined)) {
    fila[fila.indexOf(undefined)] = item
    return 
 }

 }
console.log("fila cheia");
return
//. Crie uma função removerFila() e faça uma verificação que, caso não receba uma fila, não faça nada e retorne uma mensagem de erro.

export function removerDaFila(fila = []){

    if (fila[0] === undefined) {
        console.log("fila vazia");
        return
        }
        let primeiroLugar = fila[0]
        for (let i = 0; i < fila.length -1; i++) {
        fila[i] = fila[i+1]
        }
        fila[fila.length -1] = undefined
        console.log(primeiroLugar);
        return primeiroLugar
        }
 //Crie uma função esvaziarFila(), onde deve retirar TODOS itens da fila, e manter apenas o primeiro. (a fila não deve mudar de tamanho)texto em itálico:

export function EsvaziarFila(fila=[]) {
    if (fila[0] === undefined) {
    console.log("a fila ja esta vazia");
    return
    }
    let primeiro = fila[0]
    for (let i = 0; i < fila.length; i++) {
    fila[i]=undefined
    }
    fila[0]= primeiro
    }
//5. Crie uma função verTamanhoFila(), onde você deve retornar um objeto como o exemplo abaixo:
