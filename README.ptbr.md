[English](README.md) | Português

# Projeto de Blender de CG

Esse projeto é para a cadeira de Computação Gráfica na Faculdade (IFCE - BR)

Isto é um conceito de um carro para ser modelado e animado durante o semestre

## Como contribuir para o projeto

Primeiramente, obviamente, você tem que instalar essas ferramentas e seguir os passos que tem nos sites abaixo

-   [Git](https://git-scm.com/downloads)
-   [Git LFS](https://git-lfs.github.com/)
-   [Blender](https://www.blender.org/download/)

Para verificar se está instalado, apenas vá para seu terminal e digite (Para o Blender, basta abrir)

`git --version`

`git lfs --version`

Uma vez que você fez o clone/fork deste repositório, vá até o diretório que está o repositório e digite

`git lfs install --local`

### Por que usar o Git Large File Storage

Porque o git tem um bom controle sobre arquivos binários mas não quando está trabalhando com arquivos grandes binários, logo Git LFS faz outro ponteiro para o seu repositório somente pegar as coisas que você está trabalhando e não tem que puxar todos os commits com um arquivo grande que foi modificado (Estes ponteiros funcionam como um commit mas sempre apotando para o arquivo binário grande, fazendo sua .git ter vários ponteiros, ao invés de muitos arquivos binários grandes, levando para um pequeno repo)

[^Referências]: Sobre todas os conhecimentos e além dessa README.ptbr.md

[What is Git LFS](https://www.youtube.com/watch?v=9gaTargV5BY)

[Working with Blender, Git, and Git Large File Storage (LFS)](https://creativepolygon.com/tutorials/working-with-blender-git-and-git-large-file-storage-lfs)

### Versão do Blender

Usando a versão do Blender [v2.83.16 Windows 64x](https://download.blender.org/release/Blender2.83/blender-2.83.16-windows-x64.zip)

Mesma versão do Blender para diferentes SO [aqui](https://download.blender.org/release/Blender2.83/)

## Conclusão

Eu acho que é isto! Apenas abra seu pull request e vamos trabalhar!

[^Grupo]: Grupo do Projeto na cadeira de CG 

>   João Victor (github.com/VictorS8)
>
>   Yuri Moura (github.com/MouraYuri)
>
>   Levi Cordeiro (github.com/LeviCC8)

