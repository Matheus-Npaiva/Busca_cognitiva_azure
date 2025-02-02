# Busca cognitiva Azure
## Dentro do portal do Azure
Primeiro pesquise por 'Azure AI services' e procure por 'create' e crie um diretório.
<div align="center">
 <img src="https://github.com/user-attachments/assets/66b1d5c4-6f81-47e1-b33d-ad0d6034573b" width="700px" />
</div>

Dentro do 'create' dê um nome e selecione o pacote para usar, neste exemplo eu selecionei o pacote de 15 GB, quanto maior mais caro será.
Após criar volte para a tela principal do portal Azure e procure por 'AI search' e também crie um diretório igual ao anterior, são parecidos, porém são necessários, perceba o nome diferente nas imagens.
<div align="center">
 <img src="https://github.com/user-attachments/assets/bb8a0161-949e-4218-8303-2fa15614ec64" width="700px" />
</div>


Depois de criados os 2 diretórios e ainda dentro do portal do Azure procure por 'Storage accounts' e crie um novo storage.
<div align="center">
 <img src="https://github.com/user-attachments/assets/d88292f6-84a2-4fbc-a23e-66b5c80dbe24" width="700px" />
</div>

Em redundancy selecione a opção 'LRS', após criar seu storage selecione-o e na aba a esquerda procure por 'Configuration' e habilite a função 'Allow blob anonymous acess' que estará desabilitada e não esqueça de salvar.
Na aba a esquerda procure por 'Containers' e crie um novo container. em seu novo container selecione a opção ilustrada abaixo:
<div align="center">
 <img src="https://github.com/user-attachments/assets/68cc318c-4a2a-4277-a213-6a775daeaac9" width="700px" />
</div>

Em seu novo container clique em 'Upload' para inserir seu conjunto de dados. O conjunto de dados usado neste exemplo é fornecido pela própria microsoft e estão neste link `https://aka.ms/mslearn-coffee-reviews`.
Volte para o portal do Azure e procure por 'AI search' e selecione o diretório que foi criado anteriormente, dentro deste diretório vamos importar os dados clicando em 'Import' como ilustrado abaixo:

<div align="center">
 <img src="https://github.com/user-attachments/assets/fda4915b-17f8-48eb-acd3-fdea13775390" width="700px" />
</div>
Dentro do 'Import' procure pelo conjunto de dados que carregamos, conforme a imagem abaixo:
<div align="center">
 <img src="https://github.com/user-attachments/assets/877aa006-8d3a-4ae7-a2ba-b807dc057d37" width="700px" />
</div>

## Fazendo nossa primeira busca

Na mesma aba onde selecionamos o 'import data' clique em 'Search explorer' e já podemos fazer nossas buscas.

<div align="center">
 <img src="https://github.com/user-attachments/assets/d837d9bc-077a-498a-a274-d26c3f423b61" width="700px" />
</div>

