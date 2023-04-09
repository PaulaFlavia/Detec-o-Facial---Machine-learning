# Reconhecimento Facial dos personagens do BigBang Theory

Este projeto tem como objetivo detectar e reconhecer os personagens do seriado The Big Bang Theory em imagens utilizando a biblioteca OpenCV e o algoritmo de detecção de faces Haar Cascade.


## Instalação
Para executar o projeto, é necessário instalar as seguintes bibliotecas:

OpenCV
Numpy
TensorFlow
Matplotlib

## Como usar

Após instalar as bibliotecas necessárias, siga os seguintes passos:
Faça o download dos arquivos haarcascade_frontalface_default.xml e recognizer.yml e salve-os na mesma pasta do arquivo main.py.
Execute o arquivo main.py.
Selecione a imagem que deseja testar quando solicitado.
A imagem será exibida com os rostos detectados e os personagens reconhecidos.

## Arquivos

haarcascade_frontalface_default.xml: arquivo necessário para a detecção de faces utilizando o algoritmo Haar Cascade.
recognizer.yml: arquivo contendo o modelo de reconhecimento dos personagens treinado previamente.
main.py: arquivo principal do projeto, responsável pela detecção e reconhecimento dos personagens em uma imagem.

### Notas

O modelo de reconhecimento dos personagens foi treinado utilizando uma base de imagens de treinamento contendo fotos dos personagens Sheldon, Leonard, Penny, Raj, Amy e Bernadette.
O algoritmo de detecção de faces Haar Cascade foi treinado utilizando uma base de imagens de rostos.
O projeto foi testado utilizando imagens do seriado The Big Bang Theory contendo os personagens Sheldon, Leonard, Penny, Raj, Howard, Bernadette e Amy. No entanto, é possível que o reconhecimento não funcione corretamente em outras imagens ou com outros personagens.


## Contribuindo

Contribuições são sempre bem-vindas! Se você tiver alguma sugestão ou encontrar algum bug, por favor, abra uma issue ou um pull request.

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo LICENSE.md para obter mais detalhes.







