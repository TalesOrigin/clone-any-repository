git config --global user.name "TalesOrigin"
git config --global user.email "nuhamidu@gmail.com"
git init
git add .
git branch -M main
git remote add origin https://github.com/TalesOrigin/clone-any-repository.git
git remote set-url origin git@github.com:TalesOrigin/clone-any-repository.git
git commit -m "init"


set GIT_SSH_COMMAND=ssh -i my_portable_key && git push -u origin main && set GIT_SSH_COMMAND=

set GIT_SSH_COMMAND=ssh -i my_portable_key && git clone git@github.com:TalesOrigin/Frost-Engine.git && set GIT_SSH_COMMAND=


git config --global --unset user.name
git config --global --unset user.email
