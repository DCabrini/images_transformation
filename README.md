# images_transformation

# Conversão de Imagens em Tons de Cinza e Binarização
Este projeto realiza a conversão de imagens coloridas para tons de cinza e, posteriormente, para uma versão binarizada (preto e branco). Foi desenvolvido sem o uso de bibliotecas específicas para manipulação direta de imagens, proporcionando um entendimento mais aprofundado sobre o processamento de imagens em Python.

# Objetivo
O objetivo do projeto é:

Converter uma imagem colorida (RGB) em tons de cinza, utilizando a fórmula de luminosidade.
Binarizar a imagem convertida, reduzindo-a para apenas duas cores: preto e branco.
Exibir as imagens processadas sem alterações de orientação ou rotação indesejadas.

# Conversão para Tons de Cinza
A conversão utiliza a fórmula de luminosidade para calcular o valor em tons de cinza:

Cinza = 0.2989×R + 0.5870×G + 0.1140×B

Isso atribui diferentes pesos às componentes RGB, refletindo a percepção humana de luminosidade.

# Binarização
Cada pixel é avaliado em relação a um limiar. Se o valor do tom de cinza for maior que o limiar, o pixel é definido como branco (255); caso contrário, é definido como preto (0).

# O programa exibirá:

A imagem original.
A imagem em tons de cinza.
A imagem binarizada (preto e branco).
