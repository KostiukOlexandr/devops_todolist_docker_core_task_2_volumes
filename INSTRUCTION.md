# INSTRUCTION.md

## 1. Запуск MySQL контейнера з примонтованим volume
```powershell
docker run -d --name mysql-local --network todo-net -v ~/mysql-data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=rootpass -e MYSQL_DATABASE=app_db -e MYSQL_USER=app_user -e MYSQL_PASSWORD=1234 -p 3306:3306 olexandrkv/mysql-local-public:1.0.0



---

### 🔹 Повна структура `INSTRUCTION.md`
```markdown
# INSTRUCTION.md

## 1. Запуск MySQL контейнера з примонтованим volume
```powershell
docker run -d --name mysql-local --network todo-net -v ~/mysql-data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=rootpass -e MYSQL_DATABASE=app_db -e MYSQL_USER=app_user -e MYSQL_PASSWORD=1234 -p 3306:3306 olexandrkv/mysql-local-public:1.0.0
