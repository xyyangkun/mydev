1. 先下载repo
proxychains git clone https://github.com/xyyangkun/git-repo.git


2. 使用下载版本的repo进行下载
export REPO_URL='https://github.com/xyyangkun/git-repo.git'
proxychains ./git-repo/repo init --repo-url=https://github.com/xyyangkun/git-repo.git  -u https://github.com/xyyangkun/mydev.git 
(or proxychains ./git-repo/repo init --repo-url=https://github.com/xyyangkun/git-repo.git  -u https://github.com/xyyangkun/mydev.git  -m default.xml
)

3. 同步下载
./git-repo/repo sync


4. 修改manifests
cd .repo/manifests

