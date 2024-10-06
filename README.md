<div align="center" id="top"> 
  <img src="https://thumbs.gfycat.com/WeightyDopeyCats-size_restricted.gif" alt="Blazor"/>

&#xa0;

  <!-- <a href="https://blazor.netlify.app">Demo</a> -->
</div>

<h1 align="center">Blazing Pizza</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/Jose1060/blazor?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/Jose1060/blazor?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Jose1060/blazor?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/{Jose1060/blazor?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/{{YOUR_GITHUB_USERNAME}}/blazor?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/{{YOUR_GITHUB_USERNAME}}/blazor?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/{{YOUR_GITHUB_USERNAME}}/blazor?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center">
	🚧  Blazor 🚀 Under construction...  🚧
</h4>

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">Author</a>
</p>

<br>

## :dart: About

Tutorial obtenido de https://learn.microsoft.com/en-us/training/modules/use-pages-routing-layouts-control-blazor-navigation/1-introduction

## :sparkles: Features

:heavy_check_mark: Blazon\
:heavy_check_mark: Docker\

## :white_check_mark: Requirements

Solo necesitas [Git](https://git-scm.com) y docker, se recomienda usar [Play with Docker](https://labs.play-with-docker.com/).

## :checkered_flag: Starting

```bash
# Clone this project
$ git clone https://github.com/Jose1060/BlazzingPizza && cd BlazzingPizza

# Build image
$ docker build -t blz_pizza .

# psdt: el punto significa la ubicacion actual, por lo que tendremos que estar en la misma carpeta que se encuentra el dockerfile en la consola :v

# Run the project
$ docker run -it --rm -p 5200:80 --name pizzacontainer blz_pizza

# The server will initialize in the <http://localhost:5200>
# Si se esta trabajando con play with docker podra acceder con la ip publica que nos ofrece este

# Para subir la imagen a DockerHub solo necesitas crear un respositorio nuevo, en este caso se creara
# con el nombre de pizza.

# Despues se tiene que logear en nuestro espacio de trabajo, con
$ docker login -u YOUR-USER-NAME

# Creamos el Tag
$ docker tag blz_pizza YOUR-USER-NAME/blz_pizza

# Realizamos el Push
$ docker push YOUR-USER-NAME/blz_pizza

# Si queremos probar nuestra imagen, podemos crear una nueva instancia y utilizar el comando
$ docker run -dp 5200:80 YOUR-USER-NAME/blz_pizza

```

## :memo: License

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

Made with :heart: by <a href="https://github.com/Jose1060" target="_blank">Jose1060</a>

&#xa0;

<a href="#top">Back to top</a>
