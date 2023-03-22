# Exercitando com: classes em Kotlin

- Este repositório consiste no seguinte problema: escrever uma classe para conter três membros de dados do tipo int denominados horas, mins e segs e chamá-la de Tempo. Visando o estudo e aprofundamento em POO usando a linguagem Kotlin.



class Tempo{
  var hora:Double = 0.0
  var min:Double = 0.0
  var segs:Double = 0.0

}

Veja que acima nos temos apenas a estrutura da classe formada, e precisamos instanciar a mesma. E para isso é preciso fazer a chamada da classe Tempo() dentro da função principal do nosso código.

fun main(){
  var tempoA = Tempo()
  tempoA.hora = 1.5
  println(tempoA.hora)


}

Agora a classe foi instanciada e armazenada dentro de uma variável chamada tempoA (bem criativo kkkk), e a partir disso foi criado um objeto onde através dele será possível acessar as propriedades da classe assim como chamar os métodos.
