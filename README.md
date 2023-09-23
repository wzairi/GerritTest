# GerritTest

1) Clone repo (When Using https://review.gerrithub.io please use the below command) 
#git clone "ssh://wzairi@review.gerrithub.io:29418/wzairi/GerritTest" && (cd "GerritTest" && f=`git rev-parse --git-dir`/hooks/commit-msg ; mkdir -p $(dirname $f) ;
curl -Lo $f https://review.gerrithub.io/tools/hooks/commit-msg ; chmod +x $f)
2)Make changes 
3)Upload for review on gerrithub
git push origin HEAD:refs/for/main




