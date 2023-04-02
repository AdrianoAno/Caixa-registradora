#Programando uma caixa registradora

valor = 0
quantidade = 0
preço = 0

print(f"{'-Aproxime o produto ao leitor-' : >70}")

preço = float(input("\nPreço: R$ "))

while (preço > 0.0):
    valor = valor + preço
#soma a quantidade de itens comprados
    quantidade = quantidade + 1
# Mensagem ociosa
    print(f"{'-Aproxime o produto ao leitor-' : >70}")
#Leitura do valor
    preço = float(input("\nPreço: R$ "))

#digite 0 para encerrar
print("\nValor total da compra: R$ {:.2f}".format(valor))
print("Quantidade de itens comprados: {}" .format(quantidade))
