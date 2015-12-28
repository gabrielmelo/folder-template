# Folder Skeleton 

Folder Skeleton é um sistema de arquivamento de pastas e arquivos de um projeto.

Através dele, desejamos estruturar e manter organizado todos arquivos relacionados a uma projeto de maneira mais eficaz para a equipe.

Folder Skeleton é um projeto baseado na proposta de estrutura de arquivos feita por [Peter Vukovic](https://twitter.com/pvukovic), titulada em How to keep your design files neat and tidy. 

Para mais informações: <http://99designs.com/designer-blog/2013/02/06/how-to-keep-your-design-files-neat-and-tidy/>

---

## Instalação:


## Estrutura:

### Client Input

Este diretório deve conter tudo que o cliente enviar durante o desenvolvimento do projeto. Trata-se dos arquivos, documentos, anotações, imagens e etc...

### Businnes

Este diretório deve conter propostas, cronograma, planejamento, slides, pautas de reuniões. Ou seja, todos documentos ou planilha que envolva o projeto.

### Assets

Este diretório contém fotos, vetores, fontes, icones e todos elementos de design utilizado para compor o layout final. 

### Design

Este diretório contém os arquivos do projeto. Nele não deve conter nada além das versões do arquivo, caso não esteja usando um controlador de versões, mantenha os últimos arquivos enviados para aprovação separados. Ou seja, gere novas versão única e final para cada arquivo.

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
Este diretório deve conter todos os arquivos finais para entrega ao cliente ou área envolvida. Para os projetos cujos a finalidade é impressão, esta é a pasta onde coloca-se os arquivos para pré-impressão, tais como: PDF, TIFF, PNG e etc...

Para projetos web, este é o diretório onde devemos colocar o guia de estilo referênte a interface, tais como: HTML, CSS e Javascript.
