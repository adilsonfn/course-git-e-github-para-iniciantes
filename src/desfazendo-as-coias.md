* git checkout `volta a versão da branch master`
* git reset HEAD nomedoarquivo `tira do stage`
* git reset --soft hash do commit `volta o commit para o stage com base no hash, de baixo para cima no commit do hash os demais acima irão sumir e os arquivos voltarão no stage`
* git reset --mixed hash do commit`faz o mesmo comando do --soft so que os arquivos voltam um nível antes do stage`
* git reset --hard hash do commit `mesmo comando do --soft porém mata o commit e os arquivos voltando ao hash apontado`