# Laravel Forum Website  

This project is a **forum platform** built with **Laravel**, designed to provide an interactive environment where users can create discussions, share ideas, and engage with others.  

## Features  

- **User Authentication**: Register, login, and manage accounts.  
- **Discussion System**: Create topics and post comments.  
- **Voting Mechanism**: Upvote or downvote discussions and comments.  
- **Admin Dashboard**: Manage users, topics, and comments with ease.  

## Installation  

1. Clone the repository:  
```bash
git clone https://github.com/ahmetfarukyasar/webforum.git
```  

2. Install dependencies:  
```bash
composer install
npm install
npm run dev
```  

3. Set up environment file and application key:  
```bash
cp .env.example .env
php artisan key:generate
```  

4. Run database migrations:  
```bash
php artisan migrate
```
