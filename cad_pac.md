
# cadastrar os paciente

def cadastro_paciente():
    nomes = []
    emails = []
    telefone = []
    rgs = []
    cpfs = []
    cep = []
    enderecos = []
    numeros = []
    bairros = []
    cidades = []
    uf = []
    cns = []
    med_assist =[]

while (True):

    print('------- CADASTRO DE PACIENTE -------')

    nomes = input("Nome completo: ").upper()
    nomes.append(nomes)
    email = input("E-mail: ").lower()
    emails.append(email)
    telefone = input("Telefone: ")
    fones.append(telefone)
    rg = input("Número do RG: ")
    rgs.append(rg)
    cpf = input("Múmero do CPF: ")
    cpfs.append(cpf)
    cep = input("CEP: ")
    cep.append(cep)        
    endereco = input("Endereço: ").upper()
    enderecos.append(endereco)
    numero = input('Número: ')
    numeros.append(numero)
    bairro = input("Bairro: ").upper()
    bairros.append(bairro)
    cidade = input("Cidade: ").upper()
    cidades.append(cidade)
    uf = input("UF: ").upper()
    ufs.append(uf)
    cns = input("Número do Cartão SUS: ")
    cns.append(cns)
    med_assist= input("Nome do médico assistente: ").upper()
    med_assist.append(med_assist)
