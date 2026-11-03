# 率土之滨同盟打城考勤助手

React + TypeScript + Vite 的移动端界面原型。

## 本地运行
\`\`\`bash
npm install
npm run dev
\`\`\`

## 当前阶段
这是第一阶段界面原型，数据仅保存在页面内存中，刷新会重置。尚未接入多人共享数据库、真实登录和权限控制。下一阶段接入 Supabase 数据库与身份系统，再实现完整业务规则。

## 环境变量
复制 `.env.example` 为 `.env`，填写 Supabase Project URL 和 publishable/anon key。严禁把 service_role 或 secret key 放进前端。
