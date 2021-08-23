# Módulos importados
import qrcode, image

url = input('Digite uma URL: ')
nome = input('Digite o nome do arquivo: ')

# Cria e salva o qrcode
imagem = qrcode.make(url)
imagem.save(nome+'.png')
