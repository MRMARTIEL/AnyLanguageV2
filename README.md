# AnyLanguage  
AnyLanguage é uma ferramenta fácil de usar para arquivos .lang destinada a criadores de addons para Minecraft.

## Uso  
Visite https://solveddev.github.io/AnyLanguage/ ou baixe este repositório e abra o arquivo index.html. Os arquivos de idioma do Minecraft consistem em dois componentes: uma chave e uma tradução. Agora, insira a chave na área de texto à esquerda e, ao lado, a tradução. (Exemplo: death.fell.killer e %1$s foi condenado a cair). Você pode editar os idiomas de destino nas outras duas áreas de texto. Se adicionar um novo idioma, é necessário adicionar um nome para ele na mesma linha na área de texto à direita, a chave do idioma é a caixa de texto ao lado. Certifique-se de que o formato siga en_US, onde as duas primeiras letras representam o idioma e as duas últimas a região.  
Para gerar os arquivos de idioma, clique em "Download". A página começará a baixar todos os arquivos necessários. Certifique-se de selecioná-los todos e colocá-los na pasta resource_pack em uma pasta chamada "texts".

## Tradutor Automático  
AnyLanguage pode traduzir automaticamente seu texto para os idiomas que você selecionar. Os idiomas aceitos são os suportados pelo Google Tradutor. Certifique-se de clicar na caixa de seleção correspondente para ativar as traduções automáticas.

## Por quê?!  
A única maneira de renomear itens no Minecraft Bedrock com addons atualmente é alterando os arquivos de tradução. Para suportar todos os idiomas, você precisa editar cada arquivo .lang. Às vezes, você também quer renomear uma entidade, o que gera o mesmo volume de trabalho. Este gerador pode fazer esse trabalho desagradável por você.

## Tecnologias usadas:  
JSZip: https://stuk.github.io/jszip/  

FileSaver.js: https://github.com/eligrey/FileSaver.js/