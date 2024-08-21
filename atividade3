import java.text.DecimalFormat

fun main() {
    // 1. criação de variáveis
    val nomeProduto: String = "Notebook" // usando `val` porque o nome do produto não deve mudar
    val precoUnitario: Double = 2500.0 // usando `val` porque o preço unitário não deve mudar
    val quantidadeComprada: Int = 3 // usando `val` porque a quantidade não deve mudar
    val taxaImposto: Double = 18.0 // usando `val` para a taxa de imposto, que é um valor fixo
    val margemLucro: Double = 20.0 // usando `val` para a margem de lucro, que é um valor fixo

    // 2. atribuição de valores (já foi feita acima)

    // 3. operações simples
    val valorTotalSemImposto: Double = precoUnitario * quantidadeComprada // cálculo do valor total sem impostos

    val valorImposto: Double = valorTotalSemImposto * (taxaImposto / 100) // cálculo do valor do imposto
    val valorTotalComImposto: Double = valorTotalSemImposto + valorImposto // cálculo do valor total com impostos

    val precoVenda: Double = valorTotalComImposto * (1 + margemLucro / 100) // cálculo do preço de venda para atingir a margem de lucro

    // 4. desafio extra: arredondamento e formatação
    val decimalFormat = DecimalFormat("R$ #,##0.00") // formatando como moeda

    val valorTotalComImpostoFormatado: String = decimalFormat.format(valorTotalComImposto) // formatando o valor total com impostos
    val precoVendaFormatado: String = decimalFormat.format(precoVenda) // formatando o preço de venda

    val mensagemFinal: String = "Produto: $nomeProduto\nValor total com impostos: $valorTotalComImpostoFormatado\nPreço de venda sugerido: $precoVendaFormatado" // criando a mensagem final

    // 5. exibição de resultados
    println("Nome do produto: $nomeProduto")
    println("Preço unitário: R$$precoUnitario")
    println("Quantidade comprada: $quantidadeComprada")
    println("Taxa de imposto: $taxaImposto%")
    println("Margem de lucro: $margemLucro%")
    println("Valor total sem imposto: R$$valorTotalSemImposto")
    println("Valor do imposto: R$$valorImposto")
    println("Valor total com imposto: $valorTotalComImpostoFormatado")
    println("Preço de venda sugerido: $precoVendaFormatado")
    println(mensagemFinal)
}
