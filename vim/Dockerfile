FROM debian
RUN apt update && apt install -y vim git curl python3
RUN curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
COPY vimrc ~/.vimrc
RUN vim +PlugInstall +qall
