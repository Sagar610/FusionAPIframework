# FusionAPIframework 🚀

FusionAPIframework is a **high-performance**, **modular**, and **extensible** framework for building modern APIs. Built on **Fastify**, it comes with **built-in plugins** for common API features like authentication, caching, rate limiting, and more. Whether you're building a simple REST API or a complex real-time application, FusionAPIframework has you covered.

---
## **About the Developer**

FusionAPIframework is developed and maintained by [ **sagar gondaliya** ](https://www.linkedin.com/in/sagar-gondaliya/), a passionate developer dedicated to creating tools that make API development faster, easier, and more efficient. If you have any questions or feedback, feel free to reach out!

## **Features**

FusionAPIframework is packed with features to make API development faster, easier, and more efficient:

- **Modular Design**: Use only the plugins you need.
- **High Performance**: Built on Fastify for blazing-fast performance.
- **Extensible**: Add custom plugins and dependencies.
- **Built-in Plugins**:
  - Authentication (JWT + OAuth)
  - Caching (In-Memory + Redis)
  - Rate Limiting
  - File Uploads
  - GraphQL Support
  - WebSocket Support
  - Advanced Security (CSRF, CORS)
  - Interactive API Docs (Swagger)
  - Task Queues
  - Serverless Deployment

---

## **Comparison Table**

Here’s how FusionAPIframework compares to other popular frameworks:

| Feature                          | Express.js | Fastify | NestJS | FusionAPIframework |
|----------------------------------|------------|---------|--------|--------------------|
| **Core Framework**               | ✅         | ✅      | ✅     | ✅                 |
| **Performance**                  | Medium     | High    | Medium | High               |
| **Modularity**                   | ❌         | ✅      | ✅     | ✅                 |
| **Plugin System**                | ❌         | ✅      | ❌     | ✅                 |
| **Dependency Injection**         | ❌         | ❌      | ✅     | ✅                 |
| **Built-in Authentication**      | ❌         | ❌      | ❌     | ✅ (JWT + OAuth)   |
| **Real-Time WebSocket**          | ❌         | ❌      | ✅     | ✅                 |
| **Rate Limiting**                | ❌         | ❌      | ❌     | ✅                 |
| **Caching**                      | ❌         | ❌      | ❌     | ✅ (In-Memory + Redis) |
| **GraphQL Support**              | ❌         | ❌      | ✅     | ✅                 |
| **GraphQL Subscriptions**        | ❌         | ❌      | ✅     | ✅                 |
| **Interactive API Docs**         | ❌         | ❌      | ✅     | ✅ (Swagger)       |
| **Zero-Config Setup**            | ❌         | ❌      | ❌     | ✅                 |
| **File Uploads**                 | ❌         | ❌      | ❌     | ✅                 |
| **Database Integration**         | ❌         | ❌      | ✅     | ✅                 |
| **Webhook Support**              | ❌         | ❌      | ❌     | ✅                 |
| **Serverless Support**           | ❌         | ❌      | ❌     | ✅                 |
| **CLI Tool**                     | ❌         | ❌      | ❌     | ✅                 |
| **Advanced Security Features**   | ❌         | ✅      | ✅     | ✅                 |
| **Built-in Task Queue**          | ❌         | ❌      | ✅     | ✅                 |
| **Built-in Real-Time Analytics** | ❌         | ❌      | ✅     | ✅                 |

---

## **Installation**

Install FusionAPIframework globally using npm:

```bash
npm install -g fusionapiframework
```

---

## **Getting Started**

### **1. Create a New Project**
Use the FusionAPIframework CLI to scaffold a new project:

```bash
fusion-cli init my-project
```

### **2. Run the Project**
Navigate to the project directory and start the server:

```bash
cd my-project
node index.js
```

Your FusionAPIframework server will be running at `http://localhost:3000`.

---

## **Usage**

### **Basic Example**
```javascript
const FusionAPIframework = require('fusionapiframework');
const app = new FusionAPIframework();

app.start(3000);
```

### **Using Plugins**
FusionAPIframework supports plugins for adding features like authentication, caching, and more.

```javascript
const FusionAPIframework = require('fusionapiframework');
const authPlugin = require('fusionapiframework-auth');
const cachePlugin = require('fusionapiframework-cache');

const app = new FusionAPIframework();
app.use(authPlugin);
app.use(cachePlugin);

app.start(3000);
```

---

## **Plugins**

### **Authentication**
FusionAPIframework supports **JWT** and **OAuth** authentication.

```javascript
const authPlugin = require('fusionapiframework-auth');
app.use(authPlugin);
```

### **Caching**
FusionAPIframework supports **in-memory caching** and **Redis** for distributed caching.

```javascript
const cachePlugin = require('fusionapiframework-cache');
app.use(cachePlugin);
```

### **File Uploads**
FusionAPIframework makes it easy to handle file uploads.

```javascript
const fileUploadPlugin = require('fusionapiframework-file-upload');
app.use(fileUploadPlugin);
```

### **GraphQL**
FusionAPIframework supports **GraphQL** and **GraphQL subscriptions**.

```javascript
const graphqlPlugin = require('fusionapiframework-graphql');
app.use(graphqlPlugin, { typeDefs, resolvers });
```

### **WebSocket**
FusionAPIframework supports **real-time communication** with WebSockets.

```javascript
const websocketPlugin = require('fusionapiframework-websocket');
app.use(websocketPlugin);
```

---

## **Documentation**

For detailed documentation, visit the [FusionAPIframework Documentation Website](#).

---

## **Contributing**

We welcome contributions! Please read our [Contributing Guide](CONTRIBUTING.md) to get started.

---

## **License**

FusionAPIframework is licensed under the [MIT License](LICENSE).
```

---

### **Key Changes Made**
1. **Package Name**: Replaced `FusionAPI` with `FusionAPIframework` everywhere in the document.
2. **Installation Command**: Updated the installation command to use `fusionapiframework`:
   ```bash
   npm install -g fusionapiframework
   ```
3. **Require Statements**: Updated all `require` statements to use `fusionapiframework`:
   ```javascript
   const FusionAPIframework = require('fusionapiframework');
   ```
4. **Plugin Names**: Updated plugin names to use `fusionapiframework` as the prefix:
   - `fusionapiframework-auth`
   - `fusionapiframework-cache`
   - `fusionapiframework-file-upload`
   - `fusionapiframework-graphql`
   - `fusionapiframework-websocket`

---

