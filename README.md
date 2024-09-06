# POC_Flexbox
Prova de conceito sobre Flexbox
# Prova de conceito Flexbox

O projeto é uma prova de conceito que demonstra e especifíca cada uma das funcionalidades do Flexbox em CSS no HTML.


## Descrição

O projeto se baseia em uma prova de conceito que tem como ojbetivo comprovar a funcionalidade de cada uma das propriedades do Flexbox em CSS dentro de um código HTML. 

## Instalação
N/A


## Uso
Um flex-container é um elemento HTML x o qual ativa o layout Flexbox para todos os seus filhos diretos, que são os flex-items. O flex-container é responsável por distribuir o espaço disponível entre e ao redor dos flex-items.
![image](https://github.com/user-attachments/assets/14841b69-7a60-4689-8681-8c0c309684a5)

A propriedade flex-direction especifica a direção na qual os itens flexíveis são organizados no flex-container -

**Direction Column** - Alinha os itens verticalmente, de cima para baixo:

![image](https://github.com/user-attachments/assets/31736652-65a5-48c0-ac22-ff457267b3d1)

Direction **Column-reverse** - Alinha os itens verticalmente, mas de baixo para cima.

![image](https://github.com/user-attachments/assets/81a8bba0-b1f9-4de2-adbd-d8505335749f)

**Direction Row** - Alinha os itens horizontalmente, da esquerda para a direita:

![image](https://github.com/user-attachments/assets/068d8441-c44a-4237-9b82-9adfb0c124e1)

Direction **row-reverse** - Alinha os itens mas da direita para a esquerda:

![image](https://github.com/user-attachments/assets/ec9e1f90-2b99-473b-abc1-4e88af0581f8)

A propriedade **Flex-wrap** funciona para que os itens flexíveis serão esticados ou encolhidos para caber dentro do flex-container sem quebrar para a próxima linha.

![image](https://github.com/user-attachments/assets/82c383b0-976b-40a7-b7bf-58456dcb550b)

O Flex **wrap-reverse** faz com que os itens quebram em várias linhas ou colunas, mas a ordem de empilhamento das linhas ou colunas é invertida.

![image](https://github.com/user-attachments/assets/edbc493b-4a32-43f2-8ead-0e6ef8a2e377)

A propriedade **justify-content** controla como os itens flexíveis são alinhados e distribuídos ao longo do eixo principal do flex-container:

O Justify-center alinha os itens no centro do eixo principal:

![image](https://github.com/user-attachments/assets/15b3bbec-83a8-4097-8bb3-a2f54e3d9001)

O Justify flex-start Alinha os itens no início do eixo principal:
![image](https://github.com/user-attachments/assets/8d7e77e7-74ba-44a9-b073-43ac8731ed37)

O Justify flex-end Alinha os itens no final do eixo principal:
![image](https://github.com/user-attachments/assets/536e6011-4478-4b2a-8418-4532c83c1dca)

O Justify space-around Distribui os itens com espaçamento igual ao redor de cada item:
![image](https://github.com/user-attachments/assets/d9449f6b-5864-4de4-b555-c5838e65a522)

O Justify space-between  Distribui os itens com espaçamento igual entre eles, sem espaço extra nas bordas:
![image](https://github.com/user-attachments/assets/035a2480-8f33-4b9e-8e94-a10777a35a96)

A propriedade **align-items** define como os itens flexíveis são alinhados ao longo do eixo transversal dentro de um flex-container:

O Align items center Alinha os itens no centro do eixo transversal:
![image](https://github.com/user-attachments/assets/a534af5e-0c1c-4fae-95eb-1c2ab717eb04)

O Align items flex-end alinha os itens no final do eixo transversal:
![image](https://github.com/user-attachments/assets/d385c043-b195-4b35-b97f-96733773ec5e)

O Align items flex-start alinha os itens no início do eixo transversal:
![image](https://github.com/user-attachments/assets/2ef54695-4ac5-49f5-a893-9d8f0d830c0d)

O Align items stretch estica os itens para preencher o container ao longo do eixo transversal:
![image](https://github.com/user-attachments/assets/4448a35c-9b3e-4d74-a4d5-79fcd076c1fe)

O Align items baseline alinha os itens com base na linha de base do texto:
![image](https://github.com/user-attachments/assets/07dd6255-9d1d-4177-950a-c25c55f3ee17)

A propriedade **order** determina a ordem na qual os itens flexíveis são exibidos dentro do flex-container:

![image](https://github.com/user-attachments/assets/259af994-1621-4e08-9cd8-afcf9f541200)

A propriedade **flex-grow** define a proporção de espaço extra que um item flexível deve ocupar em relação aos outros itens dentro do container:

![image](https://github.com/user-attachments/assets/e77fb938-271d-40b5-9274-d861e4f0ec8d)

A propriedade **flex-shrink** determina o quanto um item deve diminuir quando o espaço no container é reduzido:

![image](https://github.com/user-attachments/assets/2aa7a311-080a-4cb5-8572-90207a084ee2)

A propriedade **flex-basis** especifica o tamanho inicial de um item flexível antes que o espaço disponível no container seja alterado:

![image](https://github.com/user-attachments/assets/5d7776ae-17b8-42bb-865f-23d5bfe1322f)

A propriedade **Align-self** fornece uma maneira de alterar o alinhamento de um item específico sem afetar os outros itens no mesmo container:

![image](https://github.com/user-attachments/assets/737beb63-a7bf-4d29-9e88-fc0e52559faa)




















```bash
# Comando para executar o projeto
npm start
