<h3 align="center">nextjs 15</h3>

## 1 Setup new project

**Installation**

Install the project:

```bash
npx create-next-app@latest ./
```

**overrides ในไฟล์ package.json ดังนี้**

ถ้ามีการกำหนดเวอร์ชัน: หาก $react, $react-dom, และ $next ถูกกำหนดให้มีค่าเป็นเวอร์ชันใหม่ใน dependencies ของโปรเจกต์ การสั่ง npm install จะทำให้ npm ติดตั้งเวอร์ชันใหม่ตามที่ระบุไว้ใน overrides

```bash
  "packageManager": "npm@10.5.2",
  "overrides": {
    "react": "$react",
    "react-dom": "$react-dom",
    "next": "$next"
  },
```

## 2 Authentication with NextAuth

- [NextAuth](https://authjs.dev/getting-started/installation)
