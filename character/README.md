# GraphQuest: Exploring and Implementing GraphQL

A hands-on project to explore GraphQL using the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).  
This repository contains queries, JSON outputs, and a React/Next.js application demonstrating GraphQL data fetching, pagination, and reusable components.

---

## 📁 Repository Structure

### alx-graphql-0x00: GraphQL Queries & Outputs
- **Directory:** `character/`  
  - `character-id-1.graphql` … `character-id-4.graphql`  
  - `character-id-1-output.json` … `character-id-4-output.json`
- **Directory:** `episode/`  
  - `episode-id-1.graphql` … (additional episode queries as needed)
  
Purpose: Contains GraphQL queries for fetching characters and episodes by ID, plus their corresponding JSON outputs.


## 🛠 Installation & Setup

### 1. Clone the repository
```
git clone <https://github.com/BenTachie/alx-graphql-0x00>
cd alx-graphql-0x01/character

2. Install dependencies
npm install @apollo/client graphql
npm install @types/graphql
npm install

3. Run the development server
npm run dev

Open http://localhost:3000 to view the app.
```

## 📜 How to Run GraphQL Queries
```
Example: Fetch a character by ID
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

Generate JSON output via endpoint:
https://rickandmortyapi.com/graphql
```
## 🚀 Features
- GraphQL queries for characters and episodes (by ID and paginated list)
- Reusable components for displaying episode cards
- Dynamic pagination and data fetching
- TypeScript interfaces for type safety

## 📚 Learning Objectives

- Understand GraphQL queries and schema
Learn to query APIs with Apollo Client
- Apply GraphQL in React/Next.js environment
- Build modular, reusable, and scalable frontend components
- Manage paginated data and state effectively

## ⚡ Contributing

- Fork the repo
- Create a new branch (git checkout -b feature/my-feature)
- Make your changes
- Commit with a clear message
- Push and create a pull request

## 📄 License
MIT License

## Happy GraphQuesting! 🚀