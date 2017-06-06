###Linux命令行中常用命令（文件的增删改查）:
#####1.cd：
  该命令用来切换当前目录，cd为change directory的缩写
#####2.pwd：
显示工作目录的路径名称，pwd为print working directory的缩写
#####3.mkdir：
创建目录，mkdir为make directory的缩写
mkdir -p： -p 参数为parents ，例如：mkdir -p a/b/c，在a中创建b目录，b中创建c目录。（若原先没有b目录，则会创建一个b目录）
#####4.ls：
该命令用来显示当前目录的内容
ls -a： -a参数为all 查看当前目录内的所有内容
ls -l：详细查看当前目录内所有内容的详细信息，包括文件的执行权限，创建时间等等
ls -al：ls -a与ls -l命令的结合
#####5.echo：
该命令用来在显示器上显示一段文字
特殊用法：
echo qwer > a.txt；将 qwer 为内容输出到文件 a.txt 中
echo  qwer >! a.txt；将qwer为内容强制覆盖到a.txt 中
echo qwer >> a.txt;将qwer写入a.txt原有的内容之后（追加内容）
#####6.touch：
该命令用来创建文件或修改文件更新时间
#####7.cp：
该命令用来复制文件
例：cp x.txt y.txt,将x.txt复制为y.txt
#####8.mv：
该命令用来移动重命名文件/目录
#####9.rm：
该命令用来删除文件/目录
rm -f：参数-f为force，指强制删除文件
rm -r：参数-r为recursive（递归），在删除目录时使用，指递归进入目录中删除其中的内容，只有目录内是空的，才可删除该目录
rm -rf：-r -f的结合，指强制删除目录
#####10.cat
该命令用来显示文件内容
例：cat 1.txt 显示1.txt的文件内容