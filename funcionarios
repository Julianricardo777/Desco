// Definindo a classe Funcionario
class Funcionario {
    constructor(nome, idade, cargo) {
      this.nome = nome;
      this.idade = idade;
      this.cargo = cargo;
    }
  
    seApresentar() {
      console.log(`Olá, meu nome é ${this.nome}, tenho ${this.idade} ano e sou ${this.cargo}.`);
    }
  
    trabalhar() {
      console.log(`Estou executando minhas funções como ${this.cargo}.`);
    }
  }
  
  // Definindo a classe Gerente que herda de Funcionario
  class Gerente extends Funcionario {
    constructor(nome, idade, departamento) {
      super(nome, idade, 'Gerente');
      this.departamento = departamento;
    }
  
    gerenciar() {
      console.log(`Como gerente do departamento de ${this.departamento}, estou gerenciando as atividades.`);
    }
  }
  
  // Definindo a classe Desenvolvedor que herda de Funcionario
  class Desenvolvedor extends Funcionario {
    constructor(nome, idade, linguagem) {
      super(nome, idade, 'Desenvolvedor');
      this.linguagem = linguagem;
    }
  
    programar() {
      console.log(`Estou programando em ${this.linguagem}.`);
    }
  }
  
  // Criando instâncias de um gerente e de um desenvolvedor
  const gerenteAlex = new Gerente('Alex', 35, 'TI');
  const desenvolvedorMario = new Desenvolvedor('Mario', 28, 'JavaScript');
  
  // Chamando métodos apropriados para cada funcionário
  gerenteAlex.seApresentar();
  gerenteAlex.trabalhar();
  gerenteAlex.gerenciar();
  
  desenvolvedorMario.seApresentar();
  desenvolvedorMario.trabalhar();
  desenvolvedorMario.programar();
  
