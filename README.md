# EcommercePrompt
git clone git@github.com:bianpeijiang/design_mode.git //克隆版本库
cd design_mode/
vim README.md //新建一个readme文件
git add .  //把当前目录的新建文件，添加版本库跟踪
git commit -m "init"  //提交当前分枝的版本库跟踪未提交内容，并设置备注信息为"init"
git push //推送提交内容到远程，这时会报错，提示当前分枝为master,远程为main
git branch -M main  //修改当前分枝名称为main
git push -u origin main //推送当前分枝到远程main分枝
