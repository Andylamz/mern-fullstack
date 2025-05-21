# MERN Product Store

This is a full stack product management application built with the MERN stack: - MongoDB Atlas - Express - React (Vite) - Node.js
The app allows users to create, read, update and delete (CRUD) products with name, price, and image URL. All data is stored remotely on MongoDB Atlas

## Features

    - Add new product with name, price, and image URL
    - Edit and delete existing products (Users can only update the fields that need to be changed, leaving fields blank will remain the same)
    - View all products on the Homepage (auto-refreshed)
    - Redux Toolkit Query handles data detching and cache invalidation
    - Reacct with Vite as frontend build tool
    - Express API connected to MongoDB Atlas

## Technologies

    - Frontend: React + Vite + RTK Query
    - Backend: Node.js + Express
    - Database: MongoDB Atlas
    - State Management: Redux Toolkit (Slice and RTK query)
    - HTTP Client: fetch via RTK Query
