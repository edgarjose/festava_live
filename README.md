# Festava Live — ficheiros estáticos para laboratórios

Website de demonstração baseado no template **Festava Live, TemplateMo 583**. Este repositório contém os ficheiros HTML, CSS, JavaScript, imagens e vídeo usados nos meus exercícios de alojamento em AWS e Docker.

O design e os conteúdos do template são da TemplateMo e dos respetivos autores dos recursos; este repositório não apresenta o template como um design original meu.

## Abrir localmente

Abrir `index.html` no browser. Não é necessário instalar pacotes nem executar um build. A segunda página é `ticket.html`.

| Diretório | Conteúdo |
| --- | --- |
| `css/` | Bootstrap, ícones e estilos do template |
| `js/` | Scripts do template, Bootstrap e jQuery |
| `images/` | Fotografias usadas pelas páginas |
| `fonts/` | Ficheiros de ícones |
| `video/` | Vídeo de fundo |

## Limites da demonstração

Os formulários usam `action="#"`: não existe backend de contacto, compra, pagamentos ou emissão de bilhetes. Não inserir dados pessoais ou interpretar uma submissão como uma compra real. Alguns links são exemplos do template. Google Fonts e o mapa incorporado dependem de acesso à internet.

## Usar num laboratório

- [Apache numa instância EC2](https://github.com/edgarjose/deploy-static-website-on-aws)
- [Imagem Docker para publicar no ECR/ECS](https://github.com/edgarjose/ecr-ecs-docker-website-project)
- [Website com CloudFormation](https://github.com/edgarjose/aws-cloudformation-static-project)

Ao descarregar um arquivo do GitHub, copiar o conteúdo de `festava_live-main/` para a raiz do servidor web, não a pasta exterior inteira. A branch `main` pode mudar; para uma execução reproduzível, fixar uma revisão do repositório.

## Atribuição e reutilização

Consultar [o template original](https://templatemo.com/tm-583-festava-live) e os termos aplicáveis aos ficheiros de terceiros antes de reutilizar ou redistribuir os recursos. Este README não concede uma licença nova sobre esses materiais.

Parte dos exemplos publicados em [Edgar's Cloud Notes](https://www.edgarcloudnotes.com/).
