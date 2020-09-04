# Redimensionando partições
Tutorial para redimensionar partições em computadores com dual boot.
1. **Salvar arquivos importantes**

Antes de tudo, caso você tenha arquivos de muita importância (tanto no Linux como no Windows), salve-os na nuvem ou em outra mídia removível só por segurança.
2. Criar um pendrive bootável

Você vai precisar usar um pendrive com uma imagem ISO (vou usar o Ubuntu 18.04, mas creio que outros funcionem da mesma maneira) para poder mexer nas partições “de fora”. Você pode utilizar o mesmo pendrive que usou para instalar o Linux no seu computador (aí pode pular esse passo).
O link para baixar a ISO: 
https://releases.ubuntu.com/18.04/
Tutorial para criar o pendrive bootável pelo Ubuntu: https://www.techtudo.com.br/dicas-e-tutoriais/noticia/2017/01/veja-como-criar-um-pendrive-bootavel-ubuntu.html
Tutorial para criar o pendrive bootável pelo Windows: https://www.techtudo.com.br/dicas-e-tutoriais/2018/08/como-criar-pen-drive-bootavel-com-o-rufus-software-gratis-para-download.ghtml
3. Descobrir partições

Você precisa descobrir onde estão suas partições para saber qual aumentar e qual diminuir. rode o comando `sudo fdisk -l` no seu terminal (no Linux).
Procure pela seguinte tabela: 
![tabela](https://lh6.googleusercontent.com/Ac8Bi-Of52m8Jn-Cb2Kvarb6UicZRnawqGBbVLwSA0GxSgDJNkr17AM1wZiaqppu4OJ4hpi-lGI2kVlBSW7LFtBGUhWEcBzp9A77uU_3nL8Q4iU6DpPwUOXFE56N881n--WtR7by)

O Windows está instalado na partição com tipo “Microsoft dados básicos” e o Linux no tipo “Linux sistema de arquivos”. No meu caso, o  Linux está em /dev/sda7 e o Windows está em /dev/sda3 e em /dev/sda5 (o Windows usa duas partições de dados, a OS(:C) e a DATA(:D), você pode retirar a memória de qualquer uma das duas, mas prefira fazer da que estiver mais “embaixo”, que é a DATA (neste caso é a /dev/sda5)). Anote essas informações.
4. Abrir live

	(Nesse passo, pode ser que a BIOS do seu computador seja diferente, mas creio que os passos sejam parecidos)
	Vamos abrir o Ubuntu pelo computador pelo modo de teste (sem instalar de fato). Para isso reinicie o seu computador e na página de boot selecione ''System Setup''. Com as setas, navegue até a aba “BOOT” e selecione “add new boot option”. Ao selecionar “add boot option”, coloque um nome qualquer (só para identificar a opção do pendrive), depois selecione “path for boot option” e escolha a opção USB. Navegue por EFI -> BOOT, selecione o arquivo grubx64.efi e finaliza selecionando “create”.
	Agora vá para para a aba “save and exit” e escolha a opção que você criou na lista “Boot Override”. Vai abrir um menu com as opções, então você seleciona “try ubuntu without installing”.

5. Gerenciar partições

	Com o ubuntu no modo de teste aberto, abra o aplicativo GParted (ele vem instalado por padrão).
	Clique na partição do Windows da qual você vai tirar a memória, clique na aba “Partição” e em Redimensionar/Mover.
![gparted1](https://lh6.googleusercontent.com/fzoaENVX81n49Gz4YzGja3nSSqoGdoSb9Vny4TjiYOSY1dgpP1nX4bEvnrHKLe317Bgz81lbvOuKCaEiDbP67jV9l39ZMAOmOGigngYYXwu-v63mH6alzDPh2LVcDaGPzeQsBeoo)
    Na opção “espaço livre após”, coloque a quantidade de memória que você deseja adicionar ao Linux (você também pode ajustar movendo a seta da direita). Clique em “Redimensionar/mover” (no meu computador essa opção só fica disponível após eu clicar em outro campo).
![gparted2](https://lh5.googleusercontent.com/6HEpDm711u3coD9Yb0cvlx9AqrwOiiMC9aAxmzcPN77_Zr8l107uFgx9ul5C0kxjvOajADST67zmfBI9M98iDDc1kBTO-S2VDE7MUnrw5g8tK-2IpXVQS-5XCWhR6-jPc7O5gFB4)
*Repare que o tamanho é dado em MB (coloquei uma memória bem pequena ali para exemplificar).*
Veja que uma memória não alocada foi criada no final do seu HD.
![gparted3](https://lh3.googleusercontent.com/hQMO_8fWlOOWhjYplCCA08JTHv99en5wrXRxm_--3S8TqQF0rn1YRMVsTdoq0s-aq_v0QVuBwdRJY62UMGtrlEkvWz8wJ0DdyDGmMU9h-dBlwsvBXiD6finW0Pa1Fy6FxxLg141G)
Precisamos agora mover as outras partições para que essa memória não alocada fique à direita da partição do Linux. Vamos fazer uma por uma, selecionando a que está em cima da memória não alocada, abrindo a opção “Redimensionar/mover” e movendo a barra da memória para a esquerda, para que ela fique depois da memória não alocada (é só clicar, segurar e arrastar a barra delimitada pela borda verde). Alguns avisos serão mostrados, mas pode clicar em OK em todos.

![gparted4.1](https://lh6.googleusercontent.com/fyFS-dmsnFXnMGnPNJQ3gUlDZDUxkT89IMT5eZzWUXlaT4Z3MT1vzY0LC76Cl6s3rWe_nmC_Jpph0YIbLm0H4P3TLhz-_BJklO1GFppiKVcx6mGPc6bttB3mdsgdKNKkBZJDWZ3q) ![gparted4.2](https://lh6.googleusercontent.com/HDHBK3ScbznK0u98qu68Sgo4pRu20m4qOxxqVfvB0eP6UEvOSLHyAoFdNh-T7hPLe6AoENveWRUtI-nR3Zyeb6dyTHyFM7-Mr99wMzDd4Y2TSm0LgJ1FA3E_O1VGz5KADQkObB4B)

Vamos repetir esse processo até a memória estar ao lado da partição do linux.
![gparted5](https://lh3.googleusercontent.com/fmOyRaZoagYlXYS5gD_qIa8_h6GEcRPxyIfvUZ4bohVx9kaJsY5MaT-LDgmBoCkVlgHaJUVSgYD7tDgZ7qV7mO1iPYTwtAvckf3FAN7zRMTfcOE-ZCMo370AoIW8wBsq0sKwv3fY)
Agora vamos expandir a partição do Linux para abranger a memória não alocada, selecionando-a, clicando em “Redimensionar/mover” e arrastando a seta da direita até o final. A lista de operações pendentes vai ficar parecida com isso: 
![gparted6](https://lh4.googleusercontent.com/8YLR75fuceTd3Vf4XEs89N1dsxXnfgGI1NXfmr20DpS-1IGLbd13CVHgGVRJD66uzUyLJ8ci91BoULRZClc6TpXBZQLrq1Se7jlVSSQ)

Essa parte pode demorar bastante tempo, então mantenha seu computador ligado à uma fonte de energia, desative as opções de suspensão automática nas configurações de energia do Ubuntu e não inicie esse processo se você for precisar do computador em breve (recomendo deixar fazendo e ir dormir haha). Então é só clicar no ✅ ali em cima do gráfico de memória.
	Depois que terminar a operação, é só reiniciar o seu computador e tá pronto! 😃










