# laba1
export GITHUB_USERNAME=samchik7
echo $GITHUB_USERNAME
samchik7
export GIST_TOKEN=token
echo $GIST_TOKEN
alias edit = nano



mkdir -p ${GITHUB_USERNAME}/workspace
cd ${GITHUB_USERNAME}/workspace
pwd
/Users/sam/samchik7/workspace
cd ..
pwd
/Users/sam/samchik7
cd
mkdir -p workspace/tasks/
mkdir -p workspace/projects/
mkdir -p workspace/reports/
cd workspace




wget https://nodejs.org/dist/v6.11.5/node-v6.11.5-linux-x64.tar.xz
--2025-03-02 15:46:50--  https://nodejs.org/dist/v6.11.5/node-v6.11.5-linux-x64.tar.xz
Распознаётся nodejs.org (nodejs.org)… 2606:4700:10::6814:172e, 2606:4700:10::6814:162e, 104.20.22.46, ...
Подключение к nodejs.org (nodejs.org)|2606:4700:10::6814:172e|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 200 OK
Длина: 9356460 (8,9M) [application/x-xz]
Сохранение в: «node-v6.11.5-linux-x64.tar.xz»

node-v6.11.5-linux- 100%[===================>]   8,92M  15,8MB/s    за 0,6s    

2025-03-02 15:46:51 (15,8 MB/s) - «node-v6.11.5-linux-x64.tar.xz» сохранён [9356460/9356460]
tar -xf node-v6.11.5-linux-x64.tar.xz
rm -rf node-v6.11.5-linux-x64.tar.xz
mv node-v6.11.5-linux-x64 node









ls node/bin
node	npm
echo ${PATH}
/opt/homebrew/bin:/opt/homebrew/sbin:/Users/sam/.brew/bin:/usr/local/bin:/Library/Frameworks/Python.framework/Versions/3.12/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin:/Library/Apple/usr/bin:/usr/local/share/dotnet:~/.dotnet/tools
export PATH=${PATH}:`pwd`/node/bin
/opt/homebrew/bin:/opt/homebrew/sbin:/Users/sam/.brew/bin:/usr/local/bin:/Library/Frameworks/Python.framework/Versions/3.12/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin:/Library/Apple/usr/bin:/usr/local/share/dotnet:~/.dotnet/tools:/Users/sam/node/bin
mkdir scripts
mkdir scripts
cat > scripts/activate<<EOF
heredoc> export PATH=\${PATH}:`pwd`/node/bin
heredoc> 
EOF
source scripts/activate




sudo gem install gist
Successfully installed gist-6.0.0
Parsing documentation for gist-6.0.0
Done installing documentation for gist after 0 seconds
1 gem installed




(umask 0077 && echo ${GIST_TOKEN} > ~/.gist)


