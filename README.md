# shamoji_dotfiles

自分用のdotfileを集めたもの。  
新規PCをインストールした際に、以下の手順でインストールしてもらえれば、  
いつもの環境が手に入る。


## zsh

最初はそっけないZshでもp10kを使用すればあっという間におしゃれ便利なterminalに。

## インストール方法

### Zinit

https://github.com/zdharma/zinit

こちらにアクセスして、autoinstallを行う。

### p10k

[こちら](https://github.com/romkatv/powerlevel10k#manual-font-installation)
でフォントをダウンロードし、インストール。

Terminal上のフォントをMesloLGS NFに指定

## vimrc
Vundleのインストールが必要。

`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

を使用することでVundleがインストールされる。

## dotfileの適用

git cloneして展開すればOK

## そのあとやること

## zsh

p10kの設定を終わらせる。

## vim

`:PluginInstall`を実行する。

