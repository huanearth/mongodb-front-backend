# 启动后端

npm start

## 验证

http://localhost:8080

# 启动前端
pnpm install
npm install --no-optional --legacy-peer-deps
pnpm run serve

## 验证

http://localhost:3000/public/getCaptcha

# 启动数据库容器

docker-compose -f docker-compose.dev.yml up -d

# 查看状态

docker-compose -f docker-compose.dev.yml ps

# 查看日志

docker-compose -f docker-compose.dev.yml logs -f mongodb
