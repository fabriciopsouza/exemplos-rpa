#RPA CONSULTAR O VALOR DO DOLAR NO GOOGLE CHROME EM 2K
#importa biblioteca autogui
import pyautogui as posicaoAbrirGoogle

#tempo de espera para o computador pensar
posicaoAbrirGoogle.sleep(2)

#abre o menu iniciar
posicaoAbrirGoogle.moveTo(x=488, y=1411)
posicaoAbrirGoogle.click(x=488, y=1411)

#tempo de espera para o computador pensar
posicaoAbrirGoogle.sleep(2)

#Digita nome do programa desejado
posicaoAbrirGoogle.typewrite('google chrome')

#captura posicao do programa desejado
print(posicaoAbrirGoogle.position())

#move para posicao do programa pesquisado e clica
posicaoAbrirGoogle.moveTo(x=943, y=865)
posicaoAbrirGoogle.click(x=943, y=865)

#tempo de espera para o computador pensar
posicaoAbrirGoogle.sleep(2)

#move para perfil chrome e clica
posicaoAbrirGoogle.moveTo(x=1189, y=782)
posicaoAbrirGoogle.click(x=1189, y=782)

#move para caixa de texto do chrome, clica e digita
posicaoAbrirGoogle.moveTo(x=177, y=65)
posicaoAbrirGoogle.click(x=177, y=65)

#tempo de espera para o computador pensar
posicaoAbrirGoogle.sleep(2)

#digita na caixa de pesquisa o que deseja
posicaoAbrirGoogle.typewrite('dolar hoje')

#tempo de espera para o computador pensar
posicaoAbrirGoogle.sleep(2)

#Dar enter e executar a pesquisa
posicaoAbrirGoogle.press('enter')
