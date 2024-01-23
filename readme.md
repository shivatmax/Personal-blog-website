# Personal Notion Blog Web

## Contents
- [Introduction](#-introduction)
- [Demo](#-demo)
- [Features](#-features)

## 🚀 Introduction
This is a blog template that uses Notion as CMS.<br>
Upload posts in Notion, share them through your blog!<br>
**This project uses `App Router` that is now stable in Next.js 13.4.**

## 👀 Demo
Check out the demo site [HERE](https://decoders.vercel.app/blog)

## 🌟 Features
- Simple to sync Notion and blog
- Search posts by name
- Filter posts by categories
- Related posts
- Dark mode
- Responsive design
- Sitemap

## 📦 Major Package Dependencies
- [react-notion-x](https://www.npmjs.com/package/react-notion-x): Renderer for notion pages
- [notion-client](https://www.npmjs.com/package/notion-client): Unofficial Notion API which is much faster than official Notion API

**Slug should be unique because it's used as url of the post page**

### Environment Variables
`NOTION_DATABASE_ID`: getting started step 3<br>
`NOTION_AUTH_TOKEN`: getting started step 4<br>
`SITE_URL`: URL of your site (http://localhost:3000 in local environment)<br>
`API_KEY`: Choose your own password for route handler
