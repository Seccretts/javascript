# javascript

class pessoa{
    constructor(nome,idade,cpf,peso,personalidade) {
        this.nome_p = nome;
        this.idade_p = idade;
        this.cpf_p = cpf ;
        this.peso_p = peso;
        this.personalidade_p = personalidade;
    
    }
    retornar_dados(){
        console.log("nome:" + this.nome_p);
        console.log("idade:" + this.idade_p);
        console.log("cpf:" + this.cpf_p);
        console.log("peso:" + this.peso_p);
        console.log("personalidade:" + this.personalidade_p);

    }
}
pessoa1 = new pessoa("amanda",28,61555, 75,"vontade de matar um")
pessoa1.retornar_dados();

pessoa2 = new pessoa("maria",99,65651,90, "pé na cova";
pessoa2.retornar_dados();

)

