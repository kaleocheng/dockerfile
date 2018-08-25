FROM debian
RUN apt update && apt install -y vim git curl python3 python3-pip
RUN pip3 install yapf pylint
RUN curl -fLo /root/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
COPY vimrc /root/.vimrc
RUN vim +PlugInstall +qall
