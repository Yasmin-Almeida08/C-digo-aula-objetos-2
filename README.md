# C-digo-aula-objetos-2
const estudante = {
    nome: "Vinicius",
    idade: 15,
    prontuario: 1234,
    turma: "Desenvolvimento web",
    bolsista: true,
    telefones: ["1234-56789", "9874-84833"],
    // endereco: [{
    //     rua: "Nome da rua",
    //     numero: "500",
    //     bairro: "Santa Cruz"
    // },
    // {
    //     rua: "Rua 2",
    //     numero: "23B",
    //     bairro: "Sabiá"
    // }]
}

console.log(typeof estudante) //object
console.log(estudante)

//acessando propriedades do objeto
console.log(estudante.telefones) // lista de telefones
console.log(estudante.telefones[1])
console.log(estudante['idade'])

// estudante.endereco = {
//     rua: "Nome da rua",
//     numero: "500",
//     bairro: "Santa Cruz"
// }

// console.log(estudante.endereco.rua)
