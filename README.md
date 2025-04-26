# 🚀 Simple GraphQL Server using Apollo Server and Express

## 📚 About This Project
This project helps you set up a **GraphQL server** using **Apollo Server 4** and **Express.js** in a beginner-friendly way.

It allows you to query a static list of users and learn the basics of GraphQL API building.

## 🛠 Tech Stack
- **Node.js**
- **Express.js**
- **Apollo Server (@apollo/server)**
- **GraphQL**

## 📂 Project Structure
- `/schema/type-defs.js`
- `/schema/resolver.js`
- `fakedb.js`
- `server.js`
- `.env`
- `package.json`

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone <repository-link>
cd <project-folder>
```
## 2. Install dependencies

```bash
npm install
```
## 3. Environment Variable

Create a `.env` file and add:

```env
APP_SERVER=http://localhost
```
## 4. Start Server
```bash
node server.js
```
## 📡 After Running the Server

Your server will be live at:

**[http://localhost:8000/graphql](http://localhost:8000/graphql)**

---

# 📡 GraphQL API

You can access the **GraphQL Playground** at:

**[http://localhost:8000/graphql](http://localhost:8000/graphql)**

---

## 📋 Example Query

```graphql
query {
  users {
    id
    name
    country
  }
}
```
