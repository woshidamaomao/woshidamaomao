<div class="language-switch">
  <button onclick="showEnglish()" id="btn-en" class="active">🇺🇸 English</button>
  <button onclick="showChinese()" id="btn-cn">🇨🇳 中文</button>
</div>

<!-- English Version -->
<div id="content-en" class="content">

# Hi! 👋 I'm Colin

> 💻 **Web Developer** | 🚀 **Indie Hacker**

## 🛠️ Tech Stack

[TypeScript](https://www.typescriptlang.org/) • [Vue](https://vuejs.org/) • [React](https://react.dev/) • [Svelte](https://svelte.dev/) • [NestJS](https://nestjs.com/) • [NextJS](https://nextjs.org/) • [Electron](https://www.electronjs.org/) • [WXT](https://wxt.dev/)

## 🏢 Work

Frontend development and browser extension technologies

## 🎯 Side Projects

**[AI Exporter](https://saveai.net/)** - AI conversation export tool with 5k+ users

## 💡 Interests

- 📚 **Reading** - Programming, History, Psychology, Business & Product, Investment
- 🎯 **Long-term Thinking** - Love doing boring things that create long-term value

## 🌐 Connect

[Website](https://saveai.net/) • [Twitter](https://x.com/ColinGo2030)

</div>

<!-- Chinese Version -->
<div id="content-cn" class="content" style="display: none;">

# Hi! 👋 我是 Colin

> 💻 **Web Developer** | 🚀 **独立开发者**

## 🛠️ 技术栈

[TypeScript](https://www.typescriptlang.org/) • [Vue](https://vuejs.org/) • [React](https://react.dev/) • [Svelte](https://svelte.dev/) • [NestJS](https://nestjs.com/) • [NextJS](https://nextjs.org/) • [Electron](https://www.electronjs.org/) • [WXT](https://wxt.dev/)

## 🏢 工作

专注于前端开发和浏览器扩展技术

## 🎯 业余项目

**[AI Exporter](https://saveai.net/)** - AI对话导出工具，安装用户 5k +

## 💡 兴趣爱好

- 📚 **阅读** - 编程技术、历史、心理学、企业和产品、投资理财
- 🎯 **长期主义** - 喜欢做枯燥但能产生长期价值的事情

## 🌐 联系方式

[Website](https://saveai.net/) • [Twitter](https://x.com/ColinGo2030)

</div>

<style>
.language-switch {
  text-align: center;
  margin-bottom: 2rem;
}

.language-switch button {
  background: #f5f5f5;
  border: 1px solid #ddd;
  padding: 8px 16px;
  margin: 0 4px;
  border-radius: 6px;
  cursor: pointer;
  font-size: 14px;
  transition: all 0.2s ease;
}

.language-switch button:hover {
  background: #e9e9e9;
}

.language-switch button.active {
  background: #007acc;
  color: white;
  border-color: #007acc;
}

.content {
  animation: fadeIn 0.3s ease;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
</style>

<script>
function showEnglish() {
  document.getElementById('content-en').style.display = 'block';
  document.getElementById('content-cn').style.display = 'none';
  document.getElementById('btn-en').classList.add('active');
  document.getElementById('btn-cn').classList.remove('active');
}

function showChinese() {
  document.getElementById('content-en').style.display = 'none';
  document.getElementById('content-cn').style.display = 'block';
  document.getElementById('btn-en').classList.remove('active');
  document.getElementById('btn-cn').classList.add('active');
}
</script>
