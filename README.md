# zy-common-tool
格式化时间，获取2019-08-07 15:06:32或2019-08-07或15:06:32

# install
npm install -g zy-common-tool

#github
git@github.com:please512/npm.git

#usage
let formatter = require('./index')
formatter.init('2018-6-9')
console.info(formatter.getDateTime())