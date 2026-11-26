# Prote-o-de-Informa-es-criptografia-e-hash-com-Python
for numero in senha:
    numero = int(numero) + 1
    senha_criptografada = senha_criptografada + str(numero)
print(senha_criptografada)
in letra in senha:
def codifica(senha):
    senha_criptografada = ""
    for letra in senha:
        if "a" <= letra <= "z":
            posicao = ord(letra) - ord("a") # 0 até 25
            senha_criptografada += dicionario[posicao]
        else:
            senha_criptografada += letra
    return senha_criptografada
    def calcula_hash(senha):
    valor = 0
    for letra in senha:
        valor += ord(letra)
    return valor

print(calcula_hash("marcelo123"))
