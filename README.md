# Работа с удалённым репозиторием

## git clone — создание копии (удаленного) репозитория

Для начала работы с центральным репозиторием, следует создать копию оригинального проекта со всей его историей локально.

Клонирует репозиторий, используя протокол http:

git clone http://user@somehost:port/~user/repository/project.git
Клонирует репозиторий с той же машины в директорию myrepo:

git clone /home/username/project myrepo
Клонирует репозиторий, используя безопасный протокол ssh:

git clone ssh://user@somehost:port/~user/repository
У git имеется и собственный протокол:

git clone git://user@somehost:port/~user/repository/project.git/
Импортирует svn репозиторий, используя протокол http:

git svn clone -s http://repo/location
где -s – понимать стандартные папки SVN (trunk, branches, tags)

# git fetch и git pull — забираем изменения из центрального репозитория
