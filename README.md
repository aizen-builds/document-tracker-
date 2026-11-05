# Document Tracker

A web-based document tracking system that helps you trace documents and find where each one is.

**Live site:** https://drd-document-tracker.netlify.app

![Screenshot](screenshot.png)

## Features

- Department-based access, so each department only sees its own documents
- Admin and user roles
- Preset locations for quick and consistent tracking
- Movement history showing where a document has been
- Overdue alerts for documents that are not returned on time

## Built with

- HTML, CSS, and JavaScript (single-file app)
- Supabase (database and authentication)
- Netlify (hosting)

## Setup

1. Create a project at [supabase.com](https://supabase.com).
2. Create the tables the app needs: [list your tables, e.g. documents, locations, movements, users].
3. Turn on Row Level Security and add policies so departments only see their own data.
4. Open `index.html` and replace the Supabase URL and anon/public key with your own.
5. Deploy the repo on Netlify or GitHub Pages, or open `index.html` in a browser.

> Never put your Supabase service_role key in this repo. Only the anon/public key belongs in the app.

## Usage

- **Admin:** [manage users, departments, and locations]
- **User:** [add documents, update location, view history]

## Author

Built by [your name or aizen-builds].
