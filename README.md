# gitconfig
Alias de Git

las puedo configurar bien con git config --global alias.[alias_nombre]
o desde .gitconfig
[alias]
  gl = log --graph --abbrev-commit --oneline  --decorate --all
	gl2 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%    %C(bold yellow)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)' --all
	


