# Criar um aplicativo de consulta a API do [GitHub](https://github.com)#

Criar um aplicativo para consultar a [API do The Movie Database](https://developers.themoviedb.org/3/getting-started/introduction/) e trazer os filmes mais populares. Basear-se no mockup fornecido:

![Captura de tela de 2015-10-22 11-28-03.png](https://bitbucket.org/repo/7ndaaA/images/3102804929-Captura%20de%20tela%20de%202015-10-22%2011-28-03.png)

### **Deve conter** ###

- __Lista de filmes__. Documentado na página: `https://developers.themoviedb.org/3/movies/get-popular-movies`
  * Ao tocar em um item, deve levar a lista de Pull Requests do repositório
- __Detalhes do filme__. Documentado na página: `https://developers.themoviedb.org/3/movies/get-movie-details`
  * Cada item da lista deve exibir Nome / Foto do autor do PR, Título do PR, Data do PR e Body do PR
  * Ao tocar em um item, deve abrir no browser a página do Pull Request em questão

### **Ganha + pontos se conter** ###

* Framework para comunicação com API
* Testes no projeto (unitários)
* Cache de imagens e da API

### **Sugestões** ###

As sugestões de bibliotecas fornecidas são só uma orientação, sinta-se a vontade para usar alguma outra. O importante de fato é que o objetivo seja atingido. =)

* Retrofit
* Picasso | Universal Image Loader | Glide

### **OBS** ###

A foto do mockup é meramente ilustrativa.  


### **Processo de envio** ###

O candidato deverá implementar a solução e enviar um pull request para este repositório com a solução.

O processo de Pull Request funciona da seguinte maneira:

1. Candidato fará um fork desse repositório (não irá clonar direto!)
2. Fará seu projeto nesse fork.
3. Commitará e subirá as alterações para o __SEU__ fork.
4. Pela interface do Github, irá enviar um Pull Request.

Se possível deixar o fork público para facilitar a inspeção do código.

### **ATENÇÃO** ###

Não se deve tentar fazer o PUSH diretamente para ESTE repositório!
