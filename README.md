# login
usuario = input('Nome de usuário: ')
senha = input('Sena do usuário: ')

usuario_bd = 'nycollas'
senha_bd = '123456'

if usuario_bd == usuario and senha_bd == senha:
    print('Voce está logado no sistema')
else:
    print('Usuario ou senha inválidos')
