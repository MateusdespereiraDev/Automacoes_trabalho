Linhas 1 até 4:
são as bibliotecas utilizadas no código, vocês terão que instalar elas, pyautogui, openpyxl e pyperclip
para ser instalada rode o comando: pip install "nome da biblioteca", no CMD do VScode, aperte CRTL + J

Linha 8:
é o endereço do arquivo dentro do seu computador, troque para cada um dos computadores

Linhas 16 até 18:
são os pontos críticos do código, as coordenadas dos clicks do mouse,
eles são dados pelos pyxel da tela, para descobrir rodem o código pixel, que ao final de sua execução
aparece a coordenadas no CMD, só trocar elas com a respectiva variável

Linhas 23 até 44:
for i in dados.iter_rows(min_row=0, values_only=True): vai ler linha por linha da planilha
min_row=0: é a linha inicial, caso dê algum erro substitua esse trecho
email: nome da variável apenas

posicao.click(botao_adcionar_lead): qual ponto será apertado
posicao.press("tab", presses=3): a tecla que será apertada e quanta vezes

pyperclip.copy(str(email)): copia o valor(conteúdo) da variável
posicao.hotkey("ctrl", "v"): cola o conteúdo

pyperclip.copy("impo"): copia a palavra "impo"