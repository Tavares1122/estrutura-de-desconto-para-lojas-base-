# estrutura-de-desconto-para-lojas-base-

preço = float(input('digite o preço do produto:'))
novo = preço - (preço * 5 / 100)
print('o novo valor com 5% de desconto é de R${:.2f}'.format(novo))


#$$$$$$$$$$$$=========

preço = float(input('digite o preço do produto:'))
novo = preço - (preço * 5 / 100)
print('o antigo preço era de {:.2f}, com o desconto fica {:.2f}'.format(preço, novo))
