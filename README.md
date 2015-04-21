# dotfiles
 Uso
=====
>   + crear un .vimrc_local en ~/
	+ clonar el repo en ~/
	+ acceder a /dotfiles
	+ lanzar el comando ./stow-all.sh
	+ despues lanzar el comando ./sync.sh
	+ Para utilizar el completador de sintaxis YouCompleteMe:
		cd ~/.vim/plugged/YouCompleteMe
    	 ./install.sh --clang-completer

>Con esto se crearán todos los dotfiles en tu carpeta personal y se instalarán todos los plugins.

- Para ver correctamente el theme distinguished en 256 colores, poner esto en el terminal:
> export TERM=xterm-256color


** VIM
*** Dependencias:
+ tmux
+ Vim
+ Git
