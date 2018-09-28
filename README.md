# Repository
Repository连接方法


方法1：  

#创建新文件夹  

mkdir xxx  

#进入  

cd xxx  

#初始化Git仓库   

git init  

#提交改变到缓存
git commit -m 'description'
#本地git仓库关联GitHub仓库 
git remote add origin git@github.com:han1202012/TabHost_Test.git
#提交到GitHub中 
git push -u origin master

方法2：
#从GitHub上克隆项目到本地 
git clone git@github.com:han1202012/NDKHelloworld.git #注意克隆的时候直接在仓库根目录即可, 不用再创建项目根目录 ;
#添加文件 
git add ./*  # 将目录中所有文件添加;
#提交缓存 
git commit -m '提交';
#提交到远程GitHub仓库 
git push -u origin master ;

---------------------
