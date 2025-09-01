# PEP-7

![Preview](https://github.com/rshdgvn/pep-7/blob/no-error/Screenshot%202025-09-02%20015025.png)

PEP-7 is a web application built with **Laravel**. It aims to help students improve their **Filipino vocabulary** through fun and interactive games.

---

## Features

PEP-7 includes three educational games:

1. **Text Twister** – Unscramble letters to form correct words.  
2. **Interactive Novel** – Read and interact with stories to learn vocabulary in context.  
3. **Hangman** – Classic word-guessing game to reinforce vocabulary learning.  

---

## Tech Stack

- **Backend:** Laravel 11  
- **Frontend:** Blade templates with TailwindCSS  
- **Database:** MySQL  
- **Other:** Breeze for authentication and starter UI  

---

## Installation

Follow these steps to run the project locally:

### 1. Clone the repository
```bash
git clone pep-7
cd pep-7
```
### 2. Install Dependencies
```bash
composer install
copy .env.example .env
php artisan key:generate
npm install
npm run dev
```
### 3. Run it
```bash
php artisan serve
```
