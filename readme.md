# Folder Template

Folder Template é um sistema de arquivamento de pastas e arquivos de um projeto. Através dele, desejamos estruturar e manter organizado todos os arquivos de maneira mais eficaz para a equipe.

Folder Template é baseado na proposta de estrutura de arquivos feita por [Peter Vukovic](https://twitter.com/pvukovic), titulada em "How to keep your design files neat and tidy". 

[Mais informações](http://99designs.com/designer-blog/2013/02/06/how-to-keep-your-design-files-neat-and-tidy)

---

## Instalação:


## Estrutura

### Assets

Este diretório contém fotos, vetores, fontes, icones e todos elementos de design utilizado para compor o layout final. 


### Businnes

Este diretório deve conter propostas, cronograma, planejamento, slides, pautas de reuniões. Ou seja, todos documentos ou planilha que envolva o projeto.


### Client Input

Este diretório deve conter tudo que o cliente enviar durante o desenvolvimento do projeto. Trata-se dos arquivos, documentos, anotações, imagens e etc...


### Design

Este diretório contém os arquivos gráfico, ilustração, folder ou interface do usuário do projeto em trabalho. Nesta pasta, não deve conter nada além da versão atual dos arquivos de trabalho. Caso não esteja usando um controlador de versões como o [git](https://git-scm.com), mantenha os últimos arquivos enviados para aprovação separados. Ou seja, gere nova versão única e final para cada arquivo.

Para arquivos arquivos grandes, você poderá integrar seu controle de versão a partir do [Git Large FIle Storage](https://git-lfs.github.com)

Exemplos:

** Sem controlador de versões **

	-	Photoshop_01.psd
	-	Photoshop_02.psd
	-	Photoshop_03.psd		
	-	Photoshop_04.psd
	
	-	Illustrator_01.ai
	-	Illustrator_02.ai
	-	Illustrator_03.ai
	
** Com controlador de versões **

	-	Photoshop.psd
	
	-	Illustrator.ai
	

### Production

Este diretório deve conter todos os arquivos finais para entrega ao cliente. Para os projetos cujos a finalidade é impressão, esta é a pasta onde coloca-se os arquivos para pré-impressão, que podem ser enviados para a impressoa, tais como: PDF, TIFF, PNG e etc...

Para projetos web, este é o diretório onde devemos colocar os arquivos da aplicação, tais como: HTML, CSS e Javascript.

Observações: Em caso de projetos web, pode ser relacionado diretórios externos associados ao submódulo do git ou dependência.

