#ServiceFramework for Maven

对于一个以Maven为基础工具的开发团队，使用另外一种目录结构毕竟是不方便的(即使这个结构很简单)。而且一个项目没有版本号，没有依赖库的版本管理，又带来另外的一丝丝的不安全感。好在有了git，这一切都变得简单很多。


分别clone下列库：
git clone git://github.com/cheney83/active_orm.git
git clone git://github.com/cheney83/csdn_common.git
git clone git://github.com/cheney83/mongomongo.git
git clone git://github.com/cheney83/ServiceFramework.git
git clone git://github.com/cheney83/ServiceFramework4Maven.git

目录结构如下：
├── active_orm
├── csdn_common
├── mongomongo
├── ServiceFramework
└── ServiceFramework4Maven

cd ServiceFramework4Maven
mvn compile

[原始文档](https://github.com/allwefantasy/ServiceFramework)