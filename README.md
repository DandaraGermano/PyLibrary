from datetime import datetime, date, time, timedelta

resp = ''
while resp != '0':
    print('                                     ')
    print(  ' 𓂃˖˳·˖ ִֶָ ⋆📖⋆ ִֶָ˖·˳˖𓂃 ִֶ    ָ')
    print('                                     ')
    print('Bem-vindo(a) à PyLibrary!')
    print('                                     ')

    print("[ ▶︎ ]      1 - Módulo Leitor         ")
    print("[ ▶︎ ]      2 - Módulo Bibliotecário     ")
    print("[ ▶︎ ]      3 - Módulo Gêneros Textuais         ")
    print("[ ▶︎ ]      4 - Módulo Retirada de livros     ")
    print("[ ▶︎ ]      5 - Módulo Informações e horários   ")
    print("[ ▶︎ ]      0 - Sair                 ")
    print('                                             ')
    resp = input('✎𓂃Por favor, selecione o que deseja: ')

    if resp == '1':
        print()
        print("﹌﹌﹌﹌﹌﹌﹌")
        print("⬩➤ 1: Módulo leitor")
        print()
        nome = input('› Digite seu nome completo:   ')
        print()
        mat = input('› Insira o número de matrícula:    ')
        print()
        email = input('Digite seu Email:    ')
        print()
        contato = input('Digite seu número de telefone para possível contato:   ')
        print()
        print('\t ⌗ ┆ Parabéns leitor (a), você agora faz parte da PyLibrary!')
        resp2 = input('✎𓂃Por favor, selecione o que deseja:    ')
        print()
        print('                                     ')
        input('Aperte <ENTER> para continuar')

    elif resp == '2':
        print()
        print("﹌﹌﹌﹌﹌﹌﹌")
        print("⬩➤ 2: Módulo Bibliotecário")
        print()
        funcionario = input('› Digite seu cpf e respectivo cargo:   ')
        print()
        senha = input('› Digite seu login para acessar o sistema:   ')
        print()
        print('\t ⌗ ┆ Tudo certo! Pode conferir seu acesso agora!')
        print(''                          '')
        input('Aperte <ENTER> para continuar')

    elif resp == '3':
        print()
        print("﹌﹌﹌﹌﹌﹌﹌")
        print("⬩➤ 3: Módulo Gêneros textuais")
        print()
        genero = input('› Qual o gênero de livro desejas ler?')
        if genero == 'Romance':
             print('Temos 580 livros disponíveis deste estilo na biblioteca')
        elif genero == 'Fantasia':
            print('Temos 580 livros disponíveis deste estilo na biblioteca')
        elif genero == 'Terror':
                print('Temos 100 livros disponíveis deste estilo na biblioteca')
        elif genero == 'Criminal':
            print('Temos 100 livros disponíveis deste estilo na biblioteca')
        elif genero == 'Lógica de progamação':
                print('Você está com sorte! Temos apenas 1 cópia em estoque!')
        elif genero == 'Algoritmos':
            print('Você está com sorte! Temos apenas 1 cópia em estoque!')
        else:
            print('› Infelizmente não temos este estilo em estoque.')
            print('                                     ')
            input('Aperte <ENTER> para continuar')

    if resp == "4":
        print()
        print("﹌﹌﹌﹌﹌﹌﹌")
        print("⬩➤ 1: Módulo Retirada de livros")
        print()
        print('                                     ')
        identific = input('Digite seu cadastro: ')
        print('                                     ')
        print('\tProssiga para retirar seu livro')
        print('                                     ')
        livro = input('› Escreva o título da obra que deseja retirar:   ')
        print('                                     ')
        hoje = hoje = date.today()
        prazo = hoje + timedelta(days=45)
        print('                                     ')
        print('ⓘ A partir desta data de hoje, você tera este prazo para a entrega:  ', prazo)
        print('                                     ')
        print('⚠ Caso o prazo definido não seja obedecido, uma multa de R$50 será emitida ao leitor, correndo risco de suspensão de cadastro se não for paga.')
        print('                                     ')
        print('\t ⌗ ┆ Aproveite sua leitura e volte sempre!')
        print('                                     ')
        input('Aperte <ENTER> para continuar')

    if resp == '5':
        print()
        print("﹌﹌﹌﹌﹌﹌﹌")
        print("⬩➤ 5: Módulo Informações e horários")
        print()
        print('                                     ')
        print('. ݁₊ ⊹ Funcionamos de Segunda a Sábado, das 8:00 até às 22:00, sem horário de almoço .ᐟ')
        print(""" Regras de nossa instituição: 
            ╰┈➤  Proibido fumar ;
                 Manter o silêncio em todos os horários ;
                 Tenha zelo por nossos livros, leitores depois de você também os lerão ;
                 Em caso de roubo, tomaremos todas as providências cabíveis, sujeito à denúncia policial ;
                 E uma boa leitura a todos!! ࿐ ࿔* """)
        print('                                     ')
        input('Aperte <ENTER> para continuar')

if resp == "0":
    print()
    print("﹌﹌﹌﹌﹌﹌﹌")
    sair = input('⬩➤       Volte sempre, nossos livros estarão no seu aguardo!')
    print()
    print('                                     ')
    input('Aperte <ENTER> para continuar')

print('                                     ')
print(" › Fim do programa! Espero que goste! ᯓ★ ")
