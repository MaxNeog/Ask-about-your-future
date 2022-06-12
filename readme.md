# HTML
- Hyper Text Markup Language

- Hiper Texto ?
- Marcação
  - tags
  -atributos

- Linguagem
  - maneira de escrever  


  O que é HyperText
  O que é Markup
  O que é tag
  O que é linguagem HTML?

  # Intro ao css
  # Declaração
  - seletor
  - propriedade e valor

  # Conceitos
  - Cascata
  - Especificidade
  - Box Model

  # O valor border-box impede que o padding e a borda do elemento sejam somados à largura e altura do elemento, por isso o seu botão fica menor que os campos de texto, que possuem como padrão o valor content-box (você pode saber mais sobre o box-sizing nesta documentação).

Para resolver isso, basta você alterar o box-sizing do botão para content-box, que tudo irá ficar com o mesmo tamanho, pois o botão irá somar o padding e o border às suas dimensões:

  // 1. variaveis
    // let estaChovendo = true;
    // const meuNome = "Max";

  // 2. Tipos de dados
    // String
    // ""
    // ''
    
  // 3. Numbre
    // 12 - integer (+ -)
    // 3.2 - float (+ -)

  // 4. Boolean
    // true or false
    // const MaiorDeDezoito = false;

  // 5. undefined - Indefinido
  
  // 6. Operadores
    // Atrbuição (ex: =)
    // atribuir valor
    let n1 = 12;
    let n2 = 3;    

  // 7. console.log(n1 * n2);;

  // 8. aritméticos (ex: * / + -)
    // calculos matemáticos simples
  console.log(12 / 4);

  // 9. concatenação de string (+)
  console.log("23" + 4);

  // 10. comparação (ex: > < ==)
    // transforma a expressão em true ou  false
  const maiorQue = 1 > 2; // false
  const igualA = 1 == 1; // true

  // 11. condicional (if/else)
  const idade = 17;
  const maiorDeDezoito = idade >= 18;

  if (maiorDeDezoito) {
    alert("Pode tirar carteira de motorista")
  } else {
    alert("Não pode tirar")
  }

  // 12. Estrutura de dados
    // array - vetor - list
    // array -----         0     1    2  3
    const temperaturas = [23.3, 32.2, 1, 5];

  // 13. object
    const pessoa = {
      nome: "Max",
      idade: 28,
      filhos ["A", "B", "C"]
    }  
    console.log(pessoa.idade);
    console.log(pessoa.filhos[2]);

  // 14. Function
    1. Criação
    function nomeDaFuncao() {
      console.log('código dentro da função)
    }

    2. Execusão
    nomeDaFuncao()

  // 15. parâmetros  
    function soma (a, b {
      console.log(a + b)
    }
    soma(34, 45);
    soma(90, 54);
  // 16. retorno
    function soma(a, b)  {
      return a + b
    }
    const multiplica = soma(2, 2) * 4;
    console.log(multiplica);
    console.log(soma(2, 2));

  // 17. extenções de linguagem (ex: math, date ...)
    // math.randow()
    // math.floor(1.2)
    // math.ceil(1.2)
    // math.pi

  // 18. DOM - document object Model
    // window
    // window.alert("alerta")
    // document
    // document.write("texto")
    // manipular elementos
    // documento.documentElement.style.background = "black"