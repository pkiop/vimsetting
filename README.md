# vimsetting

## one shot
cd ~ && git clone https://github.com/pkiop/vimsetting.git && cd vimsetting && mv .vimrc .. && cd .. && rm -rf vimsetting
mkdir -p ~/.vim/colors
cd ~/.vim/colors
curl -O https://raw.githubusercontent.com/nanotech/jellybeans.vim/master/colors/jellybeans.vim

## explain
1. cd ~

2. git clone https://github.com/pkiop/vimsetting.git

3. mv vimsetting/.vimrc ..

if permission denied
  cd vimsetting
  mv .vimrc ..
  cd ..

4. rm -rf vimsetting
