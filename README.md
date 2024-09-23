# GERADOR DE QR CODE UTILIZANDO PYTHON 



![qrcode_1](https://github.com/user-attachments/assets/e80be1ac-2757-4dfa-ad5a-44b966ede7c7)


    import qrcode
    qrcode_usuario = input('Bem vindo ao gerador de QRcode, qual site você deseja gerar em QR? ')
    img = qrcode.make(f'https://{qrcode_usuario}.com')
    
    img.save('qrcode_1.png')
    
    try:
        print('Seu QRcode foi gerado!')
    
    except:
        print('Error, tente novamente')









