# Desbravando-os-Ransowares-e-Keyllogers
Introdução ao estudo de vírus e criação de ferramentas de intrusão que visam o aperfeiçoamento nos conceitos de RedTeam.

# RANSOWARES:
Após realizar um estudo sobre os ransowares, demonstro que eles servem para realizar a criptografia de arquivos em computadores das vítimas.

Para isso, utilizam de um código fonte que tem por função a criação de uma ferramenta, que criptografe os arquivos do alvo, tornando, assim, inacessível o acesso à máquina da vítima.
Dessa forma, é importante entender como funcionam e como eles se introduzem em nosso cotidiano. 

Portanto, para realizar a sua criação, dividimos o código em etapas, que visam simplificar o entendimento do malware. Sendo assim, é possível classificar em **gerar uma chave**, que fará com que os arquivos tenham uma chave para serem acessados posteriormente, em seguida, devemos carregar essa chave para o nosso programa salvar as informações de recuperação dos arquivos do alvo, assim, finalmente entramos na parte de criptografia, utilizando as pastas raizes do sistema como alvo, pois é lá que se encontra as informações que queremos capturar, devendo também acrescentar um buscador para essas informações. Logo, devemos exibir uma mensagem para a vítima saber o que houve e entender que necessita pagar recuperar seus dados 
