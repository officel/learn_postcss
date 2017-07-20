# work history

## node.js

    ndenv versions 
    ndenv install -l
    ndenv install v8.1.4
    ndenv rehash
    ndenv global v8.1.4
    node -v

## make repos

    mkdir learn_postcss
    cd learn_postcss/
    git init
    npm init
    npm install postcss postcss-cssnext
    npm install postcss-cli --save-dev

    git add package.json 
    git add package-lock.json 
    wget https://github.com/github/gitignore/raw/master/Node.gitignore
    mv Node.gitignore .gitignore
    git add .gitignore 

## add modules

    npm i -D  postcss-loader
    npm i -D  postcss-import
    npm i -D  postcss-filter
