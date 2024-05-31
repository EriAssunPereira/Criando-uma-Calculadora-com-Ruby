# Criando uma Calculadora com Ruby

Ruby é uma linguagem de programação poderosa e flexível, conhecida por sua capacidade de criar programas concisos e legíveis. Uma calculadora é um excelente projeto para iniciantes e intermediários que desejam aprimorar suas habilidades em Ruby, pois abrange conceitos fundamentais como entrada/saída, manipulação de strings e lógica condicional.

## Módulos em Ruby

Módulos em Ruby são uma forma de agrupar métodos, classes e constantes relacionados. Eles são muito úteis para organizar o código e evitar conflitos de nomes em programas maiores.

```ruby
module Calculadora
  def self.soma(a, b)
    a + b
  end

  def self.subtrai(a, b)
    a - b
  end

  def self.multiplica(a, b)
    a * b
  end

  def self.divide(a, b)
    return 'Erro: Divisão por zero' if b == 0
    a.to_f / b
  end
end
```

## Utilizando os Módulos

Para usar os métodos definidos no módulo `Calculadora`, você pode fazer uma chamada direta aos métodos do módulo, passando os argumentos necessários.

```ruby
puts Calculadora.soma(5, 3) # Saída: 8
puts Calculadora.subtrai(10, 7) # Saída: 3
puts Calculadora.multiplica(4, 6) # Saída: 24
puts Calculadora.divide(20, 0) # Saída: Erro: Divisão por zero
puts Calculadora.divide(20, 5) # Saída: 4.0
```

## Desafio: Melhorando o Projeto

Agora que você tem uma base, por que não expandir a calculadora para incluir funções como exponenciação ou raízes quadradas? Ou talvez adicionar uma interface gráfica usando a gem `gosu` ou `tk`? Lembre-se de que a prática leva à perfeição!

## Compartilhando seu Projeto

Após concluir e testar sua calculadora, é hora de compartilhá-la com o mundo. Crie um repositório no GitHub e faça o upload do seu código. Não se esqueça de incluir um `README.md` detalhado com instruções sobre como executar o programa e exemplos de uso. Se você criou uma interface gráfica, considere adicionar screenshots ao seu `README.md`.

Além disso, se você utilizou recursos externos, como um banco de dados ou um template do Figma, certifique-se de incluir links ou arquivos necessários no repositório para que outros possam facilmente configurar e usar sua calculadora.

Espero que este guia tenha sido útil para você que precisa começar com o seu projeto de calculadora em Ruby.
