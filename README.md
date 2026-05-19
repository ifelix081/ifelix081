```JavaScript
class Italo {
  constructor() {
    this.name = "Italo Vincius";
    this.username = "ifelix081";
    this.location = "404 not found";
    this.web = "404 not found";
    this.hardskill = "Python, Git, Linux, C";
  }

  toString() {
    return this.name;
  }

  getInfo() {
    return {
      nome: this.name,
      usuario: this.username,
      localizacao: this.location,
      website: this.web,
      habilidades: this.hardskill
    };
  }
}

const me = new Italo();

console.log(`Bem vindo a ${me.toString()}`);
console.log("Informacoes:", me.getInfo());

module.exports = Italo;
