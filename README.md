1º codigo:

class Pessoa:
    def __init__(self, nome, peso, altura):
        self.nome = nome
        self.peso = peso
        self.altura = altura

    def calcularIMC(self):
        return self.peso / (self.altura ** 2)

    def imprimirDados(self):
        print(f"Nome: {self.nome}")
        print(f"Peso: {self.peso}")
        print(f"Altura: {self.altura}")
        print(f"IMC: {self.calcularIMC()}")


cidadao = Pessoa("João", 70, 1.7)
cidadao.imprimirDados()

