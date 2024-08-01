Basic Instructions for GitHub Usage

    git clone

    git add .

    git commit -m "ooo"

    git push,  git pull

test ssh:  ssh -T git@github.com

generate ssh-keygen:  ssh-keygen

config file:  ~/.ssh/config

    Host github.com
    HostName github.com
    User hhwang01
    IdentityFile ~/.ssh/id_rsa

change protocol:  

    git remote set-url origin git@github.com:hhwang01/test_Rep1.git


Ref 1  【Github Git】超白話簡單入門
        https://emtech.cc/post/github-and-git/

Ref 2  【Git教學】手把手 Github SSH 連線設定教學
        https://www.maxlist.xyz/2022/12/22/github-ssh-setting/

Ref 3  【Git】使用 SSH 金鑰與 GitHub 連線
        https://cynthiachuang.github.io/Generating-a-Ssh-Key-and-Adding-It-to-the-Github/

Ref 4  如何設定在本機設定 github 帳戶
        [https://cynthiachuang.github.io/Generating-a-Ssh-Key-and-Adding-It-to-the-Github/](https://g0v.hackmd.io/@tmonk/HJ5r_et2B)
