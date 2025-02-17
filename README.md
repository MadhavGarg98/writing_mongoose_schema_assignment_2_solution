# Blog Application - MongoDB Schema

## Overview
This project defines a MongoDB schema for a blog application using Mongoose. It enables creating, storing, and managing blog posts and comments while ensuring data validation and efficient queries.

## Features
✅ **Validation Rules**  
- Titles must be unique and have a minimum length of 5 characters.  
- Content must have a minimum length of 50 characters.  
- Categories are restricted to predefined values.  

✅ **Embedded Comments**  
- Comments are stored as subdocuments inside blog posts.  

✅ **Timestamps**  
- `createdAt` and `updatedAt` are automatically managed.  

---

## 📂 Project Structure
