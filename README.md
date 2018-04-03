# Instalação do OpenCV para a Linguagem C++ no Linux

- O arquivo `install_opencv.sh` realiza a instalação da última versão do OpenCV, automaticamente, para ser utilizado em conjunto com a linguagem C++.

- Para realizar essa instalação, primeiro clone esse arquivo no seu computador. Para isso, por meio do Terminal, execute o comando abaixo no diretório desejado:

    * `git clone https://github.com/walissonsilva/opencv-install.git`

> OBS.: Caso você não possua o _git_ instalado no seu computador, o comando acima apresentará um erro. Para resolver esse problema instale o _git_ com o comando `sudo apt install git`.

- O próximo passo é dar permissão para que o arquivo `install_opencv.sh` seja executado. Para isso, execute o seguinte comando:

    * `sudo chmod +x install_opencv.sh`

> **ATENÇÃO!** Para executar o próximo passo é necessário que você esteja logado como _root_! Para isso, execute o comando `sudo su` no Terminal e, em seguida, informe a sua senha.

- Pronto! Agora execute esse _script_ com o comando abaixo:

    * `./install_opencv.sh`