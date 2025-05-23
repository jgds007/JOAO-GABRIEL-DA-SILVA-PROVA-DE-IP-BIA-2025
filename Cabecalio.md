# PROVA – Introdução à Programação (BIA)
**Nome completo:** JOAO GABRIEL DA SILVA
**Matrícula:** 202504009
**E-mail institucional:** joaogabriel1@discente.ufg.br

## QUESTÃO5
### a)
O framework escolhido foi o opencv ja que ele e um framework que e especifico para trabalhar com visão computacional. E para meu projeto que seria otimo porque ele e possivel realizar o processamento de imagem, videos gravados ou ao vivo. Além de ja possuir modelos de treinamento de reconhecimento facial como o haar cascade que facilita o trabalho e não ter de desenvolver um do zero.

### b)
Uma das funcionalidades concretas do meu projeto e se capaz de detectar rostos humanos atravez de um video ao vivo (atualmente estou usanda a camera do meu proprio notebook para realizar testes). Utilizando a função `cv2.VideoCapture(1)` e criado um objeto de captura de vídeo e a denominação 1 define a webca que sera utilizada para gerar o vídeo que sera analizado.
Resumindo essa função permite que minha webcam gere um video par ser analizado.
O video e lido frame por frame para ajudar na detecção.
Utilisamos a função `cv2.cvtColor()` para converter o frame que normalmente sempre e gerado em BGR, para a escala de cores GRAY que deixa a imagem toda cinza usando a função `cv2.COLOR_BGR2GRAY`.
Por fim o Frame e analizado pelo algoritimo pre-treinado haar cascade. Esse algoritimo e treinado com um grande conjunto de imagens que são positivas e negativas do objeto que deseja detectar, para apreder as caracteristicas que distinguem o objeto do fundo. Para selecionar o haar Cascade que você deseja utilizar, use a função função `cv2.CascadeClassifier()` que seleciona o haar cascade que você deseja utilizar para classificar os frames.
Após a classificação ele desenha um retangulo no rosto da pessoa detectada utilizando o metodo `cv2.rectangle()` que pega dois pontos de um frame/imagem, que define os cantos do retangulo, definimos a cor e a espesura como entrada do frame/imagem.

### c) 
Ainda não consegui desenvolver um metodo de gerar uma id para cada pessoa e tambem não achei nada sobre como criar uma função de biometria facial para bloquear e desbloquear arquivos com o rosto de uma pessoa.
Estou pensando em olhar outras bibliotecas como face-recognition e deepface para ver se consigo algum modelo de biometria facial, mas ate agora não consegui achar nada.

## QUESTÃO4
Mesmo não conseguindo concluir o meu jogo tetris. eu achei divertido começar a tipo desenvolver meu proprio jogo, sempre fui uma pessoa que gosta de jogos, mas nunca tentei desenvolver meus proprios jogos antes. Por isso acho que me diverti bastante em "criar um jogo" eu mesmo, o sentimento de felicidade que eu senti quando descobri que a unica coisa que me atrapalhava o desenvolvimento do meu jogo era o fato de que eu comentei a variavel e toda vez que precisava utiliza-la não conseguia porque "A variavel não esta definida", so não pulei gritando de alegria porque ja estava tarde da noite. No fim eu curti essa experiencia de tentar criar o tetris mesmo que não tenha terminado a tempo e me anima a tentar criar outros tipos de jogos (talvez depois da apresentação do meu projeto final de ip possa tentar fazer algum outro jogo.).

## QUESTÃO6
Não tive tempo o suficiente para começar, mas assim como o tetris a proposta e interessante.

## Observações Finais
Foi desafiante de certa forma, mas tambem pareceu bem familiar o jeito que consegui resolver algumas questões, alem de bastante divertida.