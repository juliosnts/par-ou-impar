# par-ou-impar
def par_ou_impar(numero):
    if numero %2 == 0:
        return "par"
    else:
        return "impar"
    
numero = 5

resultado= par_ou_impar(numero)

print(f"o numero {numero} é {resultado}")


