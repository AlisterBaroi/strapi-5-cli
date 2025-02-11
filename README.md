# Strapi 5 Deployment to VM (CLI and Docker)

## 1. Install using CLI
### 1.1 Setup
1) Update the system
    ```
    sudo apt update && sudo apt update
    ```
2) Install Node.Js and NPM (Node Package Manager)
    ```
    sudo apt install nodejs npm
    ```
3) Create Strapi project
    ```
    npx create-strapi@latest
    ```
### 1.2 Run in Development Mode
1) Build and Run in Dev Mode
    ```
    npm run develop
    ```
2) Just Build
    ```
    npm run build
    ```
3) Just Start
    ```
    npm run start
    ```
### 1.3 Production Deployment 
1) Build for production
    ```
    NODE_ENV=production npm run build
    ```
2) Deploy at production
    ```
    NODE_ENV=production npm run start
    ```

## 2. Run Docker
