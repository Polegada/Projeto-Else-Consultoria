# Projeto-Else-Consultoria

Criar uma aplicação web utilizando ReactJS com AntDesign para consumir uma API Rest
criada (por você) no Firebase (cloud firestone).


Regra de Negócio

A aplicação será para uma loja de venda de carros online, com duas funções principais: Ver os
carros ofertados e Administrar as ofertas (CRUD). Adicionar uma navbar com as duas opções:
Ofertas e Administração

CRUD de ofertas (Administração):

Ao entrar na parte administrativa da aplicação (não precisa ter autenticação/login) o usuário
verá uma tabela com as ofertas já existentes podendo filtrar por um campo de busca textual.
Cada oferta deverá conter as ações editar e excluir;
A tela deverá ter um botão para adicionar uma nova oferta, todo oferta deverá ter: Marca,
Modelo, Ano, Preço, Cor, Quilometragem, Placa, Cidade, Fotos (mais de uma) e Data de
Cadastro.


Tela de Ofertas:

Ao entrar na aplicação (não precisa ter autenticação/login) o usuário verá os vários veículos
ofertados, podendo escolher se quer a visualização em lista ou em grade. As informações
visiveis (em um card) dos veículos devem ser: 1 Foto, Preço, Marca, Modelo, Ano e número de
visualizações que o veículo recebeu.

Ao clicar no card do veículo um modal (ou outra tela) deve se abrir e mostrar todas as
informações do veículo, que são: Fotos (mais de uma), Preço, Marca, Modelo, Ano, Cor, Placa,
Cidade, Quilometragem e Data de Cadastro. Nesse momento de abertura do modal (ou outra
tela) deve se adicionar mais 1 ao número de visualizações do veículo
